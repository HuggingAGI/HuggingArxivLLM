# # 视觉-语言模型规划及其在机器人辅助教学中的应用

发布时间：2025年01月29日

`LLM应用

理由：该论文主要探讨了如何利用大型语言模型（LLM）和视觉语言模型（VLM）来自动生成规划领域定义语言（PDDL），并将其应用于AI规划领域。这属于LLM在实际应用中的使用，特别是在自动化生成结构化问题实例和解决复杂现实任务方面。因此，将其分类为“LLM应用”是合适的。` `AI规划` `机器人辅助教学`

> Planning with Vision-Language Models and a Use Case in Robot-Assisted Teaching

# 摘要

> # 摘要
利用大型语言模型（LLM）自动化生成规划领域定义语言（PDDL），为AI规划领域开辟了新的研究方向，尤其是在处理复杂现实任务时。本文提出Image2PDDL框架，通过视觉语言模型（VLM）将初始状态图像和目标状态描述自动转化为PDDL问题。该框架结合PDDL领域与视觉输入，解决了感知理解与符号规划之间的关键挑战，降低了创建结构化问题实例的门槛，并提升了跨复杂任务的可扩展性。我们在多个领域（如积木世界、滑动拼图等）和不同难度数据集上评估了该框架，重点关注语法正确性（确保语法与可执行性）和内容正确性（验证生成PDDL问题中的状态表示准确性）。实验结果表明，该方法在不同复杂度的任务中表现优异，展现了其在AI规划中的广泛应用潜力。最后，我们还将探讨其在机器人辅助自闭症谱系障碍学生教学中的潜在应用。

> Automating the generation of Planning Domain Definition Language (PDDL) with Large Language Model (LLM) opens new research topic in AI planning, particularly for complex real-world tasks. This paper introduces Image2PDDL, a novel framework that leverages Vision-Language Models (VLMs) to automatically convert images of initial states and descriptions of goal states into PDDL problems. By providing a PDDL domain alongside visual inputs, Imasge2PDDL addresses key challenges in bridging perceptual understanding with symbolic planning, reducing the expertise required to create structured problem instances, and improving scalability across tasks of varying complexity. We evaluate the framework on various domains, including standard planning domains like blocksworld and sliding tile puzzles, using datasets with multiple difficulty levels. Performance is assessed on syntax correctness, ensuring grammar and executability, and content correctness, verifying accurate state representation in generated PDDL problems. The proposed approach demonstrates promising results across diverse task complexities, suggesting its potential for broader applications in AI planning. We will discuss a potential use case in robot-assisted teaching of students with Autism Spectrum Disorder.

[Arxiv](https://arxiv.org/abs/2501.17665)