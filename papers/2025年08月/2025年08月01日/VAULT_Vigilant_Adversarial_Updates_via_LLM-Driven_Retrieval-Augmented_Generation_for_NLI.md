# VAULT：通过基于LLM的检索增强生成实现警惕的对抗更新，用于自然语言推理

发布时间：2025年08月01日

`RAG` `对抗生成`

> VAULT: Vigilant Adversarial Updates via LLM-Driven Retrieval-Augmented Generation for NLI

# 摘要

> 我们很高兴推出VAULT，一个完全自动化的对抗RAG管道。它通过三个阶段——检索、对抗生成和迭代重新训练——系统地发现并修复自然语言推理模型中的弱点。首先，VAULT利用语义相似性（BGE）和词汇相似性（BM25）嵌入前提，执行平衡的少量样本检索。接着，它将这些上下文整合成LLM提示，生成对抗假设，并通过LLM集合验证这些假设的标签保真度。最后，VAULT将这些经过验证的对抗示例逐步注入训练集，以不断增加的混合比例，从而逐步强化零样本RoBERTa-base模型。在标准基准测试中，VAULT显著提升了RoBERTa-base的性能：在SNLI上从88.48%提升至92.60%，ANLI从75.04%提升至80.95%，MultiNLI更是大幅跃升至71.99%（提升了17.32%）。此外，VAULT在所有数据集上都超越了先前的上下文对抗方法，最高提升了2.0%。通过大规模自动化高质量对抗数据的整理，VAULT为自然语言推理任务带来了快速、无需人工干预的鲁棒性提升。

> We introduce VAULT, a fully automated adversarial RAG pipeline that systematically uncovers and remedies weaknesses in NLI models through three stages: retrieval, adversarial generation, and iterative retraining. First, we perform balanced few-shot retrieval by embedding premises with both semantic (BGE) and lexical (BM25) similarity. Next, we assemble these contexts into LLM prompts to generate adversarial hypotheses, which are then validated by an LLM ensemble for label fidelity. Finally, the validated adversarial examples are injected back into the training set at increasing mixing ratios, progressively fortifying a zero-shot RoBERTa-base model.On standard benchmarks, VAULT elevates RoBERTa-base accuracy from 88.48% to 92.60% on SNLI +4.12%, from 75.04% to 80.95% on ANLI +5.91%, and from 54.67% to 71.99% on MultiNLI +17.32%. It also consistently outperforms prior in-context adversarial methods by up to 2.0% across datasets. By automating high-quality adversarial data curation at scale, VAULT enables rapid, human-independent robustness improvements in NLI inference tasks.

[Arxiv](https://arxiv.org/abs/2508.00965)