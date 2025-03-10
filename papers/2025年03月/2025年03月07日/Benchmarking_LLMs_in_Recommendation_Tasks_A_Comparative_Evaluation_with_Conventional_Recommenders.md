# # 标题
评测 LLM 在推荐任务中的性能：与传统推荐器的对比评估

发布时间：2025年03月07日

`LLM应用` `推荐系统`

> Benchmarking LLMs in Recommendation Tasks: A Comparative Evaluation with Conventional Recommenders

# 摘要

> 近年来，大型语言模型（LLMs）与推荐系统的结合为提升推荐质量开辟了新途径。然而，要全面评估并比较LLMs与传统推荐系统的表现，仍需建立一个全面的基准。为此，我们提出了RecBench，该框架系统性地研究了多种项目表示形式（包括唯一标识符、文本、语义嵌入和语义标识符），并评估了两大核心推荐任务：点击率预测（CTR）和序列推荐（SeqRec）。我们的实验涵盖了17个大型模型，并在来自时尚、新闻、视频、书籍和音乐领域的5个多样化数据集上开展。研究发现，基于LLMs的推荐器优于传统推荐器，在CTR场景下AUC提升了5%，在SeqRec场景下NDCG@10提升了170%。然而，这些性能提升是以推理效率大幅下降为代价的，这使得将LLMs作为推荐系统（RS）的范式在实时推荐环境中难以实现。我们希望这些发现能为未来研究提供启发，包括专门针对推荐任务的模型加速方法。我们将开放代码、数据、配置和平台，支持其他研究者在此基础上进行扩展和探索。

> In recent years, integrating large language models (LLMs) into recommender systems has created new opportunities for improving recommendation quality. However, a comprehensive benchmark is needed to thoroughly evaluate and compare the recommendation capabilities of LLMs with traditional recommender systems. In this paper, we introduce RecBench, which systematically investigates various item representation forms (including unique identifier, text, semantic embedding, and semantic identifier) and evaluates two primary recommendation tasks, i.e., click-through rate prediction (CTR) and sequential recommendation (SeqRec). Our extensive experiments cover up to 17 large models and are conducted across five diverse datasets from fashion, news, video, books, and music domains. Our findings indicate that LLM-based recommenders outperform conventional recommenders, achieving up to a 5% AUC improvement in the CTR scenario and up to a 170% NDCG@10 improvement in the SeqRec scenario. However, these substantial performance gains come at the expense of significantly reduced inference efficiency, rendering the LLM-as-RS paradigm impractical for real-time recommendation environments. We aim for our findings to inspire future research, including recommendation-specific model acceleration methods. We will release our code, data, configurations, and platform to enable other researchers to reproduce and build upon our experimental results.

[Arxiv](https://arxiv.org/abs/2503.05493)