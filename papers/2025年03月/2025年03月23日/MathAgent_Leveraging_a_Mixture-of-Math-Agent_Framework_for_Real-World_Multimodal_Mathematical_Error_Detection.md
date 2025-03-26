# MathAgent：基于混合数学代理框架的现实世界多模态数学错误检测

发布时间：2025年03月23日

`Agent

理由：这篇论文提出了一个名为MathAgent的混合数学智能体框架，用于教育环境中的数学错误检测。该框架由三个专门的智能体组成，分别负责不同的任务，如图像-文本一致性验证、视觉语义解释和综合错误分析。因此，这篇论文主要涉及智能体的设计与应用，属于Agent类别。`

> MathAgent: Leveraging a Mixture-of-Math-Agent Framework for Real-World Multimodal Mathematical Error Detection

# 摘要

> 教育环境中的数学错误检测对多模态大型语言模型（MLLMs）是一项重要挑战，不仅需要模型深入理解视觉与文本数学内容，还需具备复杂推理能力。尽管MLLMs在数学问题解决上表现出色，但在多模态数学场景下识别和分类学生错误仍具难度。因此，我们提出MathAgent——一个专为应对这些挑战而设计的新型混合数学智能体框架。我们的方法将错误检测分为三个阶段，分别由三个专业智能体负责：图像-文本一致性验证器、视觉语义解释器和综合错误分析器。这种架构通过明确建模多模态问题与学生解题步骤间的关系，显著提升了数学内容处理的准确性。实验结果表明，在真实教育数据上，MathAgent的错误步骤识别准确率较基线模型提升了约5%，错误分类准确率提高了3%。此外，MathAgent已成功应用于一个教育平台，服务超过一百万K-12学生，实现了近90%的学生满意度，并通过减少人工检测显著降低了成本。

> Mathematical error detection in educational settings presents a significant challenge for Multimodal Large Language Models (MLLMs), requiring a sophisticated understanding of both visual and textual mathematical content along with complex reasoning capabilities. Though effective in mathematical problem-solving, MLLMs often struggle with the nuanced task of identifying and categorizing student errors in multimodal mathematical contexts. Therefore, we introduce MathAgent, a novel Mixture-of-Math-Agent framework designed specifically to address these challenges. Our approach decomposes error detection into three phases, each handled by a specialized agent: an image-text consistency validator, a visual semantic interpreter, and an integrative error analyzer. This architecture enables more accurate processing of mathematical content by explicitly modeling relationships between multimodal problems and student solution steps. We evaluate MathAgent on real-world educational data, demonstrating approximately 5% higher accuracy in error step identification and 3% improvement in error categorization compared to baseline models. Besides, MathAgent has been successfully deployed in an educational platform that has served over one million K-12 students, achieving nearly 90% student satisfaction while generating significant cost savings by reducing manual error detection.

[Arxiv](https://arxiv.org/abs/2503.18132)