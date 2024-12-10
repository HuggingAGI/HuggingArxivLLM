# 在艺术领域，通过稳定扩散进行的对象检测没有相关注释

发布时间：2024年12月09日

`LLM应用` `数字人文`

> No Annotations for Object Detection in Art through Stable Diffusion

# 摘要

> 在艺术领域，对象检测是数字人文的一项宝贵工具，因为它能比人类更快地识别艺术和历史图像中的对象。不过，由于需要专业的领域知识，给这类图像做标注面临着巨大挑战。我们推出了 NADA（艺术检测无需标注），这是一个借助扩散模型的艺术相关知识来检测绘画中对象的流程，无需完整的边界框监督。我们的方法支持弱监督和零样本两种场景，且无需对其预训练的组件进行任何微调，它由基于大型视觉语言模型的类别提议器和基于 Stable Diffusion 的类别条件检测器构成。NADA 在 ArtDL 2.0 和 IconArt 这两个艺术品数据集上进行了评估，在弱监督检测方面超越了之前的成果，同时也是艺术领域零样本对象检测的首次尝试。相关代码可在 https://github.com/patrick-john-ramos/nada 获取。

> Object detection in art is a valuable tool for the digital humanities, as it allows for faster identification of objects in artistic and historical images compared to humans. However, annotating such images poses significant challenges due to the need for specialized domain expertise. We present NADA (no annotations for detection in art), a pipeline that leverages diffusion models' art-related knowledge for object detection in paintings without the need for full bounding box supervision. Our method, which supports both weakly-supervised and zero-shot scenarios and does not require any fine-tuning of its pretrained components, consists of a class proposer based on large vision-language models and a class-conditioned detector based on Stable Diffusion. NADA is evaluated on two artwork datasets, ArtDL 2.0 and IconArt, outperforming prior work in weakly-supervised detection, while being the first work for zero-shot object detection in art. Code is available at https://github.com/patrick-john-ramos/nada

[Arxiv](https://arxiv.org/abs/2412.06286)