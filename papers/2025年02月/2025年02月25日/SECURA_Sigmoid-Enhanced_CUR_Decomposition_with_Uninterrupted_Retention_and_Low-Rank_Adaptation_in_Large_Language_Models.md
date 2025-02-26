# # SECURA：Sigmoid增强的CUR分解在大型语言模型中的持续保留与低秩自适应
# SECURA：大型语言模型中基于Sigmoid增强的CUR分解实现持续保留与低秩自适应

发布时间：2025年02月25日

`LLM理论` `机器学习`

> SECURA: Sigmoid-Enhanced CUR Decomposition with Uninterrupted Retention and Low-Rank Adaptation in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 的快速发展使得全微调 (FT) 变得不切实际，原因在于其高昂的计算成本和可能引发的灾难性遗忘问题。为此，我们提出了低秩适应 (LoRA) 作为替代方案，通过仅微调少量参数，在显著降低资源需求的同时达到与 FT 相似的性能。然而，LoRA 仍未能完全解决灾难性遗忘的难题。
    
    为应对这一挑战，我们推出了 SECURA，一种创新的参数高效微调 (PEFT) 方法。该方法引入了新型归一化技术 SigNorm，有效提升参数保留能力与整体性能表现。
    
    SECURA 在数学问题解决 (GSM8K)、复杂问答 (CNNDM)、翻译 (NewsDE) 和多项选择推理 (LogiQA) 等多种任务中接受了全面评估。实验数据显示，在 Gemma2 2b、Qwen2 1.5b、Qwen 2 7b、Llama3 8b 和 Llama3.1 8b 等模型上，与 DoRA 相比，SECURA 在多项选择题 (MCQ) 任务中平均提升 3.59%，问答 (QA) 任务中平均提升 2.51%。此外，SECURA 在知识保留方面表现卓越，在 16 项连续学习测试中，基本 LLM 知识准确率始终保持在 70% 以上，优于经验回放 (ER)、序列学习 (SEQ)、EWC、I-LoRA 和 CUR-LoRA 等方法。

> With the rapid development of large language models (LLMs), fully fine-tuning (FT) these models has become increasingly impractical due to the high computational demands. Additionally, FT can lead to catastrophic forgetting. As an alternative, Low-Rank Adaptation (LoRA) has been proposed, which fine-tunes only a small subset of parameters, achieving similar performance to FT while significantly reducing resource requirements. However, since LoRA inherits FT's design, the issue of catastrophic forgetting remains.
  To address these challenges, we propose SECURA: Sigmoid-Enhanced CUR Decomposition LoRA, a novel parameter-efficient fine-tuning (PEFT) variant that mitigates catastrophic forgetting while improving fine-tuning performance. Our method introduces a new normalization technique, SigNorm, to enhance parameter retention and overall performance.
  SECURA has been evaluated on a variety of tasks, including mathematical problem-solving (GSM8K), challenging question-answering (CNNDM), translation (NewsDE), and complex multiple-choice reasoning (LogiQA). Experimental results show that SECURA achieves an average fine-tuning improvement of 3.59% across four multiple-choice question (MCQ) tasks and a 2.51% improvement across five question-answering (QA) tasks on models such as Gemma2 2b, Qwen2 1.5b, Qwen 2 7b, Llama3 8b, and Llama3.1 8b, compared to DoRA. Moreover, SECURA demonstrates superior knowledge retention capabilities, maintaining more than 70% accuracy on basic LLM knowledge across 16 continual learning tests, outperforming Experience Replay (ER), Sequential Learning (SEQ), EWC, I-LoRA, and CUR-LoRA.

[Arxiv](https://arxiv.org/abs/2502.18168)