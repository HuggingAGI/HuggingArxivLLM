# MUCAR：面向多模态大型语言模型的多语言跨模态歧义消解基准测试

发布时间：2025年06月20日

`LLM应用` `多模态`

> MUCAR: Benchmarking Multilingual Cross-Modal Ambiguity Resolution for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在视觉语言任务中取得了显著进展。它们能够有效理解具有明确意义的图像-文本对，得益于强大的图像-文本对齐能力。然而，解决自然语言和视觉环境中的固有模糊性仍具挑战。现有基准测试通常忽略语言和视觉模糊性，主要依赖单一模态上下文消歧，未能充分利用跨模态相互澄清潜力。

为填补这一空白，我们推出MUCAR——首个专为跨多语言和跨模态场景下的多模态模糊性解决能力评估设计的基准测试。MUCAR包含两个关键部分：(1)一个多语言数据集，模糊文本表达通过视觉上下文得到唯一解析；(2)一个双模糊数据集，系统性地将模糊图像与模糊文本上下文配对，每对组合都经过精心构造，通过相互消歧得到一个清晰解释。

对19个先进多模态模型（包括开源和专有架构）的广泛评估显示，与人类水平相比存在显著差距。这凸显了未来研究更复杂跨模态模糊理解方法的必要性，进一步推动了多模态推理的边界。

> Multimodal Large Language Models (MLLMs) have demonstrated significant advances across numerous vision-language tasks. Due to their strong image-text alignment capability, MLLMs can effectively understand image-text pairs with clear meanings. However, effectively resolving the inherent ambiguities in natural language and visual contexts remains challenging. Existing multimodal benchmarks typically overlook linguistic and visual ambiguities, relying mainly on unimodal context for disambiguation and thus failing to exploit the mutual clarification potential between modalities. To bridge this gap, we introduce MUCAR, a novel and challenging benchmark designed explicitly for evaluating multimodal ambiguity resolution across multilingual and cross-modal scenarios. MUCAR includes: (1) a multilingual dataset where ambiguous textual expressions are uniquely resolved by corresponding visual contexts, and (2) a dual-ambiguity dataset that systematically pairs ambiguous images with ambiguous textual contexts, with each combination carefully constructed to yield a single, clear interpretation through mutual disambiguation. Extensive evaluations involving 19 state-of-the-art multimodal models--encompassing both open-source and proprietary architectures--reveal substantial gaps compared to human-level performance, highlighting the need for future research into more sophisticated cross-modal ambiguity comprehension methods, further pushing the boundaries of multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2506.17046)