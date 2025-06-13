# # 神经连接在BEA 2025共享任务中的研究：AI导师错误识别的检索增强提示方法

发布时间：2025年06月12日

`LLM应用` `教育评估`

> NeuralNexus at BEA 2025 Shared Task: Retrieval-Augmented Prompting for Mistake Identification in AI Tutors

# 摘要

> 本文介绍了我们在BEA 2025共享任务Track 1中的AI赋能导师教学能力评估系统，该任务专注于错误识别。我们的系统通过评估导师回复是否准确识别了学生数学推理中的错误来实现教学能力评估。我们采用了四种创新方法：(1) 多个预训练语言模型融合的token嵌入机器学习模型集成；(2) 基于[CLS]嵌入和MLP分类器的冻结句向量模型；(3) 引入多头注意力的历史感知模型；(4) 基于GPT 4o的增强型少量样本提示系统。最终系统通过检索语义相似示例、构建结构化提示，并结合基于模式的输出解析，生成了可解释的预测结果。实验结果表明，将示例驱动的提示与LLM推理相结合在教学反馈评估中具有显著优势。我们的代码已开源，详情请访问https://github.com/NaumanNaeem/BEA_2025。

> This paper presents our system for Track 1: Mistake Identification in the BEA 2025 Shared Task on Pedagogical Ability Assessment of AI-powered Tutors. The task involves evaluating whether a tutor's response correctly identifies a mistake in a student's mathematical reasoning. We explore four approaches: (1) an ensemble of machine learning models over pooled token embeddings from multiple pretrained language models (LMs); (2) a frozen sentence-transformer using [CLS] embeddings with an MLP classifier; (3) a history-aware model with multi-head attention between token-level history and response embeddings; and (4) a retrieval-augmented few-shot prompting system with a large language model (LLM) i.e. GPT 4o. Our final system retrieves semantically similar examples, constructs structured prompts, and uses schema-guided output parsing to produce interpretable predictions. It outperforms all baselines, demonstrating the effectiveness of combining example-driven prompting with LLM reasoning for pedagogical feedback assessment. Our code is available at https://github.com/NaumanNaeem/BEA_2025.

[Arxiv](https://arxiv.org/abs/2506.10627)