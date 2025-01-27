# VERUS-LM：一个融合大型语言模型与符号推理的通用框架

发布时间：2025年01月24日

`Agent

理由：这篇论文提出了VERUS-LM框架，该框架结合了大型语言模型（LLMs）和符号求解器的优势，旨在解决复杂的推理任务。VERUS-LM通过通用提示机制、明确分离领域知识与查询、支持多种逻辑推理任务等方式，提升了适应性并降低了计算成本。这些特点表明VERUS-LM是一个智能代理（Agent），能够自主执行复杂的推理任务，并在不同领域中表现出色。因此，这篇论文应归类为Agent。` `人工智能` `逻辑推理`

> VERUS-LM: a Versatile Framework for Combining LLMs with Symbolic Reasoning

# 摘要

> 最近，一种新的神经符号推理方法通过结合大型语言模型（LLMs）和符号求解器的优势，来解决复杂的推理任务。然而，现有方法存在明显不足：任务特定提示导致泛化能力差，知识和查询未分离导致效率低下，推理能力受限。这些问题限制了其在不同领域的扩展和应用。本文提出VERUS-LM框架，旨在解决这些挑战。VERUS-LM采用通用提示机制，明确分离领域知识与查询，支持多种逻辑推理任务，如优化和约束满足。该框架提升了适应性，降低了计算成本，并支持更丰富的推理形式。我们在新数据集上验证了该方法的多样化推理能力，显著优于LLMs。此外，VERUS-LM在常见推理基准测试中表现优异，尤其在困难的AR-LSAT数据集上远超其他先进方法。VERUS-LM的推出，标志着神经符号AI系统向更通用化迈出了重要一步。

> A recent approach to neurosymbolic reasoning is to explicitly combine the strengths of large language models (LLMs) and symbolic solvers to tackle complex reasoning tasks. However, current approaches face significant limitations, including poor generalizability due to task-specific prompts, inefficiencies caused by the lack of separation between knowledge and queries, and restricted inferential capabilities. These shortcomings hinder their scalability and applicability across diverse domains. In this paper, we introduce VERUS-LM, a novel framework designed to address these challenges. VERUS-LM employs a generic prompting mechanism, clearly separates domain knowledge from queries, and supports a wide range of different logical reasoning tasks. This framework enhances adaptability, reduces computational cost, and allows for richer forms of reasoning, such as optimization and constraint satisfaction. We show that our approach succeeds in diverse reasoning on a novel dataset, markedly outperforming LLMs. Additionally, our system achieves competitive results on common reasoning benchmarks when compared to other state-of-the-art approaches, and significantly surpasses them on the difficult AR-LSAT dataset. By pushing the boundaries of hybrid reasoning, VERUS-LM represents a significant step towards more versatile neurosymbolic AI systems

[Arxiv](https://arxiv.org/abs/2501.14540)