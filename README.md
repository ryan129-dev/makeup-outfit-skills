# 妆容、穿搭与视觉设计 Skills

三个专业入口按任务调用，交付图片、提示词、分析或建议。共用方法、学习流程和具体案例集中放在 `shared/`。

## 目录地图

```text
makeup-research/                  妆容、写真造型与人像修图
├── SKILL.md                     适用范围、判断要求与资源入口
└── references/                  妆容专用方法：人物适配、人像修图
outfit-research/                  穿搭、配饰与视觉换装
├── SKILL.md                     适用范围、专业取舍与资源入口
└── references/                  穿搭专用方法：搭配、替换与结构
visual-style-research/            摄影、插画等作品的视觉设计
└── SKILL.md                     画风、构图、配色、光影与材质判断
shared/                          三个 Skill 共用的知识与资源
├── methods/                     可迁移方法：任务判断、视觉关系、提示词、评价及造型光色
├── workflows/                   参考学习、探索与知识更新
├── cases/                       具体作品的观察、配方、来源与验证状态
│   ├── index.md                 案例总索引
│   ├── makeup/                  妆容及完整造型案例
│   │   └── porcelain-rose-flash/ 冷白透粉的观察、配方与迁移示例
│   ├── portraits/               人像摄影案例
│   │   └── truejpeg/            True JPEG 来源的观察与文字方案
│   └── illustration/            插画与跨画风探索案例
└── assets/                      案例对应的图片文件
    └── rose-pink-velvet-closeup/ 玫粉近景的版本与身份对照图
work/                            本地临时工作，不入库
outputs/                         本地生成结果，按需创建，不入库
```

## 从哪里进入

|任务|入口|
|---|---|
|妆容、以妆容为核心的写真、人像修图|[makeup-research](makeup-research/SKILL.md)|
|服装搭配、配饰、视觉换装|[outfit-research](outfit-research/SKILL.md)|
|视觉风格、构图、色彩、光影与材质|[visual-style-research](visual-style-research/SKILL.md)|
|查阅具体作品及验证状态|[案例索引](shared/cases/index.md)|
|研究参考图、吸收反馈、更新知识|[参考学习](shared/workflows/reference-learning.md)|

## 方法入口

|需要解决的问题|方法|
|---|---|
|确定交付、改动范围与参考角色|[任务判断](shared/methods/task-framing.md)|
|解释或设计构图、配色、材质与主次|[视觉关系与取舍](shared/methods/visual-reasoning.md)|
|将目标转成可执行描述|[视觉规格与提示词](shared/methods/prompt-design.md)|
|评价、比较与定位失败原因|[结果判断](shared/methods/result-review.md)|

## 文件归属

- `SKILL.md`：触发范围、判断依据、执行要求及必要入口。
- 各 Skill 的 `references/`：只服务该专业的方法；有内容时再建立目录。
- `shared/methods/`：跨专业适用的关系、条件、调整方法与判断标准。
- `shared/workflows/`：研究、验证和写回知识的操作要求。
- `shared/cases/`：具体案例及其来源、适用范围和证据状态；案例内的参数不自动成为全局默认。
- `shared/assets/`：已纳入案例的图像。临时图与探索产物放 `work/` 或 `outputs/`。

## 使用与安装

直接使用本仓库时，让助手读取对应的 `SKILL.md`。安装到技能目录时，将 `makeup-research/`、`outfit-research/`、`visual-style-research/` 和 `shared/` 一起复制，保持四者相邻；三个专业入口仍使用原名称。`shared/` 不设 `SKILL.md`，仅由专业入口按需读取。

冷白透粉已归为共享案例，通过妆容 Skill 调用，不再作为嵌套 Skill 独立安装。安装目录中若已有旧版 `portrait-aesthetic-skill`，迁移时应移除旧入口，避免重复触发。
