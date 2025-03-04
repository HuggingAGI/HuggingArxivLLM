# **强化视觉微调（Visual-RFT）**：视觉强化微调

发布时间：2025年03月03日

`LLM应用` `多模态`

> Visual-RFT: Visual Reinforcement Fine-Tuning

# 摘要

> 在 OpenAI o1 这类大型推理模型中，强化微调（RFT）通过学习对答案的反馈来进行训练，尤其适用于数据微调稀缺的应用场景。近期开源项目如 DeepSeek-R1 表明，带有可验证奖励的强化学习是复现 o1 的关键方向。尽管 R1 风格的模型在语言模型领域取得了成功，但其在多模态领域的应用仍有待探索。本研究推出视觉强化微调（Visual-RFT），进一步拓展了 RFT 在视觉任务中的应用范围。具体来说，Visual-RFT 利用大型视觉-语言模型（LVLMs）为每个输入生成包含推理标记和最终答案的多个响应，随后采用我们设计的视觉感知可验证奖励函数，结合策略优化算法（如组相对策略优化 GRPO）更新模型。针对不同感知任务，我们设计了相应的奖励函数，例如用于目标检测的交并比（IoU）奖励。在细粒度图像分类、少量样本目标检测、推理定位以及开放词汇目标检测等基准测试中，Visual-RFT 展现了超越监督微调（SFT）的竞争力和卓越的泛化能力。例如，在仅需 100 个样本的一次性细粒度图像分类任务中，Visual-RFT 将准确率提升了 24.3%。在少量样本目标检测中，Visual-RFT 在 COCO 的两样本设置下比基线高出 21.9，在 LVIS 上高出 15.4。我们的 Visual-RFT 代表了对 LVLM 微调范式的重大转变，提供了一种数据高效、奖励驱动的方法，显著提升了特定领域任务的推理和适应能力。

> Reinforcement Fine-Tuning (RFT) in Large Reasoning Models like OpenAI o1 learns from feedback on its answers, which is especially useful in applications when fine-tuning data is scarce. Recent open-source work like DeepSeek-R1 demonstrates that reinforcement learning with verifiable reward is one key direction in reproducing o1. While the R1-style model has demonstrated success in language models, its application in multi-modal domains remains under-explored. This work introduces Visual Reinforcement Fine-Tuning (Visual-RFT), which further extends the application areas of RFT on visual tasks. Specifically, Visual-RFT first uses Large Vision-Language Models (LVLMs) to generate multiple responses containing reasoning tokens and final answers for each input, and then uses our proposed visual perception verifiable reward functions to update the model via the policy optimization algorithm such as Group Relative Policy Optimization (GRPO). We design different verifiable reward functions for different perception tasks, such as the Intersection over Union (IoU) reward for object detection. Experimental results on fine-grained image classification, few-shot object detection, reasoning grounding, as well as open-vocabulary object detection benchmarks show the competitive performance and advanced generalization ability of Visual-RFT compared with Supervised Fine-tuning (SFT). For example, Visual-RFT improves accuracy by $24.3\%$ over the baseline in one-shot fine-grained image classification with around 100 samples. In few-shot object detection, Visual-RFT also exceeds the baseline by $21.9$ on COCO's two-shot setting and $15.4$ on LVIS. Our Visual-RFT represents a paradigm shift in fine-tuning LVLMs, offering a data-efficient, reward-driven approach that enhances reasoning and adaptability for domain-specific tasks.

[Arxiv](https://arxiv.org/abs/2503.01785)