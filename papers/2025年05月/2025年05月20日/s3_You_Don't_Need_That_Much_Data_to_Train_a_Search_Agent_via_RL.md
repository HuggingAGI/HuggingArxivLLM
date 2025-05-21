# s3: 不需要那么多数据，用强化学习也能训练出优秀的搜索代理

发布时间：2025年05月20日

`RAG` `问答系统`

> s3: You Don't Need That Much Data to Train a Search Agent via RL

# 摘要

> 检索增强生成（RAG）系统赋予大型语言模型（LLMs）访问外部知识的能力，使其在推理过程中更加得心应手。近期研究通过强化学习（RL）使LLMs化身智能搜索代理，借助与检索引擎的多轮互动显著提升了信息获取效率。然而，现有方法在优化检索效果时，要么仅关注搜索指标（如NDCG）而忽视了下游应用的实际价值，要么通过微调整个LLM来实现检索与推理的联合优化，这种做法不仅将检索与生成混为一谈，还限制了其在冻结或专有模型中的实际应用效果。针对这些局限性，我们提出了一种轻量级且适用于各类模型的框架s3。该框架创造性地将搜索器与生成器分离，并引入了Gain Beyond RAG奖励机制，即通过对比原始RAG方法，衡量生成精度的提升。令人惊叹的是，s3仅需2.4k训练样本即可超越在70倍以上数据量上训练的基线模型，其卓越性能在六个通用问答和五个医疗问答基准测试中得到了一致验证。


> Retrieval-augmented generation (RAG) systems empower large language models (LLMs) to access external knowledge during inference. Recent advances have enabled LLMs to act as search agents via reinforcement learning (RL), improving information acquisition through multi-turn interactions with retrieval engines. However, existing approaches either optimize retrieval using search-only metrics (e.g., NDCG) that ignore downstream utility or fine-tune the entire LLM to jointly reason and retrieve-entangling retrieval with generation and limiting the real search utility and compatibility with frozen or proprietary models. In this work, we propose s3, a lightweight, model-agnostic framework that decouples the searcher from the generator and trains the searcher using a Gain Beyond RAG reward: the improvement in generation accuracy over naive RAG. s3 requires only 2.4k training samples to outperform baselines trained on over 70x more data, consistently delivering stronger downstream performance across six general QA and five medical QA benchmarks.

[Arxiv](https://arxiv.org/abs/2505.14146)