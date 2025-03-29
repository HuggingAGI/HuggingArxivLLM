# ReaRAG：知识引导推理通过迭代检索增强生成，提升大规模推理模型的事实性.

发布时间：2025年03月27日

`RAG` `问答系统`

> ReaRAG: Knowledge-guided Reasoning Enhances Factuality of Large Reasoning Models with Iterative Retrieval Augmented Generation

# 摘要

> 大型推理模型（LRMs）虽然推理能力出色，但受限于参数化知识，事实准确性不足。尽管近期研究通过强化学习（RL）为这些模型赋予了检索能力，但它们仍存在过度思考和推理不稳健的问题，导致问答（QA）效果欠佳。为解决这一难题，我们提出了ReaRAG——一种增强事实性的推理模型，能够高效探索多样化查询。我们的方案包含一个创新的数据构建框架，并对推理链长度设定了上限。具体来说，首先利用大型推理模型生成深思熟虑的思考过程，然后从预设动作空间（搜索和完成）中选择动作。执行“搜索”动作时，系统会向RAG引擎发起查询，将结果作为观察返回，以指导后续推理。这一过程持续迭代，直至选择“完成”动作。得益于ReaRAG强大的推理能力，我们在多跳问答任务中超越了现有基线。进一步分析显示，ReaRAG具备卓越的反思能力，能够识别错误并优化推理路径。本研究不仅提升了大型推理模型的事实准确性，还成功将稳健推理能力融入检索增强生成（RAG）中。

> Large Reasoning Models (LRMs) exhibit remarkable reasoning abilities but rely primarily on parametric knowledge, limiting factual accuracy. While recent works equip reinforcement learning (RL)-based LRMs with retrieval capabilities, they suffer from overthinking and lack robustness in reasoning, reducing their effectiveness in question answering (QA) tasks. To address this, we propose ReaRAG, a factuality-enhanced reasoning model that explores diverse queries without excessive iterations. Our solution includes a novel data construction framework with an upper bound on the reasoning chain length. Specifically, we first leverage an LRM to generate deliberate thinking, then select an action from a predefined action space (Search and Finish). For Search action, a query is executed against the RAG engine, where the result is returned as observation to guide reasoning steps later. This process iterates until a Finish action is chosen. Benefiting from ReaRAG's strong reasoning capabilities, our approach outperforms existing baselines on multi-hop QA. Further analysis highlights its strong reflective ability to recognize errors and refine its reasoning trajectory. Our study enhances LRMs' factuality while effectively integrating robust reasoning for Retrieval-Augmented Generation (RAG).

[Arxiv](https://arxiv.org/abs/2503.21729)