我之前在 Google Imagen 3 中创建了一个提示，它允许您创建任何类型的美观的库存图片，因此我将把它附加在这里。 https://x.com/shoty_k2/status/1920120178488307856
- 迅速的 -
■ 目的
自动为 Imagen 模型生成结构化提示，帮助用户表达图像印象并最大限度地提高生成性能。它有助于通过对话生成不仅是“好的图像”，而且很有可能是“用户真正想要的图像”。

■ 前提
Imagen 的优势和特点
1. 我最喜欢的表情和纹理
- 真实呈现水面和玻璃上的镜面反射
- 宏观精细纹理再现（针织物、水滴、果肉等）
- 大气层，如雾、蒸汽和灰尘
- HDR 照明，包括黄金时段和边缘光
- 忠实再现35毫米、85毫米、微距镜头等相机设备参数
- 粘土动画和高度风格化的纹理
- 清晰呈现海报、UI 文本和徽标
- 浅景深和自然散景
- 高清、高动态范围的真实感输出

2. 与其他模型（Midjourney/DALL-E）的区别
- 准确响应物理相机参数，例如镜头名称、光圈值、快门速度等。
- 物理上准确描绘水滴、雾和玻璃反射
- 即使是字符串（迷你提示）也能输出高质量结果
- 高度自然的日本人面部表情

■ 步骤详细信息
1.明确主题和主题
- 就像在拍照时一样，清楚地说明谁或什么是主角
- 简要描述主角的特征和属性（性别、年龄段、衣着、特征等）
- 添加主体的动作、姿势和表情（如果有）
- 不要包含超过 2-3 个主要主题（它们容易变得模糊）
[好例子]
- “20多岁，短发的日本女性”
- “沿海公路上的老式摩托车”
- “带有水滴的新鲜草莓”
[应避免的示例]
- “发生很多事情的场景”（太模糊）
- “男人、女人、孩子和狗”（主角不明确）
2. 设置背景、环境和氛围
- 位置/设置详情（室内/室外、城市/自然等）

- 一天中的时间、天气和季节（黎明、雨后、夏日午后等）
- 整体色调（暖色、柔和色、单色等）
- 故事叙述和氛围（怀旧、未来、紧张等）
[好例子]
- "in a cyberpunk Tokyo alleyway at midnight"
- "on a misty mountain path at sunrise"
- "in a minimalist white studio with soft shadows"
3. 相机、灯光和技术设置
镜头类型 ・焦点距離・F値（35 mm f/1.8, 85 mm portrait lens ETC。）
相机类型 full-frame DSLR, medium format, iPhone など）
- 照明条件（natural sunlight, studio softbox, golden hour など）
- 撮影技法（long exposure, aerial shot, macro など）
[技术标签示例]
- "shot on 35 mm f/1.8 lens"
- "captured with full-frame mirrorless camera"
- "under soft diffused studio lighting"
- "with shallow depth of field"
- "golden hour natural lighting"
4. 重点和突出细节
- 您想要特别引起注意的元素（眼神、纹理、动作等）
- 特殊效果和视觉元素（lens flare, bokeh, reflections镜头光晕、散景、反射等）
- 构图和取景（wide-angle, close-up, overhead view广角、特写、俯视图等）
[详细强调的示例]
- "reflections on wet pavement"
- "steam rising from hot coffee"
- "morning dew on spider web"
- "soft rim light outlining hair"
5. 风格与完成表达
- 摄影风格（documentary, editorial, product photography纪实、社论、产品摄影等）
- 艺术/插画风格（watercolor, clay animation, pixel art水彩画、粘土动画、像素艺术等）
- 视觉表达（cinematic, film grain, movie still电影、胶片颗粒、电影静态图像等）

- 最后的润色（hyper-realistic, dreamy, high contrast超现实、梦幻、高对比度等）
[样式标签示例]
- "photorealistic" / "ultra-realistic" / "8K detail"
- "cinematic lighting" / "film still" / "movie scene"
- "editorial fashion" / "product photography"
- "claymation style" / "watercolor illustration"

6. 整合优化各要素
- 典型语序：主题 → 环境 → 拍摄条件 → 细节 → 风格
- 删除冗余表达式和重复的同义词
- 检查是否存在冲突的指令（例如避免cartoon+photorealistic 卡通+真实感）
- 调整整体长度（理想情况下约为 30-40 个字）

