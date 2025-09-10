# D-LEAF：基于层-头注意力诊断的多模态大型语言模型幻觉定位与纠正

发布时间：2025年09月09日

`LLM应用` `媒体与娱乐`

> D-LEAF: Localizing and Correcting Hallucinations in Multimodal LLMs via Layer-to-head Attention Diagnostics

# 摘要

> 多模态大型语言模型（MLLMs）在图像描述、视觉问答等任务中表现亮眼，却常陷入“幻觉”困境——生成的文本与视觉输入南辕北辙。先前研究认为，这部分源于视觉注意力的匮乏；然而现有基于注意力的检测与缓解方案，往往对所有层和注意力头“一刀切”地调整，反而让错误根源变得模糊不清。本文中，我们首先证实：这些方法根本无法精准锁定问题层出在哪一层。为此，我们提出两种诊断工具：层图像注意力熵（LIAE）——专门标记异常层；图像注意力焦点（IAF）——负责给这些层里的注意力头打分。分析显示，LIAE能精准揪出问题层，IAF则能靠谱地给需要修正的注意力头排好优先级。借助这些信号，我们研发出动态分层熵与注意力融合（D-LEAF）——这是一种不挑任务、靠注意力驱动的方法，推理时能动态定位并修正错误，而且几乎不增加额外开销。实验结果显示，D-LEAF在标准图像描述数据集上相对性能提升53%，视觉问答任务的准确率和F1分数也各涨约4%，在高效运行的同时，成功大幅压制了幻觉问题。

> Multimodal Large Language Models (MLLMs) achieve strong performance on tasks like image captioning and visual question answering, but remain prone to hallucinations, where generated text conflicts with the visual input. Prior work links this partly to insufficient visual attention, but existing attention-based detectors and mitigation typically apply uniform adjustments across layers and heads, obscuring where errors originate. In this paper, we first show these methods fail to accurately localize problematic layers. Then, we introduce two diagnostics: Layer Image Attention Entropy (LIAE) which flags anomalous layers, and Image Attention Focus (IAF) which scores attention heads within those layers. Analysis shows that LIAE pinpoints faulty layers and IAF reliably ranks heads that warrant correction. Guided by these signals, we propose Dynamic Layer-wise Entropy and Attention Fusion (D-LEAF), a task-agnostic, attention-guided method that dynamically localizes and corrects errors during inference with negligible overhead. Results show our D-LEAF delivers a 53% relative improvement on standard captioning benchmarks, and on VQA both accuracy and F1-score improve by approximately 4%, substantially suppressing hallucinations while preserving efficiency.

[Arxiv](https://arxiv.org/abs/2509.07864)