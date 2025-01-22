# 从草稿到答案：聚合微调解锁LLM潜能

发布时间：2025年01月20日

`LLM应用

**理由**：这篇论文主要讨论了如何通过聚合微调（AFT）来提升大型语言模型（LLM）的性能，特别是在推理时通过生成和聚合多个草稿响应来优化输出。这种方法属于对LLM的应用层面的改进，旨在通过优化推理过程来提升模型的实际表现，因此应归类为LLM应用。` `机器学习`

> From Drafts to Answers: Unlocking LLM Potential via Aggregation Fine-Tuning

# 摘要

> 扩展数据和模型规模已被证明能有效提升大型语言模型的性能。除了训练时的扩展，最近的研究还发现，增加测试时的计算资源也能进一步提升性能。本文提出了聚合微调（AFT），这是一种监督微调范式，模型通过学习将多个草稿响应（称为提案）合成为一个精炼的答案（称为聚合）。在推理时，提出和聚合策略通过迭代生成并聚合提案，进一步提升了性能。基准数据集上的实验表明，经过AFT训练的模型显著优于标准的SFT。值得注意的是，一个仅用64k数据从Llama3.1-8B-Base微调的AFT模型，在AlpacaEval 2上达到了41.3%的LC胜率，超越了更大的LLMs，如Llama3.1-405B-Instruct和GPT4。通过结合顺序精炼和并行采样，提出和聚合框架以灵活的方式扩展了推理时的计算。这些发现表明，AFT是一种在不增加数据量或模型规模的情况下，解锁LLMs额外能力的有前途的方法。

> Scaling data and model size has been proven effective for boosting the performance of large language models. In addition to training-time scaling, recent studies have revealed that increasing test-time computational resources can further improve performance. In this work, we introduce Aggregation Fine-Tuning (AFT), a supervised finetuning paradigm where the model learns to synthesize multiple draft responses, referred to as proposals, into a single, refined answer, termed aggregation. At inference time, a propose-and-aggregate strategy further boosts performance by iteratively generating proposals and aggregating them. Empirical evaluations on benchmark datasets show that AFT-trained models substantially outperform standard SFT. Notably, an AFT model, fine-tuned from Llama3.1-8B-Base with only 64k data, achieves a 41.3% LC win rate on AlpacaEval 2, surpassing significantly larger LLMs such as Llama3.1-405B-Instruct and GPT4. By combining sequential refinement and parallel sampling, the propose-and-aggregate framework scales inference-time computation in a flexible manner. Overall, These findings position AFT as a promising approach to unlocking additional capabilities of LLMs without resorting to increasing data volume or model size.

[Arxiv](https://arxiv.org/abs/2501.11877)