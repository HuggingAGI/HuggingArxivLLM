# COIG-P：一个高质量且大规模的中文偏好数据集，旨在实现与人类价值观的对齐。

发布时间：2025年04月07日

`LLM应用

LLM应用` `人工智能`

> COIG-P: A High-Quality and Large-Scale Chinese Preference Dataset for Alignment with Human Values

# 摘要

> 在将大型语言模型（LLMs）与人类偏好对齐方面，已经取得了显著的成功。然而，现有的中文偏好数据集受到规模较小、领域覆盖范围狭窄以及缺乏严格数据验证的限制。此外，依赖人工标注员对指令和响应进行标注，极大地限制了人类偏好数据集的可扩展性。为了解决这些挑战，我们设计了一个无需人工干预的基于LLM的中文偏好数据集标注流水线。具体来说，我们爬取并仔细筛选了92,000个高质量的中文查询，并使用15个主流的LLMs生成并评分选定的被拒绝响应对。基于此，我们引入了COIG-P（中文开放指令通用模型-偏好），这是一个高质量、大规模的中文偏好数据集，包含1,009,000个中文偏好对，涵盖6个多样化领域：聊天、代码、数学、逻辑、小说和角色。基于COIG-P，为了降低使用LLMs进行评分的开销，我们训练了一个8B规模的中文奖励模型（CRM），并精心构建了一个中文奖励基准（CRBench）。根据AlignBench \citep{liu2024alignbenchbenchmarkingchinesealignment}的评估结果，COIG-P显著优于其他中文偏好数据集，并分别为Qwen2/2.5和Infinity-Instruct-3M-0625模型系列带来了2%到12%的显著性能提升。CRBench上的结果显示，我们的CRM具有强大的稳健评分能力。我们将它应用于COIG-P测试集中的选定-拒绝响应对的筛选，实验表明，它在识别低质量样本方面与GPT-4相当，同时保持了高效性和成本效益。我们的代码和数据已发布在https://github.com/multimodal-art-projection/COIG-P。

> Aligning large language models (LLMs) with human preferences has achieved remarkable success. However, existing Chinese preference datasets are limited by small scale, narrow domain coverage, and lack of rigorous data validation. Additionally, the reliance on human annotators for instruction and response labeling significantly constrains the scalability of human preference datasets. To address these challenges, we design an LLM-based Chinese preference dataset annotation pipeline with no human intervention. Specifically, we crawled and carefully filtered 92k high-quality Chinese queries and employed 15 mainstream LLMs to generate and score chosen-rejected response pairs. Based on it, we introduce COIG-P (Chinese Open Instruction Generalist - Preference), a high-quality, large-scale Chinese preference dataset, comprises 1,009k Chinese preference pairs spanning 6 diverse domains: Chat, Code, Math, Logic, Novel, and Role. Building upon COIG-P, to reduce the overhead of using LLMs for scoring, we trained a 8B-sized Chinese Reward Model (CRM) and meticulously constructed a Chinese Reward Benchmark (CRBench). Evaluation results based on AlignBench \citep{liu2024alignbenchbenchmarkingchinesealignment} show that that COIG-P significantly outperforms other Chinese preference datasets, and it brings significant performance improvements ranging from 2% to 12% for the Qwen2/2.5 and Infinity-Instruct-3M-0625 model series, respectively. The results on CRBench demonstrate that our CRM has a strong and robust scoring ability. We apply it to filter chosen-rejected response pairs in a test split of COIG-P, and our experiments show that it is comparable to GPT-4o in identifying low-quality samples while maintaining efficiency and cost-effectiveness. Our codes and data are released in https://github.com/multimodal-art-projection/COIG-P.

[Arxiv](https://arxiv.org/abs/2504.05535)