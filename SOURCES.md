# Sources And Decisions

## Source Inventory

| Source | Trust | Confidence | Contribution | Usage constraints |
| --- | --- | --- | --- | --- |
| User-provided Chinese prompt system in creation request | Primary | High | Domain behavior, fields, module logic, output contract, negative constraints | Adapted into compact runtime guidance; unsafe sexual intensification is bounded by adult, non-explicit safety rules. |
| `skill-writer/SKILL.md` and references | Primary local | High | Skill creation workflow, inline layout choice, SPEC requirement, validation expectations | Used for structure and validation only. |
| Existing local `ai-avatar-prompt` skill | Local convention | Medium | Confirmed local skills can use compact prompt-template style | Not copied; used only as layout prior art. |

## Synthesis Decisions

| Decision | Status | Rationale |
| --- | --- | --- |
| Skill class: generic prompt-generation skill | adopted | The source is a reusable prompt workflow, not an API/integration or orchestration system. |
| Primary execution shape: inline-guidance | adopted | Every invocation needs the same parameter locking, safety boundary, module parsing, and six-section output contract. |
| References/scripts/assets | rejected for now | No branch-specific deep lookup or deterministic automation is needed. |
| Provider-specific mechanics | rejected | The skill should remain portable across hosts that support Agent Skills. |
| Safety boundary | adopted | Keeps adult realistic portrait prompts clean and non-explicit while preserving the user's intended restrained style. |

## Coverage Matrix

| Dimension | Status | Notes |
| --- | --- | --- |
| Core behavior | covered | Parameter extraction, locking, defaults, module expansion, final template. |
| Edge behavior | covered | Missing parameters defaulted; unsafe parameters redirected safely. |
| Negative behavior | covered | Explicit, minor-coded, pornographic, vulgar, CG, influencer-retouch, and anatomy failures excluded. |
| Repair patterns | covered | Anti-pattern correction example included in `SKILL.md`. |
| Version variance | not applicable | No external API or versioned provider dependency. |
| Shape mechanics | covered | Inline skill only. |

## Source Adaptation Notes

- Source intent: generate stable Chinese prompts for realistic pure-yu adult female lifestyle portraits with strong parameter fidelity.
- Local target behavior: activate as a skill, enforce safety, and return the exact six-section output format.
- Fidelity boundary: preserve parameter-locking, adult East Asian woman baseline, facial/body/filter modules, final prompt structure, and negative constraints.
- Local replacements: converted long narrative prompt into compact runtime rules, tables, defaults, and examples.
- Omitted material: repeated explanatory prose was compressed; no unique runtime requirement was intentionally removed.
- Rights and attribution: source was supplied directly by the user for this skill creation task.

## Description Optimization

Should trigger:
- “生成女性写实纯欲生活照提示词”
- “按这些参数锁定输出纯欲人像 prompt”
- “帮我写年轻成年东方女性电影生活照提示词”
- “冷白纯欲生活照滤镜，靠墙，贴身吊带，五官初恋感淡颜”

Should not trigger:
- “给我拍照构图建议”
- “生成二次元女角色提示词”
- “写成人色情写真 prompt”
- “帮我修图换背景”
- “男生商务头像提示词”

Edits made:
- Description includes Chinese and English trigger concepts through domain nouns.
- Description names required six-section output to improve recall for parameterized prompt-generation requests.
- Description includes explicit exclusions to reduce false positives for pornographic, underage, CG, and general portrait tasks.

## Validation Log

2026-05-30: `quick_validate.py` returned `{ "valid": true, "errors": [], "warnings": [] }`.

