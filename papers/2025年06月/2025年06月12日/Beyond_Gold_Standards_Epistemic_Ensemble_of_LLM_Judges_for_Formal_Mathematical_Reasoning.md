# 超越黄金标准：用于形式数学推理的 LLM 评估者知识集成

发布时间：2025年06月12日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLM）应用于自动形式化任务的评估方法。它提出了一种基于LLM的评估框架，用于评估自然语言到正式语言的转换质量。虽然论文涉及LLM的应用，但它更多地关注于如何利用LLM进行评估，而不是LLM本身的理论或架构。因此，它更适合归类为LLM应用。` `数学推理` `自动形式化`

> Beyond Gold Standards: Epistemic Ensemble of LLM Judges for Formal Mathematical Reasoning

# 摘要

> 自动形式化在正式数学推理中扮演着关键角色，它能够将自然语言陈述自动转换为正式语言。尽管基于大型语言模型（LLM）的最新进展已取得令人鼓舞的成果，但用于自动评估自动形式化的有效方法仍然未得到充分探索。当转向更复杂的领域（例如高级数学）时，人工评估不仅需要大量时间，还需要深厚的专业知识，尤其是在陈述和背景知识复杂度增加的情况下。将LLM作为评估工具为这种评估的自动化提供了一个有前景的解决方案。然而，现有方法通常采用粗粒度且通用的评估标准，这在处理复杂正式数学推理时效果有限，因为这类推理的质量依赖于细致且多粒度的维度。针对这一研究空白，本研究提出了一种系统化的自动方法，用于评估自动形式化任务。该方法基于一个知识和形式上双重严谨的LLM评估小组（EFG），其评估标准涵盖了逻辑保真（LP）、数学一致性（MC）、形式有效性（FV）和形式质量（FQ），从而实现了一个透明且全面的评估体系。我们通过实验验证了该框架在正式数学领域内作为自动形式化评估代理的可行性。总体而言，实验结果表明，基于LLM的EFG评估小组相较于传统的粗粒度模型，与人工评估的相关性更强，特别是在评估形式质量方面。这些发现表明，当LLM作为评估工具时，若能以一套明确的原子属性为指导，将能够为正式数学推理的评估提供一个可扩展、可解释且可靠的解决方案。

> Autoformalization plays a crucial role in formal mathematical reasoning by enabling the automatic translation of natural language statements into formal languages. While recent advances using large language models (LLMs) have shown promising results, methods for automatically evaluating autoformalization remain underexplored. As one moves to more complex domains (e.g., advanced mathematics), human evaluation requires significant time and domain expertise, especially as the complexity of the underlying statements and background knowledge increases. LLM-as-a-judge presents a promising approach for automating such evaluation. However, existing methods typically employ coarse-grained and generic evaluation criteria, which limit their effectiveness for advanced formal mathematical reasoning, where quality hinges on nuanced, multi-granular dimensions. In this work, we take a step toward addressing this gap by introducing a systematic, automatic method to evaluate autoformalization tasks. The proposed method is based on an epistemically and formally grounded ensemble (EFG) of LLM judges, defined on criteria encompassing logical preservation (LP), mathematical consistency (MC), formal validity (FV), and formal quality (FQ), resulting in a transparent assessment that accounts for different contributing factors. We validate the proposed framework to serve as a proxy for autoformalization assessment within the domain of formal mathematics. Overall, our experiments demonstrate that the EFG ensemble of LLM judges is a suitable emerging proxy for evaluation, more strongly correlating with human assessments than a coarse-grained model, especially when assessing formal qualities. These findings suggest that LLM-as-judges, especially when guided by a well-defined set of atomic properties, could offer a scalable, interpretable, and reliable support for evaluating formal mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2506.10903)