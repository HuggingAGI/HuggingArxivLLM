# LISA: 多模态大语言模型幻觉缓解的分层融合抑制方法

发布时间：2025年07月25日

`LLM应用

论文摘要讨论了多模态大型语言模型（MLLMs）在视觉语言任务中的应用，并提出了一种方法来解决物体幻觉的问题。这属于LLM在实际应用中的优化和改进，因此归类为LLM应用。` `视觉语言` `生成一致性`

> LISA: A Layer-wise Integration and Suppression Approach for Hallucination Mitigation in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在图像描述等视觉语言任务中表现出色，但仍然容易出现物体幻觉，即描述图像中不存在的对象。为了解决这一问题，我们提出了	extbf{LISA}（	extbf{分层集成与抑制方法}），通过层次化调制和多层融合来增强生成一致性。LISA利用MLLMs的功能分层特性，浅层提供视觉定位，中层编码语义，深层则倾向于放大虚假信号。首先，特定区域的频谱调制通过抑制深层的过度放大激活，同时保留浅层的对齐线索，从而稳定注意力。其次，通过基于锚点的路由融合所选层的token级logits，其中token级别的锚点选择和软logit融合在解码过程中实现自适应集成。LISA是完全	extbf{即插即用}的，可以无缝集成到现有的MLLMs中，包括Qwen2.5-VL。在多个基准测试中的实验表明，LISA在【数学公式】上将幻觉减少高达53.6%，并将POPE F1提高了4.5%，展示了其在模型和任务上的强大泛化能力。

> Multimodal Large Language Models (MLLMs) excel in vision-language tasks such as image captioning but remain prone to object hallucinations, where they describe objects that do not appear in the image. To mitigate this, we propose \textbf{LISA}, a \textbf{L}ayer-wise \textbf{I}ntegration and \textbf{S}uppression \textbf{A}pproach that enhances generation consistency through hierarchical modulation and multi-layer fusion. LISA leverages the functional hierarchy within MLLMs, where shallow layers provide visual grounding, middle layers encode semantics, and deep layers tend to amplify spurious signals. First, zone-specific spectral modulation stabilizes attention by suppressing over-amplified activations in deeper layers while preserving alignment cues in earlier layers. Second, token-level logits from selected layers are fused via anchor-based routing, with token-wise anchor selection and soft logit fusion enabling adaptive integration during decoding. LISA is fully \textbf{plug-and-play} and can be seamlessly integrated into existing MLLMs, including Qwen2.5-VL. Experiments on multiple benchmarks show that LISA reduces hallucinations by up to 53.6\% in $\mathrm{CHAIR}_I$ and improves POPE F1 by 4.5\%, demonstrating strong generalization across models and tasks.

[Arxiv](https://arxiv.org/abs/2507.19110)