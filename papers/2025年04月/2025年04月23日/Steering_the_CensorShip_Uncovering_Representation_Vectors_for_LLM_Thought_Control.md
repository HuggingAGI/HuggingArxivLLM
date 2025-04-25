# 驾驭审查之手：揭秘大型语言模型思想控制的表征向量

发布时间：2025年04月23日

`LLM理论` `人工智能伦理`

> Steering the CensorShip: Uncovering Representation Vectors for LLM "Thought" Control

# 摘要

> 大型语言模型（LLMs）彻底改变了我们获取信息的方式。这些模型经过调优以拒绝执行有害请求，并生成更符合控制者偏好的响应。我们采用表示工程学技术研究开放权重的安全调优模型，揭示这种“审查”机制的运作方式。我们提出了一种方法，用于寻找一个拒绝-合规向量，以检测并控制模型输出中的审查程度。我们还分析了源自DeepSeek-R1的近期推理LLMs，通过“思维抑制”揭示了审查的另一个维度。我们表明，类似的方法可用于找到一个抑制模型推理过程的向量，从而通过应用该向量的负倍数来移除审查机制。

> Large language models (LLMs) have transformed the way we access information. These models are often tuned to refuse to comply with requests that are considered harmful and to produce responses that better align with the preferences of those who control the models. To understand how this "censorship" works. We use representation engineering techniques to study open-weights safety-tuned models. We present a method for finding a refusal--compliance vector that detects and controls the level of censorship in model outputs. We also analyze recent reasoning LLMs, distilled from DeepSeek-R1, and uncover an additional dimension of censorship through "thought suppression". We show a similar approach can be used to find a vector that suppresses the model's reasoning process, allowing us to remove censorship by applying the negative multiples of this vector

[Arxiv](https://arxiv.org/abs/2504.17130)