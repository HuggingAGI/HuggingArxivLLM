# 针对代码的大型语言模型的对抗攻击分类与鲁棒性测试

发布时间：2025年06月09日

`LLM应用` `软件工程` `代码生成`

> Adversarial Attack Classification and Robustness Testing for Large Language Models for Code

# 摘要

> # 摘要
大型语言模型 (LLMs) 在代码生成、补全和分析等软件开发任务中发挥着越来越重要的作用。随着 LLMs 深度融入工作流，确保其在面对多样化或对抗性输入时的鲁棒性变得至关重要。这些漏洞可能在模型遇到扰动的任务描述、代码或注释时导致错误或不安全的代码生成。然而，先前的研究往往忽视了自然语言在指导代码任务中的作用。

本研究深入探讨了自然语言输入中的对抗性扰动（包括提示、注释和描述）对代码领域的大型语言模型 (LLM4Code) 的影响。通过分析字符、单词和句子级别的扰动，我们识别出最具影响力的漏洞。我们研究了多个项目（例如 ReCode、OpenAttack）和数据集（例如 HumanEval、MBPP），并建立了一个对抗性攻击分类框架。该框架从两个维度进行分类：第一个维度根据输入类型（代码、提示或注释）进行分类，第二个维度则关注粒度级别（字符、单词或句子级别的变化）。

我们采用了一种混合研究方法，结合定量性能指标和定性漏洞分析。研究发现，LLM4Code 模型在不同类型的扰动下表现出不同的鲁棒性。具体而言，句子级别的攻击效果最弱，表明模型对更广泛的上下文变化具有较强的抵抗力。相比之下，单词级别的扰动带来了严重挑战，揭示了语义层面的漏洞。字符级别的影响则因情况而异，显示出模型对细微句法偏差的敏感性。

本研究为测试 LLM4Code 的鲁棒性提供了一个结构化的框架，并强调了自然语言在对抗性评估中的关键作用。为了实现安全可靠的代码生成系统，提升模型在语义级别干扰中的抗性至关重要。

> Large Language Models (LLMs) have become vital tools in software development tasks such as code generation, completion, and analysis. As their integration into workflows deepens, ensuring robustness against vulnerabilities especially those triggered by diverse or adversarial inputs becomes increasingly important. Such vulnerabilities may lead to incorrect or insecure code generation when models encounter perturbed task descriptions, code, or comments. Prior research often overlooks the role of natural language in guiding code tasks. This study investigates how adversarial perturbations in natural language inputs including prompts, comments, and descriptions affect LLMs for Code (LLM4Code). It examines the effects of perturbations at the character, word, and sentence levels to identify the most impactful vulnerabilities. We analyzed multiple projects (e.g., ReCode, OpenAttack) and datasets (e.g., HumanEval, MBPP), establishing a taxonomy of adversarial attacks. The first dimension classifies the input type code, prompts, or comments while the second dimension focuses on granularity: character, word, or sentence-level changes. We adopted a mixed-methods approach, combining quantitative performance metrics with qualitative vulnerability analysis. LLM4Code models show varying robustness across perturbation types. Sentence-level attacks were least effective, suggesting models are resilient to broader contextual changes. In contrast, word-level perturbations posed serious challenges, exposing semantic vulnerabilities. Character-level effects varied, showing model sensitivity to subtle syntactic deviations.Our study offers a structured framework for testing LLM4Code robustness and emphasizes the critical role of natural language in adversarial evaluation. Improving model resilience to semantic-level disruptions is essential for secure and reliable code-generation systems.

[Arxiv](https://arxiv.org/abs/2506.07942)