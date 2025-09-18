# 提示词真的够用吗？针对软件需求分类评估基于提示词的大型语言模型（LLMs）

发布时间：2025年09月17日

`LLM应用` `工业与制造`

> Are Prompts All You Need? Evaluating Prompt-Based Large Language Models (LLM)s for Software Requirements Classification

# 摘要

> 需求分类是将自然语言需求划分到预定义类别（如功能性和非功能性）的任务。准确分类有助于降低风险、提升软件质量。现有多数模型依赖监督学习，这类方法需要大量标记数据——不仅成本高昂、生成缓慢，还受领域限制；此外，它们泛化能力较弱，往往需为每个任务重新训练。本研究旨在验证基于提示的大型语言模型能否降低数据需求。我们在两个英文数据集（PROMISE和SecReq）的多个任务上，对多种模型及提示风格（零样本、少样本、角色设定和思维链）进行了基准测试。针对每个任务，我们先对比不同的模型提示配置，再将最佳LLM设置与性能强劲的微调Transformer基准模型进行比较。结果显示，基于提示的LLM（尤其是采用少样本提示时）性能可达到甚至超越基准模型。添加角色设定，或角色设定结合思维链，还能带来进一步提升。我们得出结论：基于提示的LLM是一种实用且可扩展的方案，它能减少对大量标注数据的依赖，并提升跨任务泛化能力。

> Requirements classification assigns natural language requirements to predefined classes, such as functional and non functional. Accurate classification reduces risk and improves software quality. Most existing models rely on supervised learning, which needs large labeled data that are costly, slow to create, and domain dependent; they also generalize poorly and often require retraining for each task. This study tests whether prompt based large language models can reduce data needs. We benchmark several models and prompting styles (zero shot, few shot, persona, and chain of thought) across multiple tasks on two English datasets, PROMISE and SecReq. For each task we compare model prompt configurations and then compare the best LLM setups with a strong fine tuned transformer baseline. Results show that prompt based LLMs, especially with few shot prompts, can match or exceed the baseline. Adding a persona, or persona plus chain of thought, can yield further gains. We conclude that prompt based LLMs are a practical and scalable option that reduces dependence on large annotations and can improve generalizability across tasks.

[Arxiv](https://arxiv.org/abs/2509.13868)