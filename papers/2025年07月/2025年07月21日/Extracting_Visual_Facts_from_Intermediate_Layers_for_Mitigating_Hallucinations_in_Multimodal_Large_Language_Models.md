# 提取视觉事实：缓解多模态大语言模型中的幻觉问题，从中间层开始

发布时间：2025年07月21日

`LLM应用` `多模态` `视觉识别`

> Extracting Visual Facts from Intermediate Layers for Mitigating Hallucinations in Multimodal Large Language Models

# 摘要

> 多模态大语言模型 (MLLMs) 已经取得了显著进展，它们通过融合视觉识别与语言理解，生成的内容既连贯又在上下文中准确无误。然而，MLLMs 在处理对象幻觉问题上仍存在挑战，即模型可能会生成看似合理却事实错误的输出，甚至包含图像中根本不存在的对象。近期研究揭示，MLLMs 中的先验知识会显著抑制深层视觉信息，从而导致幻觉输出。然而，这些先验知识如何在中间层抑制视觉信息的具体机制仍不明确。我们发现，视觉事实知识与中间层先验/原始概率分布之间的差异在中间层呈现相似的演变趋势。基于这一发现，我们提出了一种名为通过提取视觉事实进行解码 (EVA) 的方法。这是一个无需训练、简单易行的解决方案，能够动态选择包含最多视觉事实信息的中间层。通过对比原始输入和纯文本输入所选层的输出分布，EVA 提取视觉事实知识，并将其按比例融入最终层以校正输出对数概率。值得注意的是，EVA 是一种模型不可知的方法，能够与各种经典解码策略无缝集成，适用于不同的 MLLMs。我们在广泛使用的基准测试中验证了 EVA 的有效性，结果显示与基线方法相比，EVA 显著降低了幻觉率，证明了其在缓解幻觉问题方面的卓越效果。

> Multimodal Large Language Models (MLLMs) have made significant strides by combining visual recognition and language understanding to generate content that is both coherent and contextually accurate. However, MLLMs continue to struggle with object hallucinations, where models produce seemingly plausible but factually incorrect outputs, including objects that do not exist in the image. Recent work has revealed that the prior knowledge in MLLMs significantly suppresses visual information in deep layers, causing hallucinatory outputs. However, how these priors suppress visual information at the intermediate layer stage in MLLMs remains unclear. We observe that visual factual knowledge and the differences between intermediate-layer prior/original probability distributions show similar evolutionary trends in intermediate layers. Motivated by this, we introduce Decoding by Extracting Visual Facts (EVA), a simple, training-free method that dynamically selects intermediate layers with the most significant visual factual information. By contrasting the output distributions of the selected layer derived from the original input and pure-text input, EVA extracts visual factual knowledge and proportionally incorporates it into the final layer to correct the output logits. Importantly, EVA is model-agnostic, seamlessly integrates with various classic decoding strategies, and is applicable across different MLLMs. We validate EVA on widely-used benchmarks, and the results show that it significantly reduces hallucination rates compared to baseline methods, underscoring its effectiveness in mitigating hallucinations.

[Arxiv](https://arxiv.org/abs/2507.15652)