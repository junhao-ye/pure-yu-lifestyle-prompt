---
name: pure-yu-lifestyle-prompt
description: Use when the user asks to generate or refine Chinese AI image prompts for realistic adult East Asian female pure-yu lifestyle portraits, cinematic everyday portrait photos, clean sensual life-photo prompts, or parameter-locked female portrait prompt templates. Produces locked-parameter review, facial analysis, body-curve analysis, filter analysis, final prompt, and negative constraints while avoiding explicit, pornographic, underage, cheap lingerie, or CG/illustration styles.
---

# 女性写实纯欲生活照提示词

Use this skill to turn user parameters into one complete, stable Chinese prompt for an AI image generator. The target output is a realistic, clean, cinematic lifestyle portrait of an adult East Asian woman with restrained pure-yu atmosphere and natural body-curve appeal.

## Safety Boundary

Always keep the subject clearly adult: a 20-28 year old young adult East Asian woman. Refuse or redirect requests involving minors, school uniforms used for sexualization, teen/young-looking framing, nudity, explicit sex, fetish content, pornographic framing, voyeurism, coercion, or instructions to intensify erotic exposure. When redirecting, offer a clean adult lifestyle portrait version.

Do not create lowbrow edge content. Keep the style clean, restrained, realistic, and non-explicit.

## Required Input Handling

1. Extract all user-supplied parameters exactly.
2. Before writing the final prompt, perform a parameter-lock review.
3. Strictly preserve locked parameters. Do not replace, weaken, reframe, or auto-optimize them.
4. Only expand and refine locked parameters in a compatible way.
5. If a parameter is missing, use the default below and label it as defaulted in the lock review.
6. If a parameter conflicts with the safety boundary, keep the safe part and replace the unsafe part with a restrained adult lifestyle-photo equivalent.

## Default Parameters

| Field | Default |
| --- | --- |
| 写真风格 | 写实纯欲生活照 |
| 场景方向 | 极简室内空间 |
| 服装方向 | 贴身吊带 |
| 气质标签 | 清纯、纯欲、温柔、安静、克制、有吸引力 |
| 五官方向 | 初恋感淡颜 |
| 身形方向 | 自然吸引力曲线 |
| 身形吸引力强度 | 中 |
| 线条重点 | 脖颈、锁骨、腰线、小腹、大腿 |
| 镜头方向 | 轻侧身站姿、半身到大腿 |
| 光线氛围 | 柔和冷白自然光 |
| 滤镜效果 | 冷白纯欲生活照滤镜 |
| 画幅比例 | 9:16 |

## Module Rules

### Person Baseline

The person must be a young adult East Asian woman, visually 20-28 years old, with natural and clear East Asian features. Avoid Westernized mixed-race drift, older-looking styling, underage cues, doll-like childish features, exaggerated influencer face, and standard AI-beauty sameness.

### Pure-Yu Definition

Pure-yu means: clean innocent facial impression + attractive adult feminine body shape + restrained sensuality + realistic lifestyle-photo atmosphere.

Use: sheer natural makeup, clean facial features, soft quiet expression, simple close-fitting but restrained clothing, clear but not exaggerated curves, clean cool-white or soft-white light.

Avoid: heavy makeup, vulgar teasing, exaggerated cleavage, explicit nudity, erotic performance, cheap lingerie-ad styling, plastic retouching, and pornographic composition.

### Facial Direction Expansion

| 五官方向 | Required expansion |
| --- | --- |
| 初恋感淡颜 | 自然鹅蛋脸或柔和小圆脸，五官舒展清秀，眼神清澈明亮，轻微羞涩和亲近感，自然小巧鼻型，柔和饱满唇形，清纯耐看，不幼态。 |
| 邻家清秀脸 | 自然柔和脸型，五官清秀耐看不过度惊艳，眼神亲近轻松干净，唇形自然柔软，真实生活中自然好看的年轻成年女性。 |
| 温柔圆脸 | 柔和圆润或小鹅蛋脸，轮廓顺滑，圆润杏眼，眼神柔和干净，小巧自然鼻型，柔软饱满唇形，亲近无攻击性。 |
| 清冷淡颜 | 窄鹅蛋脸或轻微长鹅蛋脸，轮廓干净，细长杏眼或内敛凤眼感，眼神清透安静有距离感，清秀挺直鼻型，自然克制唇形。 |
| 电影故事脸 | 自然长鹅蛋脸或柔和骨相脸，有轻微真实骨相，细长或略下垂眼型，眼神有留白和情绪感，真实有辨识度，不像标准 AI 美人脸。 |

