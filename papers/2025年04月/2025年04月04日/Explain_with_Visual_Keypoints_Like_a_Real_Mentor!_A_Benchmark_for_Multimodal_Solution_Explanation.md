# 基于视觉关键点，像真实导师一样解释！一个多模态解决方案解释的基准

发布时间：2025年04月04日

`LLM应用` `视觉解释`

> Explain with Visual Keypoints Like a Real Mentor! A Benchmark for Multimodal Solution Explanation

# 摘要

> 大型语言模型（LLMs）数学推理能力的突飞猛进，推动了AI技术在教育领域的广泛应用，助力学生理解问题解决过程。然而，现有LLM生成的解释中，视觉解释这一关键环节仍待深入探索。现实中，人类导师常借助图表、标记等视觉工具来提升概念理解。针对这一空白，我们推出视觉解决方案解释任务，要求模型不仅解答问题，还需生成包含关键视觉元素的解释（如辅助线、标注等）。为评估模型表现，我们构建了多模态基准数据集MathExplain，涵盖997道数学题，每题均标注视觉关键点并附带相关解释文本。实验结果显示，部分闭源模型在视觉解释任务中表现优异，但现有开源通用模型表现不一，尤其在识别视觉组件和生成连贯解释方面存在不足。我们相信，视觉解决方案解释与MathExplain数据集将助力多模态LLMs在教育领域的研究与应用，促使其成为以解释为导向的有效AI导师。代码与数据将公开发布。

> With the rapid advancement of mathematical reasoning capabilities in large language models (LLMs), AI systems are increasingly being adopted in educational settings to support students' comprehension of problem-solving processes. However, a critical component remains underexplored in current LLM-generated explanations: visual explanation. In real-world instructional contexts, human tutors routinely employ visual aids-such as diagrams, markings, and highlights-to enhance conceptual clarity. To bridge this gap, we introduce a novel task of visual solution explanation, which requires not only solving problems but also generating explanations that incorporate newly introduced visual elements essential for understanding (e.g., auxiliary lines, annotations, or geometric constructions). To evaluate model performance on this task, we propose MathExplain, a multimodal benchmark consisting of 997 math problems annotated with visual keypoints and corresponding explanatory text that references those elements. Our empirical results show that while some closed-source models demonstrate promising capabilities on visual solution-explaining, current open-source general-purpose models perform inconsistently, particularly in identifying relevant visual components and producing coherent keypoint-based explanations. We expect that visual solution-explaining and the MathExplain dataset will catalyze further research on multimodal LLMs in education and advance their deployment as effective, explanation-oriented AI tutors. Code and data will be released publicly.

[Arxiv](https://arxiv.org/abs/2504.03197)