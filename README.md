# 幻熊 · 婚礼旅拍配色师

为婚礼摄影、场布提案和目的地旅拍设计一套从现场到成片都能核对的颜色。给它场景、服装和想表达的情绪，就能得到主辅配色、分段色彩剧本，以及每段独立可用的图像和视频提示词。

## 从一个现场开始

> 用 $wedding-travel-colorist 为贵州肇兴侗寨的一对新人做三段旅拍。新娘穿象牙白裙，新郎穿靛青棉外套，带一把深茶色布伞。两人从清晨石阶走过午后木廊，到暮色灯下渐渐并肩。请给出配色方案、分段剧本、每段的图像和视频提示词，并准备雨天替代光线。

查看[贵州侗寨完整示例](wedding-travel-colorist/examples/guizhou-dong-village.md)，可直接比较同一段用于静帧和运动镜头的两种写法。

## 输出

| 交付项 | 内容 |
| --- | --- |
| 配色方案 | 主色、辅色、点缀色与实际载体，饱和度、反差、黑位与高光。分清花材、服装等实物色和灯光造成的呈现色。 |
| 分段色彩剧本 | 每段的人物动作、情绪、主光、光色变化及与下一段的衔接。 |
| 图像与视频提示词 | 静帧给出时刻、构图与细节，视频给出起幅、人物动作、运镜和落幅。可指定中文、英文或双语。 |
| 修订意见 | 针对婚纱高光、彩灯串色、暗部粘连或前后镜头漂色，给出可用一张样片核对的修改。 |

## 安装与配置

下载仓库 ZIP 并解压，或运行下面的命令克隆仓库。将其中的 `wedding-travel-colorist` 文件夹放入使用项目的 `.agents/skills/`，目录应为 `.agents/skills/wedding-travel-colorist/SKILL.md`。在该项目开启新的 Codex 会话即可调用。

```sh
git clone https://github.com/HaloBear-AI/skill-wedding-travel-colorist.git
```

文字方案可由支持 Skill 的助手直接完成，无需安装依赖或配置 API 密钥。制作实际影像时，可将提示词交给你选用的图像或视频生成工具；摄影和后期团队也可以拿色彩剧本与现场样片逐项对照。

## 参考来源与幻熊编写内容

电影参考的选片与五维配色方法源于磨坊主 Miller《N°09 大师配色包》。幻熊保留了 15 位创作者与代表影片的对应关系，重新编写电影光色解读、婚礼及旅拍适配和镜头建议。现场选色、跨镜头连续性、天气替代方案和贵州侗寨案例由幻熊为本 Skill 编写。

- [15 张电影参考卡](wedding-travel-colorist/references/film-cards.md)
- [婚礼与旅拍现场配色](wedding-travel-colorist/references/scene-recipes.md)
- [Skill 入口](wedding-travel-colorist/SKILL.md)
