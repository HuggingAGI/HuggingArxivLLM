# # 超树规划：通过层次化思维增强LLM推理能力

发布时间：2025年05月04日

`LLM应用` `人工智能`

> HyperTree Planning: Enhancing LLM Reasoning via Hierarchical Thinking

# 摘要

> 近期研究显著提升了大型语言模型（LLMs）在复杂推理任务中的表现，尤其在数学和逻辑推理领域取得了突破性进展。然而，这些方法在处理复杂规划任务时面临挑战，主要源于冗长的推理步骤、多样的约束条件以及对多个不同子任务的处理需求。为解决这一问题，我们提出了超树规划（HTP），一种全新的推理范式，通过构建超树结构的规划大纲实现高效规划。超树结构使LLMs能够灵活运用分而治之的策略，进行层次化思考，从而有效分解复杂推理步骤，适应多样约束，并以井然有序的方式管理多个子任务。我们进一步提出了一种自主规划框架，通过迭代优化和扩展超树结构的规划大纲完成整个规划过程。实验结果表明，HTP方法表现优异，在TravelPlanner基准测试中，使用Gemini-1.5-Pro实现了相较于o1-preview 3.6倍的性能提升，达到了目前最优的准确率水平。

> Recent advancements have significantly enhanced the performance of large language models (LLMs) in tackling complex reasoning tasks, achieving notable success in domains like mathematical and logical reasoning. However, these methods encounter challenges with complex planning tasks, primarily due to extended reasoning steps, diverse constraints, and the challenge of handling multiple distinct sub-tasks. To address these challenges, we propose HyperTree Planning (HTP), a novel reasoning paradigm that constructs hypertree-structured planning outlines for effective planning. The hypertree structure enables LLMs to engage in hierarchical thinking by flexibly employing the divide-and-conquer strategy, effectively breaking down intricate reasoning steps, accommodating diverse constraints, and managing multiple distinct sub-tasks in a well-organized manner. We further introduce an autonomous planning framework that completes the planning process by iteratively refining and expanding the hypertree-structured planning outlines. Experiments demonstrate the effectiveness of HTP, achieving state-of-the-art accuracy on the TravelPlanner benchmark with Gemini-1.5-Pro, resulting in a 3.6 times performance improvement over o1-preview.

[Arxiv](https://arxiv.org/abs/2505.02322)