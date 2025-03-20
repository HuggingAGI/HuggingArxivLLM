# MAMM-Refine：一种通过多智能体协作提升生成忠实度的方案

发布时间：2025年03月19日

`Agent` `问答系统`

> MAMM-Refine: A Recipe for Improving Faithfulness in Generation with Multi-Agent Collaboration

# 摘要

> 模型间的多智能体协作在推理任务中展现出潜力，但在长文本生成任务（如摘要和问答）中的探索尚不充分。我们扩展了多智能体多模型推理在生成任务中的应用，特别是通过改进忠实度来优化生成内容，即通过修正模型生成的输出以消除事实上的不一致。我们研究了多个实例和类型的大型语言模型（LLMs）之间的迭代协作如何提升修正过程中子任务的表现，例如错误检测、批评论不符事实的句子以及根据批评为基础进行修改。我们为每个子任务设计了内在的评估方法，研究结果表明，多智能体（多个实例）和多模型（多样化LLM类型）的方法均有助于错误检测和批评论。此外，将批评论和修正重新定义为重排序任务而非生成任务，可以提升多智能体的表现。我们将这些见解整合成一个最终的“配方”，称为多智能体多模型修正（Multi-Agent Multi-Model Refinement, MAMM-Refine），其中多智能体和多模型的协作在三个摘要数据集以及长文本问答任务上显著提升了性能，证明了我们方法的有效性和通用性。

> Multi-agent collaboration among models has shown promise in reasoning tasks but is underexplored in long-form generation tasks like summarization and question-answering. We extend multi-agent multi-model reasoning to generation, specifically to improving faithfulness through refinement, i.e., revising model-generated outputs to remove factual inconsistencies. We investigate how iterative collaboration among multiple instances and types of large language models (LLMs) enhances subtasks in the refinement process, such as error detection, critiquing unfaithful sentences, and making corrections based on critiques. We design intrinsic evaluations for each subtask, with our findings indicating that both multi-agent (multiple instances) and multi-model (diverse LLM types) approaches benefit error detection and critiquing. Additionally, reframing critiquing and refinement as reranking rather than generation tasks improves multi-agent performance. We consolidate these insights into a final "recipe" called Multi-Agent Multi-Model Refinement (MAMM-Refine), where multi-agent and multi-model collaboration significantly boosts performance on three summarization datasets as well as on long-form question answering, demonstrating the effectiveness and generalizability of our recipe.

[Arxiv](https://arxiv.org/abs/2503.15272)