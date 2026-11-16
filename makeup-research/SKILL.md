---
name: makeup-research
description: 处理人物妆容、以妆容为核心的写真造型及人像修图问题，包括设计、提示词、分析评价、适配、答疑与图像制作。普通人物识别、非妆容物体闪光不触发；单纯画风转换使用 visual-style-research。
---

# 妆容与人像

按[任务判断](../shared/methods/task-framing.md)确定交付、改动范围和参考角色。围绕本人特点、妆效与用途作判断，不要求先选现成配方。

## 专业取舍

- 妆容设计同时考虑美感、五官修饰与本人辨识度；浓度、肤色和装饰服从具体目标。
- 妆画得好，并且修饰本人的缺陷，是四条同时成立。还是这个人：眼距、虹膜、鼻唇和脸不动，已有年龄不改年轻。眉、眼、唇里只有一个重点；这个重点可以更饱和，也可以更深，或边缘更清楚，哑光深色也算重点。眼神光不算第二个妆重点。妆把缺陷收住：眼型无力、眉形散、唇色发闷、肤色不匀，要在妆后被修饰；骨相还在，不把缺陷原样留下充当真实。妆和光是一套：窗光和侧光的亮点跟着窗户，没有受光的那只眼不补白点。妆面盖住皮肤，不因此扣分。半身或特写时，缩小后认得出重点的色相。位置见[人物与妆容适配](references/adaptive-makeup-design.md)。
- 没指定风格时，浓度仍是低到中饱和，边缘干净。细闪、强湿唇、宽猫眼、深眼窝不绑在一起，但重点在成片上认得出。用户要写真、华丽，或主视点就在妆上时，只加强这一个重点。淡妆、忠实复现和自然精修按明确要求执行。
- 四样同时出现时，妆要画得好，并且修饰本人的缺陷：是主视点就只加强那一个重点，不是就保持缩小后认得出。全身穿搭不因看不清眼睑色阶把妆容打成不及格。顺序见[任务判断](../shared/methods/task-framing.md)。
- “给她化这个妆”等造型创作默认设计整张图；明确局部修改、分析或提示词请求按其范围处理。发型、神态、服饰和光线不自动成为身份约束。
- 无人物要求时，默认人物见[人像](../shared/methods/portrait-figure.md)。指定人物及年龄优先，不擅自年轻化，也不换脸。
- 眼妆按[人物与妆容适配](references/adaptive-makeup-design.md)写开。完整成片同时使用人像、穿搭和光影，见[任务判断](../shared/methods/task-framing.md)。

## 按问题读取

|问题|方法|
|---|---|
|选妆、眼形修饰、配色与质地、强度适配|[人物与妆容适配](references/adaptive-makeup-design.md)|
|原照精修、去痘、换发色等局部调整|[人像修图](references/portrait-retouch.md)|
|整体造型、神态动作、饰品与画面配合|[整体造型](../shared/methods/whole-look-review.md)|
|曝光、偏色、亮部、皮肤与妆色保护|[后期调色](../shared/methods/post-production.md)|
|写提示词或执行生成与编辑|[视觉规格与提示词](../shared/methods/prompt-design.md)|
|评价成片或定位反馈问题|[结果判断](../shared/methods/result-review.md)|
|妆容、穿搭或光影好不好看|[好看的量化](../shared/methods/look-quality.md)|
|身材、三视图、中间人左右穿搭|[人像](../shared/methods/portrait-figure.md)|
|学习、探索或更新知识|[参考学习](../shared/workflows/reference-learning.md)|

具体风格按需查阅[案例索引](../shared/cases/index.md)；案例决定选定方向的细节，不扩大任务范围。
