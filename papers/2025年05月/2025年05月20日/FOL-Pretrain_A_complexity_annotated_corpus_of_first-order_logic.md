# # FOL-Pretrain
FOL-Pretrain：一个标注复杂度的一阶逻辑语料库。

发布时间：2025年05月20日

`LLM理论` `人工智能` `数据科学`

> FOL-Pretrain: A complexity annotated corpus of first-order logic

# 摘要

> 基于Transformer的大型语言模型（LLMs）在编程、数学问题解决和常识推理等任务中展现出了卓越的推理能力。尽管这些任务复杂度各异，但都需要模型整合并处理结构化信息。尽管已有通过受控实验逆向研究LLMs行为的努力，但对其如何内化和执行复杂算法的理解仍显不足。目前研究多局限于小规模或浅层次任务，如基础算术和语法规则匹配。理解上的一个重要障碍在于预训练数据的性质——海量、异质且标注不完善，导致难以孤立研究推理机制。为填补这一空白，我们推出一个大规模、完全开放、附带复杂度标注的一阶逻辑推理轨迹数据集，旨在深入探究LLMs的算法推理机制。该数据集包含35亿个令牌，其中880万个为LLM增强且人工标注的示例，750万个为合成生成的示例。每个合成示例均经验证正确，由定制自动定理证明器生成，并附带追踪其算法来源的元数据。我们的目标是为研究LLMs如何学习和泛化符号推理过程提供一个可扩展且可解释的工具，从而为更透明和有针对性地探究现代模型的算法能力铺平道路。

> Transformer-based large language models (LLMs) have demonstrated remarkable reasoning capabilities such as coding and solving mathematical problems to commonsense inference. While these tasks vary in complexity, they all require models to integrate and compute over structured information. Despite recent efforts to reverse-engineer LLM behavior through controlled experiments, our understanding of how these models internalize and execute complex algorithms remains limited. Progress has largely been confined to small-scale studies or shallow tasks such as basic arithmetic and grammatical pattern matching. One barrier to deeper understanding is the nature of pretraining data -- vast, heterogeneous, and often poorly annotated, making it difficult to isolate mechanisms of reasoning. To bridge this gap, we introduce a large-scale, fully open, complexity-annotated dataset of first-order logic reasoning traces, designed to probe and analyze algorithmic reasoning in LLMs. The dataset consists of 3.5 billion tokens, including 8.8 million LLM-augmented, human-annotated examples and 7.5 million synthetically generated examples. Each synthetic example is verifiably correct, produced by a custom automated theorem solver, and accompanied by metadata tracing its algorithmic provenance. We aim to provide a scalable, interpretable artifact for studying how LLMs learn and generalize symbolic reasoning processes, paving the way for more transparent and targeted investigations into the algorithmic capabilities of modern models.

[Arxiv](https://arxiv.org/abs/2505.14932)