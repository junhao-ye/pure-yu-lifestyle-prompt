# Pure-Yu Lifestyle Prompt Specification

## Intent

This skill generates Chinese AI image prompts for realistic adult East Asian female pure-yu lifestyle portraits. It preserves user-supplied parameters exactly, expands missing details safely, and outputs a stable prompt suitable for image generation.

## Scope

In scope:
- Adult 20-28 East Asian female lifestyle portrait prompts.
- Clean, restrained, cinematic, realistic pure-yu photo aesthetics.
- Parameter locking, module parsing, final prompt, and negative constraints.

Out of scope:
- Minors, teen-coded sexualization, school-uniform sexualization, nudity, explicit sex, pornography, fetish content, voyeurism, coercion, or instructions to intensify erotic exposure.
- CG, anime, illustration, influencer-heavy retouching, cheap lingerie-ad style, or vulgar edge content.

## Users And Trigger Context

- Primary users: prompt writers and image-generation users who want a reusable Chinese portrait-prompt generator.
- Common user requests: generate a pure-yu lifestyle photo prompt, lock supplied portrait parameters, convert parameters into a realistic female portrait prompt.
- Should not trigger for: ordinary portrait photography advice, non-female subjects, explicit adult content, image editing, or general fashion styling not framed as a prompt-generation task.

## Runtime Contract

- Required first actions: extract parameters, enforce safety boundary, and perform parameter-lock review.
- Required outputs: 参数锁定结果, 五官模块解析, 身形吸引力解析, 滤镜模块解析, 最终提示词, 负面约束.
- Non-negotiable constraints: preserve locked parameters exactly unless unsafe; keep the subject adult; avoid explicit or pornographic framing.
- Expected bundled files loaded at runtime: only `SKILL.md`.

## Source And Evidence Model

Authoritative sources:
- User-provided source prompt in the creation request.
- Local skill-writer guidance for Agent Skills structure.

Useful improvement sources:
- positive examples: successful six-section outputs with exact parameter preservation.
- negative examples: outputs that weaken user parameters, oversexualize, omit adult constraints, or drift into CG/influencer style.
- validation results: structural skill validation and manual trigger checks.

Data that must not be stored:
- secrets
- private user identifiers
- private image URLs or personal identity data not needed for prompt reproduction

## Reference Architecture

- `SKILL.md` contains all runtime instructions, defaults, module mappings, output contract, templates, and examples.
- `references/` is unused unless future variants require optional deep lookup tables.
- `references/evidence/` is unused unless future iteration examples need to persist.
- `scripts/` is unused.
- `assets/` is unused.

## Validation

- Lightweight validation: run `quick_validate.py` against the skill directory.
- Deeper validation: test should-trigger and should-not-trigger queries manually.
- Holdout examples: all-parameter input, missing-filter input, unsafe intensification input.
- Acceptance gates: structural validation passes; final prompt always includes six sections; locked safe parameters are preserved.

## Known Limitations

- The skill does not call an image model or verify generated images.
- It relies on the host model to apply safety judgment for ambiguous sexualized requests.

## Maintenance Notes

- Update `SKILL.md` when prompt fields, defaults, safety boundaries, or output contract change.
- Update `SOURCES.md` when adding new source material, decisions, validation notes, or examples.
- Update `references/evidence/` only when persistent positive/negative examples are needed for future revisions.
