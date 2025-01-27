# 减轻生成式AI驱动的证据污染，助力上下文外多模态虚假信息检测

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了大型生成式AI模型（GenAI）在生成欺骗性内容时引发的信息安全问题，并提出了应对污染证据的策略。虽然涉及到了多模态虚假信息检测，但其核心关注点是如何应对GenAI模型在生成内容时带来的挑战，因此属于LLM应用的范畴。` `信息安全` `虚假信息检测`

> Mitigating GenAI-powered Evidence Pollution for Out-of-Context Multimodal Misinformation Detection

# 摘要

> 尽管大型生成式AI模型（GenAI）取得了显著成就，但其潜在的欺骗性内容生成能力也引发了日益严重的信息安全问题。上下文外（OOC）多模态虚假信息检测通常依赖网络证据来识别图像在虚假语境中的滥用，但在面对GenAI污染的证据时，推理准确性面临挑战。现有研究通过风格重写在声明层面模拟GenAI污染，掩盖语言线索，却忽视了证据层面的污染问题。本研究探讨了污染证据对现有OOC检测器性能的影响，发现性能下降超过9个百分点。为此，我们提出了跨模态证据重排序和跨模态声明-证据推理两种策略，以应对污染证据的挑战。在两个基准数据集上的大量实验表明，这些策略能显著提升现有OOC检测器在污染证据环境下的鲁棒性。

> While large generative artificial intelligence (GenAI) models have achieved significant success, they also raise growing concerns about online information security due to their potential misuse for generating deceptive content. Out-of-context (OOC) multimodal misinformation detection, which often retrieves Web evidence to identify the repurposing of images in false contexts, faces the issue of reasoning over GenAI-polluted evidence to derive accurate predictions. Existing works simulate GenAI-powered pollution at the claim level with stylistic rewriting to conceal linguistic cues, and ignore evidence-level pollution for such information-seeking applications. In this work, we investigate how polluted evidence affects the performance of existing OOC detectors, revealing a performance degradation of more than 9 percentage points. We propose two strategies, cross-modal evidence reranking and cross-modal claim-evidence reasoning, to address the challenges posed by polluted evidence. Extensive experiments on two benchmark datasets show that these strategies can effectively enhance the robustness of existing out-of-context detectors amidst polluted evidence.

[Arxiv](https://arxiv.org/abs/2501.14728)