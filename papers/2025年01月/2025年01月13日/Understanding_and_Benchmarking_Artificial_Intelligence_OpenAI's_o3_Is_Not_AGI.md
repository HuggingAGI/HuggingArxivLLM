# 理解与基准测试人工智能：OpenAI的o3并非通用人工智能

发布时间：2025年01月13日

`LLM理论

**理由**：这篇论文主要讨论了基于大型语言模型（LLMs）的系统（如 OpenAI 的 o3）在 ARC-AGI 基准测试中的表现，并探讨了这些系统是否展现了智能以及是否朝着人工通用智能（AGI）迈进。论文还提出了一个新的智能基准测试，旨在更全面地评估智能水平和 AGI 的进展。这些内容主要涉及对 LLM 的理论探讨和智能评估，因此归类为 **LLM理论**。` `人工智能` `智能评估`

> Understanding and Benchmarking Artificial Intelligence: OpenAI's o3 Is Not AGI

# 摘要

> OpenAI 的 o3 在 ARC-AGI 基准测试中斩获 87.5% 的高分，该测试旨在衡量智能水平。这不禁让人思考：基于大型语言模型（LLMs）的系统，尤其是 o3，是否展现了智能，并朝着人工通用智能（AGI）迈进？ARC-AGI 的创始人 François Chollet 曾区分技能与智能，并提出了新的智能定义：智能体越智能，越能在多样化的世界中高效实现多样化的目标，且所需知识越少。分析 ARC-AGI 基准测试发现，其任务属于特定类型，可通过大量试验预定义操作的组合来解决。o3 正是采用这种方法，凭借强大的计算能力取得了高分。然而，物理世界和人类领域中的大多数问题无法提前测试，也没有预定义的操作可用。因此，像 o3 那样大量试验预定义操作并不能作为 AGI 的基础——我们需要新的方法，能够在不依赖现有技能的情况下，可靠解决各种问题。为此，我们提出了一个新的智能基准测试，涵盖更多样化的未知任务，从而全面评估智能水平及 AGI 的进展。

> OpenAI's o3 achieves a high score of 87.5 % on ARC-AGI, a benchmark proposed to measure intelligence. This raises the question whether systems based on Large Language Models (LLMs), particularly o3, demonstrate intelligence and progress towards artificial general intelligence (AGI). Building on the distinction between skills and intelligence made by François Chollet, the creator of ARC-AGI, a new understanding of intelligence is introduced: an agent is the more intelligent, the more efficiently it can achieve the more diverse goals in the more diverse worlds with the less knowledge. An analysis of the ARC-AGI benchmark shows that its tasks represent a very specific type of problem that can be solved by massive trialling of combinations of predefined operations. This method is also applied by o3, achieving its high score through the extensive use of computing power. However, for most problems in the physical world and in the human domain, solutions cannot be tested in advance and predefined operations are not available. Consequently, massive trialling of predefined operations, as o3 does, cannot be a basis for AGI - instead, new approaches are required that can reliably solve a wide variety of problems without existing skills. To support this development, a new benchmark for intelligence is outlined that covers a much higher diversity of unknown tasks to be solved, thus enabling a comprehensive assessment of intelligence and of progress towards AGI.

[Arxiv](https://arxiv.org/abs/2501.07458)