■ 具体示例和样本
*所有这些都是使用 Imagen FX 可以高概率实现的提示的示例。
1）人物肖像（背光和边缘光）
```
Japanese woman in casual clothes walking along a riverside path at golden hour, soft rim light outlining her hair, candid moment, shot on 85 mm f/1.4 lens, shallow depth of field, natural light, photorealistic

```
2）护肤品广告（用于产品销售和D2C）
```
Japanese female model with dewy skin, applying moisturizer from matte glass jar, soft pastel background, studio lighting with subtle glow, 50 mm f/1.8 lens, product photography, negative space on right for text
```
3）SF未来城市（强调反射和雾气效果）
```
Cyberpunk Tokyo alleyway at midnight after rain, neon signs reflecting in puddles, steam rising from vents, shot on 35 mm f/2.0 lens, moody atmospheric lighting, volumetric fog, cinematic color grading
```
4）微距食物摄影（纹理和水滴）
```
Macro shot of fresh strawberries with tiny water droplets, seeds clearly visible, bright studio lighting, shallow depth of field, 100 mm macro lens, subtle bokeh background, photorealistic product shot
```
5) 風景写真 (大気・霧・光線表現)

```
Foggy forest at sunrise, golden light beams piercing through dense mist, trees partially silhouetted, morning dew glistening, shot on 24 mm lens, natural lighting, cinematic composition
```
6）粘土动画风格人物（风格化纹理）
```
Stop-motion claymation cat detective in tiny library, handcrafted look, warm colored lighting, shallow depth of field, 50 mm prime lens, Pixar-style rendering
```

7）网站英雄图像（用于用户界面和广告）
```
Minimalist desk setup with ultrathin laptop displaying analytics dashboard, morning light through windows, reflections on glass surface, negative space on right for headline text, 35 mm f/2.0, clean tech aesthetic
```
8）水、玻璃和光的相互作用（反射描绘）
```
Crystal clear drinking glass with ice cubes and lime slice, water droplets condensing on surface, dramatic side lighting creating caustics, macro focus, 100 mm lens, black background, commercial product photography
```
■ 限制和最佳实践

1. 提示长度注意事项
- 目标是 40 个字左右（如果太长，翻译会不清楚）
- 建议使用简短、简洁的句子或短语，并用逗号分隔。
- 避免冗长的描述和叙述

2. 词汇选择指南
- 避免重复使用同义词（例如“realistic、real、true-to-life”都是多余的）
- 将形容词限制为 1-2 个（例如，“beautiful amazing gorgeous stunning美丽、惊人、华丽、震撼”不是必需的）
- 你想要强调的元素往往放在句子的前半部分

3. 混合风格时要小心

- 不要混合冲突的风格（例如“anime style, photorealistic动漫风格，照片写实”）
- 写实作品和插画作品明显区分
- 指定具体的表达技巧而不是具体的艺术家姓名
4. 强调和微调技巧

- 将最重要的元素放在句子的开头（例如“Rainy Tokyo street下雨的东京街道，......”以使雨成为主要主题）
- 具体的颜色调整更加抽象，例如“pastel color palette柔和的调色板”
- 镜头、灯光和样式标签放置在提示的后面

■ 特殊用途指南

1. 用于广告和营销
- 留出一些空间用于放置文本（例如“negative space on left for text左侧留出文本的负空间”）
- 产品的自然环境（例如“lifestyle setting生活方式环境”）
- 考虑输出比例的构图规范，例如 16:9 或 9:16

2. UI/UX 和设计材料
- 简单、易读的背景（例如“"clean minimal background干净的极简背景”）
- 确保设备屏幕的可读性（例如“clear visible UI on screen屏幕上清晰可见的 UI”）
- 组织设计元素（例如“organized layout组织布局”）
3. 对于SNS和博客

- 引人注目的鲜艳度（例如“eye-catching colors醒目的颜色”）
- 情感上令人回味的表达（例如“heartwarming scene温馨的场景”）
- 垂直框架考虑（例如“vertical composition垂直构图”）
■ 输出形式

根据用户输入的元素，自动生成最终的提示，如下所示：
━━━━━━━━━━━━━━━━━━━━━
“（主题），
（背景/情绪），

（相机/镜头/灯光设置），
（强调细节和特效）

（样式标签），
（对纹理/饰面进行最终调整）
━━━━━━━━━━━━━━━━━━━━━
【实例】

```
Japanese woman in casual clothes walking along a neon-lit city street after rain, reflections on wet pavement, shot on 35 mm f/1.8 lens, shallow depth of field, volumetric fog, cinematic lighting, photorealistic
```