### Body Direction Expansion

| 身形方向 | Required expansion |
| --- | --- |
| 自然吸引力曲线 | 胸、腰、腹、大腿线条均衡自然，重点是整体吸引力，不夸张单一部位。 |
| 腰臀曲线感 | 强调腰线收束、腰臀比例和下半身曲线，适合站姿或半坐姿。 |
| 胸腰腿线条感 | 强调自然胸线、腰线、小腹与大腿线条的整体联动。 |
| 丰腴自然曲线 | 线条更柔软丰润，胸部、腰臀、大腿更饱满，但保持真实克制。 |
| 轻熟曲线感 | 更有轻熟女性气质，胸线、腰线与大腿线条更明确，但不艳俗。 |

Intensity handling:

| 身形吸引力强度 | Effect |
| --- | --- |
| 弱 | 更偏清纯，身体吸引力存在但不强烈。 |
| 中 | 平衡清纯与吸引力，两者同时明显。 |
| 强 | 曲线存在感更强，但仍真实克制，不能色情化或夸张化。 |

Line emphasis must come from clothing fit, pose, composition, and light. Chest may only be described as natural curve, never exaggerated cleavage or enlarged breasts. Neck, collarbone, shoulder, and waistline are key pure-yu areas. Waist, navel, lower abdomen, thigh, and waist-hip ratio must be shown naturally, without vulgar angles.

### Scene, Clothing, Pose, Lens

Prefer clean simple scenes: 靠墙、窗边、卧室一角、床边、极简室内空间、客厅沙发边. The background supports the person and body lines; avoid clutter, luxury studio feel, or overly narrative environments.

Clothing must follow the user’s locked 服装方向. Keep it close-fitting, simple, restrained, real, and able to naturally reveal or imply collarbone, chest line, waistline, navel, lower abdomen, thigh, or waist-hip ratio. Avoid cheapness, complicated patterns, lace piling, fetishization, and lingerie-ad tone.

Pose must be simple and stable: 靠墙站姿、轻侧身站姿、坐姿轻倚、半身到大腿构图、大腿以上构图、轻微前倾坐姿、一侧腿轻微前伸、自然重心偏移. Avoid extreme twisting, wide leg poses, complex prone poses, explicit posing, and vulgar angles.

Use eye-level or slight high angle, 35mm or 50mm realistic photography perspective, medium-close framing from half body to thighs or above thighs. Avoid ultra-wide, extreme low/high angles, over-close perspective, and body-part fetish framing. Require accurate arms, fingers, legs, knees, joints, and proportions.

### Filter Rule

If the user supplies 滤镜效果, obey it exactly. If missing, use 冷白纯欲生活照滤镜.

For 冷白纯欲生活照滤镜, describe low-saturation cool white, soft grey-white, light beige-grey, clean skin tones, minimal restrained transparent quiet atmosphere, no high-saturation warm yellow, no obvious teal-orange, no vintage color cast, soft diffused natural light or cool-white indoor light, gentle shadows, clean curve edges, real skin texture, and slight soft glow.

If the user explicitly chooses 奶油暖白生活剧照滤镜, keep it warm-soft but still clean, realistic, restrained, low saturation, and non-vintage.

### Skin And Makeup

Use clear natural makeup, natural brows and eyes, clean gaze, soft natural lips. Keep real skin texture, subtle pores, slight imperfections, natural skin tone variation, and slight soft glow. Avoid plastic skin, excessive retouching, and heavy makeup.

## Output Contract

Always output exactly these six sections:

1. 参数锁定结果
2. 五官模块解析
3. 身形吸引力解析
4. 滤镜模块解析
5. 最终提示词
6. 负面约束

Keep sections 1-4 concise but specific. The final prompt should be one complete polished paragraph or several compact paragraphs ready to paste into an image generator.

## Final Prompt Template

Use this structure, preserving all locked parameter values:

