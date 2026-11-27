# 幻熊 · 婚礼与旅拍配色师

从 **30 位电影导演与摄影指导**的作品里，挑一套现场拍得出来的婚礼或旅拍配色。每位大师有一张卡，写明三个颜色分别放在哪里、主光从哪边来，以及如何保住两位新人的肤色、婚纱纹理和深色礼服的层次。

[下载 v2.0.0 安装包](https://github.com/HaloBear-AI/skill-wedding-travel-colorist/releases/download/v2.0.0/wedding-travel-colorist-v2.0.0.zip) · [打开 30 位大师选卡表](wedding-travel-colorist/references/film-cards.md) · [下载 Excel 配色速查表](https://github.com/HaloBear-AI/skill-wedding-travel-colorist/releases/download/v2.0.0/wedding-palettes.xlsx)

## 怎么选

| 面前的场景 | 可以从哪张卡开始 |
| --- | --- |
| 家中备婚，母亲在窗边替女儿整理头纱 | [是枝裕和《海街日记》](wedding-travel-colorist/references/daylight.md#look-01)。让窗光托住两个人的脸，保留木柜与白纱间的色差。 |
| 红丝绒宴会厅，暖壁灯和绿色玻璃同框 | [王家卫《花样年华》](wedding-travel-colorist/references/celebration.md#look-11)。红绿分给两处实物，控制从帘子反到脸上的红光。 |
| 阴天海岸，风吹动浅色裙摆 | [克莱尔·马松《燃烧女子的肖像》](wedding-travel-colorist/references/destination.md#look-24)。用海天与衣料的明度差勾出人物，保留裙面受风的褶纹。 |

全套卡按[亲密婚礼与柔光人像](wedding-travel-colorist/references/daylight.md)、[庆典与婚礼设计色](wedding-travel-colorist/references/celebration.md)、[目的地与时刻](wedding-travel-colorist/references/destination.md)分组，每组 10 人。表格中的色样可用来商量花材、服装、布景和画面效果，拍摄与调色时以实际人物和材质为准。

## 安装与调用

下载上方安装包并解压。把内层 `wedding-travel-colorist` 文件夹放进项目的 `.agents/skills/`，确保入口是 `.agents/skills/wedding-travel-colorist/SKILL.md`。在该项目开启新的 Codex 会话，输入下面的简报即可。也可克隆本仓库，从仓库根目录取同名文件夹。

> 用 $wedding-travel-colorist 给一场庭院婚礼选配色。上午在红木厅敬茶，新人穿红色秀禾服和深蓝西装。傍晚换象牙白纱到花园跳第一支舞。选一位电影大师作为主参考，给两段各自的三色和用光，并告诉摄影师怎么看出红绣线和白纱都拍出了纹理。

想要旅拍分镜时，加上行程、时刻和天气。需要出图或生成视频时，指定画幅、时长和提示词语言。文字方案由宿主助手完成，Skill 无需配置密钥或安装脚本。速查表可离线使用。实际生成影像时，将提示词交给所选的影像工具。

## 交付示例

- [婚礼《从敬茶到第一支舞》](wedding-travel-colorist/examples/tea-to-first-dance.md)有两段色板、现场动作、肤色验收，以及静帧和视频提示词。
- [贵州侗寨旅拍《一把布伞》](wedding-travel-colorist/examples/guizhou-dong-village.md)沿三段光线跟拍同一对新人，附雨天替代方案和逐段提示词。
- [现场配色与纠偏](wedding-travel-colorist/references/scene-recipes.md)可按宴会厅混光、草地反绿、沙滩白纱或霓虹染肤查到处理方法。

## 编写与来源

五维配色方法参考磨坊主 Miller 的《N°09 大师配色包》。幻熊为婚礼与旅拍重新选片，编写了 30 张实拍配色卡、现场处方与示例。片名和职务的出处列在每张卡尾，色号为本项目设计的 sRGB 提案色样。
