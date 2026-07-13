# Pure-Yu Lifestyle Prompt

`pure-yu-lifestyle-prompt` is an Agent Skill that turns user-provided parameters into stable AI image prompts for realistic adult East Asian female pure-yu lifestyle portraits.

The goal is not vulgar edge content, explicit glamour photography, cheap lingerie-ad styling, heavily retouched influencer imagery, or CG/illustration aesthetics. The skill focuses on clean, restrained, realistic lifestyle-photo prompts with a quiet cinematic everyday atmosphere.

## Features

- Strictly preserves user-supplied parameters
- Fills missing parameters with safe defaults
- Expands facial direction, body-shape direction, line emphasis, and filter effect
- Produces a complete final image-generation prompt
- Adds negative constraints for anatomy errors, AI-like artifacts, over-retouching, and vulgar framing
- Maintains an explicit adult, non-pornographic, non-minor-coded safety boundary

## Use Cases

- Generate realistic pure-yu lifestyle photo prompts
- Generate cinematic everyday portrait prompts
- Convert structured parameters into complete AI image prompts
- Build reusable portrait prompt templates

## Safety Boundary

This skill is only for realistic lifestyle portrait prompts featuring adult East Asian women aged 20-28. It does not support minors, minor-coded sexualization, nudity, explicit sexual content, fetish framing, voyeuristic framing, coercive scenarios, or deliberately provocative composition.

## Input Example

Suggested format:

```text
Photo style: cinematic everyday still
Scene: by the window
Clothing: fitted knit top
Vibe tags: pure, gentle, quiet, restrained, attractive
Facial direction: cool soft-featured face
Body direction: waist-hip curve
Attractiveness intensity: medium
Line emphasis: neck, collarbone, waistline, lower abdomen, thighs, waist-hip ratio
Camera direction: slight side-standing pose, half body to thighs
Lighting: soft cool-white natural light
Filter: cool-white pure-yu lifestyle photo filter
Aspect ratio: 9:16
```

## Output Format

The skill always outputs six sections:

1. Locked parameter review
2. Facial module analysis
3. Body-attractiveness analysis
4. Filter module analysis
5. Final prompt
6. Negative constraints

## Files

- `SKILL.md`: skill runtime instructions
- `SPEC.md`: maintenance specification
- `SOURCES.md`: source, decision, and validation notes
- `LICENSE`: MIT License

## License

MIT License

