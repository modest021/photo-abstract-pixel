---
name: photo-abstract-pixel
description: "Redraw an uploaded image as restrained abstract pixel art by reconstructing its subject, composition, and color relationships with deliberate pixel clusters and a limited palette. Use for 抽象像素风, abstract pixel art, low-resolution pixel reinterpretations, or geometric pixel redraws; do not use for simple mosaic/downsampling, cute chibi pixel art, or photo-and-panel editorial layouts."
---

# Photo Abstract Pixel

将一张上传图片语义级重绘为一幅完整的抽象像素艺术作品。原图是唯一内容来源；保留其主体、构图关系和情绪，但主动舍弃写实细节。结果必须像经过像素艺术设计的重新绘制，而不是对原图降采样或添加马赛克滤镜。

## Workflow

1. 内部观察原图，不输出分析。识别主体、轮廓、视线或运动方向、前中后景、负空间，以及三至六个决定性的空间与色彩关系。
2. 选择适合画面复杂度的低分辨率逻辑网格。简单主体使用更粗的像素簇，复杂场景使用稍细的网格；最终放大时保持像素边缘清晰。
3. 选择一种主要抽象语法，如大型色块、阶梯轮廓或网格节奏，最多加入两种辅助语法。先安排主体与背景的面积、位置、比例和方向，再用少量小像素簇保留必要的身份线索。
4. 从原图提炼六至十四种颜色，合并接近色与明度层级。只在原图存在时使用高饱和强调色；阴影避免默认使用纯黑。
5. 使用原图作为图像生成或编辑工具的视觉参考，生成一张完整成品。默认沿用原图宽高比；除非用户明确要求，不添加文字、边框、海报面板、游戏界面或装饰图标。
6. 只返回完成的图像，不输出观察过程、色板清单、提示词或多个候选版本。

## Visual Rules

- 使用明确的方形像素、硬边缘和成组像素簇；禁止抗锯齿、柔焦、平滑渐变、照片纹理和写实渲染残留。
- 抽象化来自形体归纳与关系重构：优先保留大轮廓、节奏、层次、方向和负空间，而不是逐像素描摹原图。默认采用中等抽象度，使主体与场景关系仍可辨认。
- 保留最低必要辨识度。人物保留姿态、发型或标志性配饰；动物保留体态、耳形或斑纹节奏；建筑保留轮廓和一至三个身份特征；风景保留地平线、主要层次与光色关系。
- 像素簇应有设计感并彼此连贯，避免随机散点、无意义抖动、glitch 故障效果、均匀马赛克方格或机械描边。
- 默认风格克制、平面、现代且偏艺术化；不要自动加入 Q 版比例、豆豆眼、腮红、复古游戏 HUD、霓虹赛博元素或像素字体。
- 不发明原图中没有的主体、道具、文字、颜色或背景内容。允许为构图做轻微裁切，但不得改变核心事件与主体关系。

如果用户明确要的是字面意义的马赛克、下采样或可爱 Q 版像素画，则按该明确意图处理，不套用本 Skill 的抽象重绘规则。
