# 妆容与穿搭研究 Skills

用于研究参考图、提炼可迁移配方、固定人物生成或编辑，并检查实际结果。

根据妆效意图识别：在人物妆容、写真或修图语境下，提到冷白皮、冷白透粉、白里透红、布灵布灵、bling bling、珠光眼妆或眼周细闪等效果时使用妆容 Skill。Skill 主动分析上传图片：身份参考用于为本人设计，风格参考用于提炼并融入指定视觉特点；同一张图可兼具两种用途。默认主导妆容、发型、神态动作、服装配饰、场景、构图、光线与后期，无身份图时设计新成年人物，不设固定默认妆容。泛泛的人像生成请求不触发本 Skill；珠宝、服装等对象的闪光描述也不触发妆容流程。

## 目录

```text
makeup-research/
  SKILL.md
  portrait-aesthetic-skill/
    SKILL.md
    references/
outfit-research/
  SKILL.md
visual-style-research/
  SKILL.md
```

- [妆容研究](makeup-research/SKILL.md)：以妆容为核心的完整人像设计，保留本人辨识度；仅明确限定时局部换妆。
- [冷白透粉闪光妆案例](makeup-research/portrait-aesthetic-skill/SKILL.md)：完整摄影方法与妆面配方。
- [穿搭研究](outfit-research/SKILL.md)：版型、配色、材质、配饰与换装检查。
- [视觉风格研究](visual-style-research/SKILL.md)：研究和应用人物、场景、静物、插画、海报等视觉方向。
- [视觉风格库](makeup-research/references/styles/illustrated-portrait-styles.md)：共享的视觉风格与画面设计参考。

## 使用

默认生成独立单张；多张分别交付，用户要求时制作宫格。

让助手读取所需目录的 `SKILL.md`，按需提供参考图和本轮目标。安装时将三个顶层目录一起复制到所用客户端的技能目录并保持相邻，以便穿搭与视觉风格 Skill 读取妆容目录中的共享风格卡。妆容目录内的案例通过相对路径按需读取；若要独立调用冷白透粉案例，也可将其单独复制到技能目录。


## 持续学习参考图

收录精美的风格、妆容、穿搭及配饰：观察参考图，提炼色彩、尺度、留白、材质和反光的关系，再保存独立风格卡。用户弃用的案例不作为正向配方。使用时结合人物、用户要求和画面选择并调整合适的风格；没有参考图或没有指定风格时，自动设计精美协调的完整造型，不固定套用同一套配方。用户明确限定局部或指定风格时，遵循当轮要求。

人物画风与妆容穿搭分开选择：真人摄影、插画和 3D 等表现方式可使用各自适配的造型；用户指定画风时按要求应用。真人写真不会仅因为风格库包含插画而自动变成插画。

- [探索与吸收：参考图学习、提炼和写回](makeup-research/references/evolution-brain.md)

例如：“研究这张妆容并沉淀成新配方”“提炼这对耳环与领口的关系”“根据这次反馈更新刚才的风格”。只要求分析时不自动生成图片或修改仓库；要求沉淀时按对应流程更新文件。

- [低饱和玫瑰棕四版完整造型](makeup-research/references/styles/muted-rose-brown-defined-eyes.md)：A 银饰露肩、B 蕾丝深眼窝、C 低位眼镜与波点颈巾、D 金饰挂脖。

- [玫瑰粉爱心与冰蓝银星完整造型](makeup-research/references/styles/pink-hearts-icy-blue-stars.md)：记录妆面、发型、配饰、服装、光线与迁移边界。
