# Nullu：借由 HalluSpace 投影来缓解大型视觉语言模型中的对象幻觉

发布时间：2024年12月18日

`LLM应用` `计算机视觉` `人工智能`

> Nullu: Mitigating Object Hallucinations in Large Vision-Language Models via HalluSpace Projection

# 摘要

> 近期研究显示，大型视觉语言模型（LVLMs）常受物体幻觉（OH）问题的困扰。为缓解此问题，我们引入了一种基于不安全子空间来编辑模型权重的高效方法，在本文中称之为 HalluSpace。以伴随视觉内容的真实和幻觉文本提示作为输入，通过提取幻觉嵌入特征并去除 LVLMs 中的真实表示，就能识别出 HalluSpace。对模型权重进行正交化处理后，输入特征会被投影到 HalluSpace 的零空间以减少 OH，基于此我们将该方法命名为 Nullu。我们发现，HalluSpaces 通常包含用于构建 LVLMs 的大型语言模型（LLMs）的统计偏差和单峰先验，这在过往研究中已被证实是 OH 的根本原因。所以，零空间投影抑制了 LLMs 的先验，从而过滤掉幻觉特征，得到上下文准确的输出。实验表明，我们的方法能在不同的 LVLM 系列中有效缓解 OH，无需额外的推理成本，在一般的 LVLM 基准测试中也有出色表现。代码发布于 url{https://github.com/Ziwei-Zheng/Nullu}。

> Recent studies have shown that large vision-language models (LVLMs) often suffer from the issue of object hallucinations (OH). To mitigate this issue, we introduce an efficient method that edits the model weights based on an unsafe subspace, which we call HalluSpace in this paper. With truthful and hallucinated text prompts accompanying the visual content as inputs, the HalluSpace can be identified by extracting the hallucinated embedding features and removing the truthful representations in LVLMs. By orthogonalizing the model weights, input features will be projected into the Null space of the HalluSpace to reduce OH, based on which we name our method Nullu. We reveal that HalluSpaces generally contain statistical bias and unimodal priors of the large language models (LLMs) applied to build LVLMs, which have been shown as essential causes of OH in previous studies. Therefore, null space projection suppresses the LLMs' priors to filter out the hallucinated features, resulting in contextually accurate outputs. Experiments show that our method can effectively mitigate OH across different LVLM families without extra inference costs and also show strong performance in general LVLM benchmarks. Code is released at url{https://github.com/Ziwei-Zheng/Nullu}.

[Arxiv](https://arxiv.org/abs/2412.13817)