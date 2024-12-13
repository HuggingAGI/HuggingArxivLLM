# 朝着用于生物医学、具备像素级洞察力的多模态大型语言模型迈进

发布时间：2024年12月12日

`LLM应用` `生物医学` `医学成像`

> Towards a Multimodal Large Language Model with Pixel-Level Insight for Biomedicine

# 摘要

> 近年来，多模态大型语言模型（MLLM）取得显著进展，证实了开发智能生物医学助手的可行性。但当下的生物医学 MLLM 主要聚焦于图像层级的理解，且将交互局限于文本指令，这就限制了其能力范畴和使用的灵活性。在本文中，我们为生物医学领域引入了一款新颖的端到端多模态大型语言模型——MedPLIB，它具备像素层级的理解能力。令人欣喜的是，它支持视觉问答（VQA）、任意像素层级的提示（点、边框和自由形状）以及像素层级的接地。我们提出了一种全新的专家混合（MoE）多阶段训练策略，将 MoE 划分为视觉语言专家模型和像素接地专家模型的单独训练阶段，随后用 MoE 进行微调。该策略有效协调了多任务学习，同时在推理时使计算成本与单个专家模型持平。为推动生物医学 MLLM 的研究，我们引入了医学复杂视觉问答数据集（MeCoVQA），其涵盖用于复杂医学成像问答和图像区域理解的 8 种模态。实验结果显示，MedPLIB 在多项医学视觉语言任务中达成了最前沿的成果。尤为重要的是，在像素接地任务的零样本评估中，MedPLIB 在 mDice 指标上，分别比最佳的小型和大型模型领先 19.7 和 15.6。代码、数据和模型检查点将在 https://github.com/ShawnHuang497/MedPLIB 公开。

> In recent years, Multimodal Large Language Models (MLLM) have achieved notable advancements, demonstrating the feasibility of developing an intelligent biomedical assistant. However, current biomedical MLLMs predominantly focus on image-level understanding and restrict interactions to textual commands, thus limiting their capability boundaries and the flexibility of usage. In this paper, we introduce a novel end-to-end multimodal large language model for the biomedical domain, named MedPLIB, which possesses pixel-level understanding. Excitingly, it supports visual question answering (VQA), arbitrary pixel-level prompts (points, bounding boxes, and free-form shapes), and pixel-level grounding. We propose a novel Mixture-of-Experts (MoE) multi-stage training strategy, which divides MoE into separate training phases for a visual-language expert model and a pixel-grounding expert model, followed by fine-tuning using MoE. This strategy effectively coordinates multitask learning while maintaining the computational cost at inference equivalent to that of a single expert model. To advance the research of biomedical MLLMs, we introduce the Medical Complex Vision Question Answering Dataset (MeCoVQA), which comprises an array of 8 modalities for complex medical imaging question answering and image region understanding. Experimental results indicate that MedPLIB has achieved state-of-the-art outcomes across multiple medical visual language tasks. More importantly, in zero-shot evaluations for the pixel grounding task, MedPLIB leads the best small and large models by margins of 19.7 and 15.6 respectively on the mDice metric. The codes, data, and model checkpoints will be made publicly available at https://github.com/ShawnHuang497/MedPLIB.

[Arxiv](https://arxiv.org/abs/2412.09278)