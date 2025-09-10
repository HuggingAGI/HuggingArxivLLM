# HALT-RAG：任务自适应的幻觉检测框架——基于校准NLI集成与弃权机制

发布时间：2025年09月09日

`RAG` `基础理论`

> HALT-RAG: A Task-Adaptable Framework for Hallucination Detection with Calibrated NLI Ensembles and Abstention

# 摘要

> 检测与给定源文本矛盾或缺乏支持的内容，是生成式语言模型安全部署的关键挑战。为此，我们提出HALT-RAG——一个事后验证系统，专门用于识别检索增强生成（RAG）管道输出中的幻觉内容。该框架灵活且适应任务，其通用特征集源自两个冻结的现成自然语言推理（NLI）模型集成，以及轻量级词汇信号。这些特征用于训练一个简单、校准良好且适应任务的元分类器。为防止数据泄露并生成无偏估计，我们采用严格的5折交叉验证（OOF）训练协议，在HaluEval基准上对系统进行评估。通过将通用特征集与轻量级、适应任务的分类器及精确约束决策策略相结合，HALT-RAG在摘要、问答（QA）和对话任务上分别取得0.7756、0.9786和0.7391的优异OOF F1分数。系统校准良好的概率支持实用的弃权机制，为平衡模型性能与安全需求提供了可靠工具。

> Detecting content that contradicts or is unsupported by a given source text is a critical challenge for the safe deployment of generative language models. We introduce HALT-RAG, a post-hoc verification system designed to identify hallucinations in the outputs of Retrieval-Augmented Generation (RAG) pipelines. Our flexible and task-adaptable framework uses a universal feature set derived from an ensemble of two frozen, off-the-shelf Natural Language Inference (NLI) models and lightweight lexical signals. These features are used to train a simple, calibrated, and task-adapted meta-classifier. Using a rigorous 5-fold out-of-fold (OOF) training protocol to prevent data leakage and produce unbiased estimates, we evaluate our system on the HaluEval benchmark. By pairing our universal feature set with a lightweight, task-adapted classifier and a precision-constrained decision policy, HALT-RAG achieves strong OOF F1-scores of 0.7756, 0.9786, and 0.7391 on the summarization, QA, and dialogue tasks, respectively. The system's well-calibrated probabilities enable a practical abstention mechanism, providing a reliable tool for balancing model performance with safety requirements.

[Arxiv](https://arxiv.org/abs/2509.07475)