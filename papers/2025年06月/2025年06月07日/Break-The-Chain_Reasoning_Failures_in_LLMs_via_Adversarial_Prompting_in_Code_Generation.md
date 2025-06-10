# 打破链式推理：揭示LLM在代码生成中的推理失败——通过对抗性提示方法

发布时间：2025年06月07日

`LLM理论` `代码生成` `推理任务`

> Break-The-Chain: Reasoning Failures in LLMs via Adversarial Prompting in Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成、数学问题解决和算法合成等需要复杂推理的任务中表现突出，尤其是在借助推理标记和链式思维提示时。然而，一个关键问题仍然存在：这些模型是否真的在推理，还是仅仅依赖浅层统计模式？本研究通过引入一组语义忠实但具有对抗性结构的提示扰动，系统地考察了推理型LLMs的稳健性。我们的评估涵盖了从LeetCode风格问题衍生出的700种被扰动的代码生成，采用了叙事重构、无关约束注入、示例重新排序和数值扰动等变换。结果显示，某些修改导致性能大幅下降（准确率下降高达-42.1%），而其他修改却意外地将模型准确率提高了高达35.3%，表明模型不仅对语义敏感，还对表面级提示动态敏感。这些发现揭示了当前推理系统的脆弱性和不可预测性，凸显了开发更基于原则的推理对齐和提示稳健性方法的必要性。我们公开了我们的扰动数据集和评估框架，以推动对可信和健壮LLM推理的进一步研究。

> Large Language Models (LLMs) have achieved remarkable success in tasks requiring complex reasoning, such as code generation, mathematical problem solving, and algorithmic synthesis -- especially when aided by reasoning tokens and Chain-of-Thought prompting. Yet, a core question remains: do these models truly reason, or do they merely exploit shallow statistical patterns? In this paper, we systematically investigate the robustness of reasoning LLMs by introducing a suite of semantically faithful yet adversarially structured prompt perturbations. Our evaluation -- spanning 700 perturbed code generations derived from LeetCode-style problems -- applies transformations such as storytelling reframing, irrelevant constraint injection, example reordering, and numeric perturbation. We observe that while certain modifications severely degrade performance (with accuracy drops up to -42.1%), others surprisingly improve model accuracy by up to 35.3%, suggesting sensitivity not only to semantics but also to surface-level prompt dynamics. These findings expose the fragility and unpredictability of current reasoning systems, underscoring the need for more principles approaches to reasoning alignments and prompting robustness. We release our perturbation datasets and evaluation framework to promote further research in trustworthy and resilient LLM reasoning.

[Arxiv](https://arxiv.org/abs/2506.06971)