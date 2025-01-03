# 大型语言模型的动态技能适配

发布时间：2024年12月26日

`LLM应用

理由：这篇论文主要讨论了如何通过动态技能适应（DSA）框架将新颖且复杂的技能适配到大型语言模型（LLMs）中。论文的核心内容涉及如何利用LLMs生成训练数据、动态调整数据以及通过实验验证该方法在数学推理和社会研究技能上的效果。这些内容都属于LLM在实际应用中的改进和优化，因此应归类为LLM应用。` `人工智能`

> Dynamic Skill Adaptation for Large Language Models

# 摘要

> 我们提出了动态技能适应（DSA），这是一个自适应且动态的框架，旨在将新颖且复杂的技能适配到大型语言模型（LLMs）中。与以往从人类整理的静态数据中随机学习的方法不同，我们首先通过模拟人类的学习路径自动生成并组织训练数据，随后根据训练动态动态调整数据。具体来说，受人类教育系统中学习结构和教学策略的启发，我们通过将复杂技能分解为子技能，并根据它们在人类学习中的依赖关系排列，构建了一个技能图。对于每个技能，我们利用LLMs生成两类数据：一类是类似教科书的详细描述数据，用于预训练；另一类是类似练习的数据，旨在通过明确使用技能解决问题来进行指令调优。此外，在指令调优过程中，我们动态更新训练数据，降低简单例子的权重，生成更复杂的例子，并过滤掉错误数据。在LLAMA和Mistral等大型语言模型上的实验表明，我们提出的方法在适应数学推理技能和社会研究技能方面具有显著效果。

> We present Dynamic Skill Adaptation (DSA), an adaptive and dynamic framework to adapt novel and complex skills to Large Language Models (LLMs). Compared with previous work which learns from human-curated and static data in random orders, we propose to first automatically generate and organize the training data by mimicking the learning pathways of human and then dynamically tailor the training data based on the training dynamics. Specifically, inspired by the learning structures and teaching strategies in the human education system, we first construct a skill graph by decomposing complex skills into sub-skills and arranging them based on their dependencies in human syllables. For every skill, we utilize LLMs to generate both textbook-like data which contains detailed descriptions of skills for pre-training and exercise-like data which targets at explicitly utilizing the skills to solve problems for instruction-tuning. Furthermore, during the instruction-tuning, we dynamically update the training data which down-weight easy-to-learn examples, generate more complex examples, and filter out data with errors. Experiments on large language models such as LLAMA and Mistral demonstrate the effectiveness of our proposed methods in adapting math reasoning skills and social study skills.

[Arxiv](https://arxiv.org/abs/2412.19361)