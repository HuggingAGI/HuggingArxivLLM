# VORD：用于减轻大型视觉语言模型中对象幻觉的视觉顺序校准

发布时间：2024年12月20日

`LLM应用` `视觉语言模型`

> VORD: Visual Ordinal Calibration for Mitigating Object Hallucinations in Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）伴随近期大型语言模型的热潮取得了显著进展。尽管如此，LVLMs 倾向于依据所提供的源内容生成看似合理，实则不准确或不一致的信息。这种被称为“幻觉”的现象，在 LVLMs 的部署期间可能会带来严重的下游影响。为应对此问题，我们推出了 VORD，这是一种简便且有效的方法，它基于修改后的图像对之间的顺序关系校准令牌预测，从而减轻幻觉。VORD 有两种形式：1.）一种无需训练的极简变体，能从修改后的图像对中剔除不合理的令牌；2.）一种可训练的目标函数，对不太可能的令牌予以惩罚。我们的实验表明，VORD 实现了更优的校准，在众多 LVLM 基准测试中有效地缓解了对象幻觉。

> Large Vision-Language Models (LVLMs) have made remarkable developments along with the recent surge of large language models. Despite their advancements, LVLMs have a tendency to generate plausible yet inaccurate or inconsistent information based on the provided source content. This phenomenon, also known as ``hallucinations" can have serious downstream implications during the deployment of LVLMs. To address this, we present VORD a simple and effective method that alleviates hallucinations by calibrating token predictions based on ordinal relationships between modified image pairs. VORD is presented in two forms: 1.) a minimalist training-free variant which eliminates implausible tokens from modified image pairs, and 2.) a trainable objective function that penalizes unlikely tokens. Our experiments demonstrate that VORD delivers better calibration and effectively mitigates object hallucinations on a wide-range of LVLM benchmarks.

[Arxiv](https://arxiv.org/abs/2412.15739)