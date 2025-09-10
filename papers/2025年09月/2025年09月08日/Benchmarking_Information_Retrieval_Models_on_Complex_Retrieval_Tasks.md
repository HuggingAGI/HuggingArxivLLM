# # 信息检索模型在复杂检索任务上的基准测试

发布时间：2025年09月08日

`其他` `基础理论`

> Benchmarking Information Retrieval Models on Complex Retrieval Tasks

# 摘要

> 大型语言模型（LLMs）堪称基于文本任务的万能神器，催生出无数曾难以想象的应用。然而检索模型领域，却迟迟未出现同等强大的通用模型。要实现这一点，检索模型需能处理复杂检索任务——这类任务的查询往往包含自然语言描述的多部分信息、约束条件或具体要求。这些任务是现有主流评估集中简单单维度查询的自然进阶。随着人们对搜索系统的期望提升——希望它能处理更具体、更具挑战性的信息需求（这一点从LLM信息系统的使用方式中可见一斑），复杂查询便应运而生。尽管学界迫切希望检索模型能提升复杂任务处理能力，但目前评估其在各类复杂任务中综合表现的资源却十分匮乏。仅有的少数资源不仅覆盖范围窄，还常常脱离真实场景，导致我们难以摸清检索模型在复杂现实任务中的真实水平。为填补这一空白、推动下一代检索模型创新，我们构建了多样化的真实复杂检索任务集，并对主流先进检索模型进行了基准测评。此外，我们还探究了基于LLM的查询扩展与重写技术对检索质量的影响。实验结果显示，即便是最顶尖的模型也难以输出高质量检索结果——所有任务的最高平均nDCG@10仅0.346，R@100也仅0.587。值得注意的是，虽然LLM增强能提升弱模型性能，但最强模型在所有重写技术下的各项指标反而均出现下降。

> Large language models (LLMs) are incredible and versatile tools for text-based tasks that have enabled countless, previously unimaginable, applications. Retrieval models, in contrast, have not yet seen such capable general-purpose models emerge. To achieve this goal, retrieval models must be able to perform complex retrieval tasks, where queries contain multiple parts, constraints, or requirements in natural language. These tasks represent a natural progression from the simple, single-aspect queries that are used in the vast majority of existing, commonly used evaluation sets. Complex queries naturally arise as people expect search systems to handle more specific and often ambitious information requests, as is demonstrated by how people use LLM-based information systems. Despite the growing desire for retrieval models to expand their capabilities in complex retrieval tasks, there exist limited resources to assess the ability of retrieval models on a comprehensive set of diverse complex tasks. The few resources that do exist feature a limited scope and often lack realistic settings making it hard to know the true capabilities of retrieval models on complex real-world retrieval tasks. To address this shortcoming and spur innovation in next-generation retrieval models, we construct a diverse and realistic set of complex retrieval tasks and benchmark a representative set of state-of-the-art retrieval models. Additionally, we explore the impact of LLM-based query expansion and rewriting on retrieval quality. Our results show that even the best models struggle to produce high-quality retrieval results with the highest average nDCG@10 of only 0.346 and R@100 of only 0.587 across all tasks. Although LLM augmentation can help weaker models, the strongest model has decreased performance across all metrics with all rewriting techniques.

[Arxiv](https://arxiv.org/abs/2509.07253)