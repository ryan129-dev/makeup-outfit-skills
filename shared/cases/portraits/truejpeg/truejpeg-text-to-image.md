# 人像参考：文生图的画面语言

本卡基于 True JPEG「人像」作品的可见画面，供文生图设计时选择、适配与组合；不是原站提示词或统一摄影滤镜。具体原图和不确定项见 [No.003—117](truejpeg-selected-003-117.md)、[No.122—148](truejpeg-selected-122-148.md) 和 [No.170—247](truejpeg-selected-149-247.md)。

## 从哪种画面出发

先按当轮用途选择明确的画面方向，再把人物、动作、构图与环境作为一个整体设计。未指定时从以下不同方向选最适合的一种，而非混合全部特征：

|方向|支撑画面的组合|对应参考|
|---|---|---|
|露台夜景侧脸|近中景背向人物、向一侧的低视线、近亮远暗的城市灯点与栏杆|[No.003 / #288](https://truejpeg.com/#288)|
|都市夜拍回望|略高视角、侧身抬眼、一手靠领口、斜穿后方的道路线和亮人物暗街景|[No.141 / #003](https://truejpeg.com/#003)|
|镜中时装自拍|近全身、竖直镜框、举手机及看镜面的视线、深色服装的材质反光、暗室|[No.005 / #183](https://truejpeg.com/#183)|
|室内眨眼抓拍|近距离略俯视、前倾肩线、一眼闭合与闭唇笑、明亮面部和暗色室内|[No.170 / #028](https://truejpeg.com/#028)|
|浅椅冷色透视|椅背包围人物、屈腿前后错位、亮青绿前景与暗室暖光纵深|[No.224 / #086](https://truejpeg.com/#086)|
|低视线窗边近景|头顶裁切、低头低眼睑、深发框脸、亮窗横线与暗室|[No.122 / #193](https://truejpeg.com/#193)，仅迁移面部与光线|

按[整体造型](../../../methods/whole-look-review.md)组织人物、动作和场景关系，按[提示词方法](../../../methods/prompt-design.md)转成文字。

## 文生图规格示例

这些是可调整的起点；选择一个后按目标补充人物和用途，不将示例当成模型必然能复现的配方。

### 露台侧脸与城市灯点

参考 [No.003 / #288](https://truejpeg.com/#288)：背向人物和侧脸、栏杆与远处小灯点共同形成空间。

```text
Create a vertical, close-to-medium fashion photograph of an adult on a balcony at night. She stands with her back toward the camera near a railing, turning her head toward image-left in profile; her eyelids are lowered, gaze directed down-left, lips gently parted. Dark hair is arranged into small braids gathered at the back; a black long dress creates a dark silhouette. One hand holds a stemmed glass. Use bright, fairly direct foreground light to reveal the face profile and shoulder line, while distant city windows remain small warm points in the dark. Keep the railing and a little foliage legible near the subject, with realistic hand-to-glass contact and detail in the dark fabric.
```

检查脸是侧面且视线朝下，栏杆、杯与远景灯点是否形成前后关系；人物与城市的亮度差是否成立。

### 灰牛仔夜街回望

参考 [No.141 / #003](https://truejpeg.com/#003)：稍高视角、回望、手与衣领和斑马线相互支撑。

```text
Create a vertical street-fashion portrait, framed from head to hip, viewed from a slightly elevated angle. An adult turns her body a little to one side and looks up toward the camera, head gently tilted, lips slightly parted. One hand rests near the collar, the other near a trouser pocket. Give her dark hair, defined outward eyeliner and a muted rose lip. Use a charcoal denim jacket and matching jeans with visible seams, plus a narrow brown shoulder-bag strap. A crosswalk runs diagonally behind her, with trees and buildings receding into a dark evening street. Light her face, hands and denim from near the camera, leaving the background darker but recognizable.
```

检查视线与头肩方向、两手位置、斑马线方向，以及前景亮光是否仍让牛仔纹理和环境结构可辨。

### 暗室镜中时装自拍

参考 [No.005 / #183](https://truejpeg.com/#183)：镜框、举机动作、深色轮廓及局部硬反光形成自拍感。

```text
Create one vertical mirror-selfie fashion photograph in a dim room. Show an adult standing nearly full length within the mirror frame, one hand holding a phone and the other at the waist, her face slightly turned toward the reflection. Compose the mirror's vertical edges clearly. Style a black hat, dark jacket, shorts and tall boots, separating fabric and leather with localized highlights. Keep the room and doorway subdued; a small bright reflection near the phone and a diagonal floor shadow give a direct-light feel. Make the phone, reflected hand, stance and mirror perspective physically coherent.
```

检查镜面边框与人物全身是否同框，手机和镜像方向是否一致，深色衣物与背景是否分离。

### 眨眼微笑的近距离抓拍

参考 [No.170 / #028](https://truejpeg.com/#028)：略俯视、前倾、单眼闭合与闭唇笑形成同一神态。

```text
Create a vertical close-range indoor portrait of an adult, viewed slightly from above. She leans subtly toward the camera, head and shoulders gently angled; one eye is closed in a wink, the other looks toward the lens, and her lips form a closed-mouth smile. Sweep center-parted dark hair back from the face. Use refined warm eye makeup, soft pink cheeks and a satin pink lip; pair it with a gray short-sleeved outfit and a small metal detail at the neckline. Bright near-camera light makes the face and shoulders clear, with a restrained warm highlight in the hair; dark cabinetry remains visible behind her without competing with the expression. Hands remain outside the frame.
```

检查单眼闭合与笑容是否同时成立、肩线是否前倾、面部明亮而柜体仍保留暗部线条。

## 结果判读

生成后先对照本次选定方向检查景别、姿态、视线、光色及环境是否同时成立，再检查五官、妆发、材质和接触关系。若只保留颜色或饰品，却把构图、动作和明暗关系改掉，应判断为画面方向偏离，调整最主要的差异后再试；不得仅因文字包含风格名就宣称成功。
