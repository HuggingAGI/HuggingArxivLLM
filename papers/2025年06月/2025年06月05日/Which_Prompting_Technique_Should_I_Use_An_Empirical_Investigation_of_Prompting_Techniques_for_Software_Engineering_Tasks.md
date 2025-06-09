# # 哪种提示工程技术更适合？软件工程任务中提示工程技术的实证研究

发布时间：2025年06月05日

`LLM应用` `软件工程`

> Which Prompting Technique Should I Use? An Empirical Investigation of Prompting Techniques for Software Engineering Tasks

# 摘要

> 针对大型语言模型（LLMs），研究者提出了多种多样的提示工程（prompt engineering）技术，但这些技术在具体软件工程（SE）任务上的系统性评估仍处于探索阶段。本研究采用四种LLM模型，对14种已建立的提示技术在10个软件工程任务上进行了全面评估。根据先前文献，所选提示技术涵盖了零样本、少样本、思维生成、集成、自我批评和分解六大核心维度。这些技术在代码生成、缺陷修复、面向代码的问题回答等任务上接受了考验。研究结果显示，对于需要复杂逻辑和深入推理的软件工程任务，某些提示技术表现尤为突出；而对于更多依赖上下文理解和示例驱动场景的任务，其他技术则更具优势。此外，我们深入分析了提示的语义特征与影响提示技术在提升软件工程任务性能方面有效性的因素之间的关联。同时，我们报告了每种提示技术在特定任务和模型上的时间与代币消耗情况，为 practitioners 选择最适合其应用场景的提示技术提供了实用指导。

> A growing variety of prompt engineering techniques has been proposed for Large Language Models (LLMs), yet systematic evaluation of each technique on individual software engineering (SE) tasks remains underexplored. In this study, we present a systematic evaluation of 14 established prompt techniques across 10 SE tasks using four LLM models. As identified in the prior literature, the selected prompting techniques span six core dimensions (Zero-Shot, Few-Shot, Thought Generation, Ensembling, Self-Criticism, and Decomposition). They are evaluated on tasks such as code generation, bug fixing, and code-oriented question answering, to name a few. Our results show which prompting techniques are most effective for SE tasks requiring complex logic and intensive reasoning versus those that rely more on contextual understanding and example-driven scenarios. We also analyze correlations between the linguistic characteristics of prompts and the factors that contribute to the effectiveness of prompting techniques in enhancing performance on SE tasks. Additionally, we report the time and token consumption for each prompting technique when applied to a specific task and model, offering guidance for practitioners in selecting the optimal prompting technique for their use cases.

[Arxiv](https://arxiv.org/abs/2506.05614)