```text
生成一张 {画幅比例} 的写实纯欲风格女性生活照。

画面主体是一位 20-28 岁年轻成年东方女性，具有自然明确的东方女性特征，不过度欧美化，不显年龄偏大，没有未成年感。人物整体气质为 {气质标签}，同时呈现清纯、安静、克制、柔和与明显女性吸引力。她不是网红脸，不是过度精修写真脸，而是像真实生活中干净、自然、柔软，却具有明确身体吸引力的年轻女性。

人物五官方向为 {五官方向}。请根据该五官方向塑造清晰但自然的长相差异，包括脸型、眼型、鼻型、唇形、骨相和整体辨识度。五官必须清纯干净、自然真实，不网红化，不假面感，不幼态化。

人物身形方向为 {身形方向}，身形吸引力强度为 {身形吸引力强度}。整体比例真实协调，胸部自然饱满但不过分夸张，胸线柔和清晰；腰线明显，肚脐自然可见，小腹平坦但保留真实身体感；大腿线条流畅柔和，腰臀比例自然好看，整体身体轮廓具有明确女性吸引力与柔和 S 型曲线。重点突出 {线条重点}，但必须保持克制、真实、干净，不低俗，不刻意色情化。

整体风格为 {写真风格}，即 realistic sensual lifestyle portrait / naturalistic intimate portrait / cinematic everyday body portrait。画面像一张极简、干净、克制的写实纯欲生活照，真实、柔和、安静，有生活感，也有明显身体吸引力，但不是情色写真，不是廉价情趣风，不是 CG 或 AI 插画。

场景设定在真实的 {场景方向} 中，环境干净、简洁、克制，背景尽量纯净，避免复杂布景和豪华影棚感，让人物身体线条成为视觉重点。

服装为 {服装方向}，整体贴身、简洁、克制、真实，能够自然呈现锁骨、胸线、腰线、肚脐、小腹、大腿或腰臀比等线条区域，但不低俗，不廉价，不夸张。

姿势采用 {镜头方向}。肩颈放松，锁骨自然显露，腰线轻微收束，肚脐和小腹可自然可见，一侧腿可轻微前伸或重心偏移，使整体形成柔和自然的 S 型曲线。动作不要复杂，不要高难度摆拍，不要刻意色情化姿势。

光线氛围为 {光线氛围}。整体光线柔和、低反差、干净通透，阴影轻柔，身体曲线边缘清楚但不过硬，皮肤保留真实细腻纹理与轻微柔光感。

整体套用 {滤镜效果}。画面采用低饱和冷白、柔和灰白、浅米灰和干净肤色体系，整体极简、克制、通透、安静，不要高饱和暖黄，不要明显青橙调色，不要复古偏色。整体突出清纯脸与有吸引力的女性身体曲线，画面纯净、克制、安静，同时带有明显纯欲气质。

镜头为平视或轻微俯视，使用 50mm 或 35mm 真实摄影视角，避免超广角变形。人物五官与身体比例真实协调，手臂、手指、腿部、膝盖和关节结构自然准确。
```

If the locked filter is not 冷白纯欲生活照滤镜, replace the cold-white filter description with an accurate compatible description of the locked filter.

## Negative Constraints Template

```text
避免：肢体变形、手指错误、多余手指、手臂扭曲、腿部畸形、身体比例异常、胸部夸张变形、爆乳感过强、低俗擦边感、廉价情趣风、过度挑逗姿势、网红脸、标准AI美人脸、过度精修感、塑料皮肤、浓妆、未成年感、娃娃脸幼态、CG感、AI插画感、过强电影滤镜、高饱和暖黄、强烈青橙调色、复古偏色、复杂背景、豪华影棚感、刻意色情化构图、超广角变形、低俗裸露感。
```

## Examples

Happy path request: user provides all parameters, such as 靠墙 + 贴身吊带 + 初恋感淡颜 + 中 + 冷白纯欲生活照滤镜. Output all six sections and preserve every supplied value exactly.

Robust variant: user omits filter and ratio. Mark 滤镜效果 and 画幅比例 as defaulted in 参数锁定结果, then use 冷白纯欲生活照滤镜 and 9:16.

Anti-pattern correction: if user asks to make the subject look younger, more exposed, or more sexually provocative, do not intensify. State that the prompt will remain adult, clean, restrained, and non-explicit, then generate the safe adult lifestyle-photo version.
