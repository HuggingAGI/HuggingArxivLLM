# 优先处理图像相关标记，提升视觉语言预训练效果

发布时间：2025年05月13日

`LLM理论` `视觉-语言模型` `图像生成`

> Prioritizing Image-Related Tokens Enhances Vision-Language Pre-Training

# 摘要

> 在标准大视觉-语言模型（LVLMs）的预训练中，模型通常通过下一个词预测（NTP）最大化基于图像的描述的联合概率。然而，由于只有少量的描述词直接关联视觉内容，这种简单的NTP方法无意中使模型拟合噪声，增加了幻觉的风险。我们提出了一种名为PRIOR的简单视觉-语言预训练方法，通过在NTP损失中对图像相关词进行差异加权，借鉴重要性采样框架，解决了这一问题。PRIOR引入了一个文本-only的大型语言模型（LLM）作为参考模型，该模型仅基于描述进行训练，不使用图像输入，根据每个词在LVLMs训练中的概率对其进行加权。直观上，直接关联视觉输入的词在没有图像的情况下更难预测，因此从文本-only的参考LLM获得更低的概率。在训练过程中，我们根据重要性评分实现了一个基于词的重新加权项，以调整每个词的损失。我们分别在两种不同的设置中实现PRIOR：带有视觉编码器的LVLMs和没有视觉编码器的LVLMs。与NTP相比，我们在多个视觉-语言基准测试中观察到平均相对提升分别为19%和8%。此外，PRIOR表现出更优越的扩展性能，如显著更高的扩展系数所示，表明与NTP相比，随着计算和数据的增加，PRIOR具有更大的性能提升潜力。

> In standard large vision-language models (LVLMs) pre-training, the model typically maximizes the joint probability of the caption conditioned on the image via next-token prediction (NTP); however, since only a small subset of caption tokens directly relates to the visual content, this naive NTP unintentionally fits the model to noise and increases the risk of hallucination. We present PRIOR, a simple vision-language pre-training approach that addresses this issue by prioritizing image-related tokens through differential weighting in the NTP loss, drawing from the importance sampling framework. PRIOR introduces a reference model-a text-only large language model (LLM) trained on the captions without image inputs, to weight each token based on its probability for LVLMs training. Intuitively, tokens that are directly related to the visual inputs are harder to predict without the image and thus receive lower probabilities from the text-only reference LLM. During training, we implement a token-specific re-weighting term based on the importance scores to adjust each token's loss. We implement PRIOR in two distinct settings: LVLMs with visual encoders and LVLMs without visual encoders. We observe 19% and 8% average relative improvement, respectively, on several vision-language benchmarks compared to NTP. In addition, PRIOR exhibits superior scaling properties, as demonstrated by significantly higher scaling coefficients, indicating greater potential for performance gains compared to NTP given increasing compute and data.

[Arxiv](https://arxiv.org/abs/2505.08971)