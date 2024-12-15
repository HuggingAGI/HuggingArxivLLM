# 基于上下文的视觉语言地点识别

发布时间：2024年10月25日

`其他` `机器人` `视觉定位`

> Context-Based Visual-Language Place Recognition

# 摘要

> 在基于视觉的机器人定位和 SLAM 中，视觉位置识别（VPR）不可或缺。本文探讨了 VPR 这一问题，即要精准识别给定查询图像所对应的位置。基于视觉的位置识别常用方法依赖于低级视觉特征。尽管近年有显著进步，但场景外观改变时，基于低级视觉特征的位置识别颇具挑战。为应对此，已提出端到端的训练方式来突破手工特征的局限。然而，这些方式在剧烈变化时仍会失效，且需要大量有标记数据来训练模型，这是很大的限制。利用诸如对象或类别等高阶语义信息的方法已被提出以应对外观变化。本文中，我们推出一种新颖的 VPR 方法，它对场景变化具有很强的适应性，且无需额外训练。我们的方法借助零样本、语言驱动的语义分割模型提取像素级嵌入来构建语义图像描述符。我们在具有挑战性的位置识别场景中，使用真实世界的公共数据集对我们的方法进行了验证。实验表明，我们的方法优于非学习的图像表示技术和现成的卷积神经网络（CNN）描述符。我们的代码可在 https: //github.com/woo-soojin/context-based-vlpr 获取。

> In vision-based robot localization and SLAM, Visual Place Recognition (VPR) is essential. This paper addresses the problem of VPR, which involves accurately recognizing the location corresponding to a given query image. A popular approach to vision-based place recognition relies on low-level visual features. Despite significant progress in recent years, place recognition based on low-level visual features is challenging when there are changes in scene appearance. To address this, end-to-end training approaches have been proposed to overcome the limitations of hand-crafted features. However, these approaches still fail under drastic changes and require large amounts of labeled data to train models, presenting a significant limitation. Methods that leverage high-level semantic information, such as objects or categories, have been proposed to handle variations in appearance. In this paper, we introduce a novel VPR approach that remains robust to scene changes and does not require additional training. Our method constructs semantic image descriptors by extracting pixel-level embeddings using a zero-shot, language-driven semantic segmentation model. We validate our approach in challenging place recognition scenarios using real-world public dataset. The experiments demonstrate that our method outperforms non-learned image representation techniques and off-the-shelf convolutional neural network (CNN) descriptors. Our code is available at https: //github.com/woo-soojin/context-based-vlpr.

[Arxiv](https://arxiv.org/abs/2410.19341)