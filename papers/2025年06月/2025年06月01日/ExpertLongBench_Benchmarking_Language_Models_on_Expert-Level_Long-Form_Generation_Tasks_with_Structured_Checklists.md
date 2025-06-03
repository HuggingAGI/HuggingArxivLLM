# # ExpertLongBench：专家长文本生成基准测试  
通过结构化清单评估语言模型的专家级长文本生成能力。

发布时间：2025年06月01日

`LLM应用` `基准测试` `评估框架`

> ExpertLongBench: Benchmarking Language Models on Expert-Level Long-Form Generation Tasks with Structured Checklists

# 摘要

> 本文介绍了 ExpertLongBench，这是一个专家级别的基准测试，包含来自 9 个领域的 11 个任务，这些任务反映了现实中的专家工作流程和应用场景。除了问答，ExpertLongBench 中的应用驱动型任务要求生成长文本输出，这些输出可能超过 5,000 个令牌，并且必须严格遵循特定领域的具体要求。值得注意的是，每个任务都配备了由领域专家设计或验证的评估标准，用于明确任务要求并指导输出评估。此外，我们提出了 CLEAR，这是一个支持在我们的基准测试中对长文本模型输出进行准确评估的评估框架。为了实现细致且符合专家标准的评估，CLEAR 从模型输出和参考输出中提取与任务特定评估标准对应的信息，生成检查表。然后将模型输出的检查表项目与参考输出的对应项目进行比较，以评估其正确性，从而实现有依据的评估。我们对 11 个大型语言模型（LLMs）进行了基准测试，并分析了 CLEAR 中的组件，结果表明：（1）现有的 LLMs 在专家级别的任务上需要显著改进，即使表现最好的模型也只有 26.8% 的 F1 分数；（2）模型可以生成与所需方面相对应的内容，尽管通常不够准确；（3）CLEAR 中的准确检查表提取和比较可以通过开放权重模型实现，从而支持更广泛和低成本的使用。

> This paper introduces ExpertLongBench, an expert-level benchmark containing 11 tasks from 9 domains that reflect realistic expert workflows and applications. Beyond question answering, the application-driven tasks in ExpertLongBench demand long-form outputs that can exceed 5,000 tokens and strict adherence to domain-specific requirements. Notably, each task in ExpertLongBench includes a rubric, designed or validated by domain experts, to specify task requirements and guide output evaluation. Furthermore, we propose CLEAR, an evaluation framework that supports accurate evaluation of long-form model outputs in our benchmark. To achieve fine-grained, expert-aligned evaluation, CLEAR derives checklists from both model outputs and references by extracting information corresponding to items in the task-specific rubric. Checklist items for model outputs are then compared with corresponding items for reference outputs to assess their correctness, enabling grounded evaluation. We benchmark 11 large language models (LLMs) and analyze components in CLEAR, showing that (1) existing LLMs, with the top performer achieving only a 26.8% F1 score, require significant improvement for expert-level tasks; (2) models can generate content corresponding to the required aspects, though often not accurately; and (3) accurate checklist extraction and comparison in CLEAR can be achieved by open-weight models for more scalable and low-cost usage.

[Arxiv](https://arxiv.org/abs/2506.01241)