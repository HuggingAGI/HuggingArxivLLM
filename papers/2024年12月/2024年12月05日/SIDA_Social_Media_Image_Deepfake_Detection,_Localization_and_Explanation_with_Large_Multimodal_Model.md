# SIDA：借助大型多模态模型实现社交媒体图像深度伪造的检测、定位与解释

发布时间：2024年12月05日

`LLM应用` `社交媒体` `图像检测`

> SIDA: Social Media Image Deepfake Detection, Localization and Explanation with Large Multimodal Model

# 摘要

> 生成式模型在创造高度逼真图像方面的迅猛发展，给错误信息的传播带来了重大风险。比如，一张合成图像在社交媒体上分享时，可能会误导众多受众，削弱对数字内容的信任，进而引发严重后果。尽管有一定进展，但学术界尚未为社交媒体创建一个大规模且多样化的深度伪造检测数据集，也未设计出有效的解决方案来应对此问题。在本文中，我们推出了社交媒体图像检测数据集（SID-Set），它有三大关键优势：（1）数量庞大，包含 30 万张带有详尽注释的 AI 生成/篡改及真实图像；（2）种类多样，涵盖了各类完全合成和篡改的图像；（3）逼真度高，多数图像仅靠肉眼观察难以与真实图像区分。此外，借助大型多模态模型的出色能力，我们提出了一个新的图像深度伪造检测、定位和解释框架，名为 SIDA（社交媒体图像检测、定位和解释助手）。SIDA 不仅能够辨别图像的真伪，还能通过掩码预测勾勒出篡改区域，并提供模型判断标准的文字解释。与 SID-Set 和其他基准上的先进深度伪造检测模型相比，大量实验表明，SIDA 在多种设置中表现卓越。代码、模型和数据集将会发布。

> The rapid advancement of generative models in creating highly realistic images poses substantial risks for misinformation dissemination. For instance, a synthetic image, when shared on social media, can mislead extensive audiences and erode trust in digital content, resulting in severe repercussions. Despite some progress, academia has not yet created a large and diversified deepfake detection dataset for social media, nor has it devised an effective solution to address this issue. In this paper, we introduce the Social media Image Detection dataSet (SID-Set), which offers three key advantages: (1) extensive volume, featuring 300K AI-generated/tampered and authentic images with comprehensive annotations, (2) broad diversity, encompassing fully synthetic and tampered images across various classes, and (3) elevated realism, with images that are predominantly indistinguishable from genuine ones through mere visual inspection. Furthermore, leveraging the exceptional capabilities of large multimodal models, we propose a new image deepfake detection, localization, and explanation framework, named SIDA (Social media Image Detection, localization, and explanation Assistant). SIDA not only discerns the authenticity of images, but also delineates tampered regions through mask prediction and provides textual explanations of the model's judgment criteria. Compared with state-of-the-art deepfake detection models on SID-Set and other benchmarks, extensive experiments demonstrate that SIDA achieves superior performance among diversified settings. The code, model, and dataset will be released.

[Arxiv](https://arxiv.org/abs/2412.04292)