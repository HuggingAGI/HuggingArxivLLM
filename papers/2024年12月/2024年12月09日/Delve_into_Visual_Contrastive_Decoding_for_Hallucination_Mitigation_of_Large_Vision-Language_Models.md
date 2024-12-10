# 深入探究用于减轻大型视觉语言模型幻觉的视觉对比解码

发布时间：2024年12月09日

`LLM应用`

> Delve into Visual Contrastive Decoding for Hallucination Mitigation of Large Vision-Language Models

# 摘要

> 尽管大型视觉语言模型（LVLMs）在生成与输入视觉内容相关关联的合理响应方面展现出了非凡的能力，然而它们仍饱受幻觉困扰，生成的文本无法精准反映视觉内容。为应对此状况，近期的方法采用对比解码，通过将输出分布与原始及视觉扭曲的样本进行对比来校准模型响应，以无训练的方式呈现出良好的幻觉缓解效果。不过，视觉输入中信息变化的潜力尚未得到充分挖掘，所以深入探究视觉对比解码的行为极具意义。在本文中，我们率先探索了多种用于改变视觉内容的对比解码手段，涵盖图像下采样和编辑。图像下采样会减少详细的文本信息，而编辑能在图像中产生新内容，从而提供新的方面作为视觉对比样本。为进一步研究使用不同对比样本的益处，我们分析了概率层面的指标，例如熵和分布距离。有趣的是，这些样本在不同的 LVLMs 和基准测试中缓解幻觉的效果差异显著。基于我们的分析，我们提出了一种简便且有效的方法来整合对比样本，为在各种场景中应用对比解码提供了实用的解决方案。开展了大量实验来验证不同基准测试中所提出的融合方法。

> While large vision-language models (LVLMs) have shown impressive capabilities in generating plausible responses correlated with input visual contents, they still suffer from hallucinations, where the generated text inaccurately reflects visual contents. To address this, recent approaches apply contrastive decoding to calibrate the model's response via contrasting output distributions with original and visually distorted samples, demonstrating promising hallucination mitigation in a training-free manner. However, the potential of changing information in visual inputs is not well-explored, so a deeper investigation into the behaviors of visual contrastive decoding is of great interest. In this paper, we first explore various methods for contrastive decoding to change visual contents, including image downsampling and editing. Downsampling images reduces the detailed textual information while editing yields new contents in images, providing new aspects as visual contrastive samples. To further study benefits by using different contrastive samples, we analyze probability-level metrics, including entropy and distribution distance. Interestingly, the effect of these samples in mitigating hallucinations varies a lot across LVLMs and benchmarks. Based on our analysis, we propose a simple yet effective method to combine contrastive samples, offering a practical solution for applying contrastive decoding across various scenarios. Extensive experiments are conducted to validate the proposed fusion method among different benchmarks.

[Arxiv](https://arxiv.org/abs/2412.06775)