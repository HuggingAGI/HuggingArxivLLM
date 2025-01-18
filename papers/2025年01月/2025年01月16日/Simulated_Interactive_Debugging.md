# 模拟交互式调试

发布时间：2025年01月16日

`LLM应用

理由：这篇论文描述了一种结合传统故障定位技术和大型语言模型（LLM）的原型系统，用于帮助学生进行软件调试。该系统利用LLM的交互式聊天机器人功能，提供自动断点设置和解释等功能，旨在提升学生的调试能力。因此，这篇论文主要涉及LLM在实际应用中的使用，属于LLM应用类别。` `软件工程`

> Simulated Interactive Debugging

# 摘要

> # 摘要
调试软件，即定位并修复故障，是软件工程的核心任务之一。因此，掌握高效调试技能对软件工程师至关重要。然而，调试技术的教学往往有限，通常仅在软件项目中以间接方式传授。这导致大多数计算机科学（CS）学生只能以零散且无系统的方式学习调试。为此，我们提出了一种名为“模拟交互式调试”的方法，通过交互式指导帮助学生完成调试过程，旨在提升他们的修复能力并提供良好的学习体验。我们期望这种引导式调试技术能尽早融入CS教育中的编程课程。为初步验证，我们结合传统故障定位技术和大型语言模型开发了一个原型，学生可使用自动断点设置和交互式聊天机器人等功能。我们设计并执行了一项对照实验，实验对象为八名本科CS学生，结果表明参与者对系统化指导反馈积极，尤其认为自动断点设置最为有效，其次是交互式调试和聊天功能，以及断点设置的解释。未来，我们将进一步完善概念和实现，增加新功能，并进行更深入的用户研究。

> Debugging software, i.e., the localization of faults and their repair, is a main activity in software engineering. Therefore, effective and efficient debugging is one of the core skills a software engineer must develop. However, the teaching of debugging techniques is usually very limited or only taught in indirect ways, e.g., during software projects. As a result, most Computer Science (CS) students learn debugging only in an ad-hoc and unstructured way. In this work, we present our approach called Simulated Interactive Debugging that interactively guides students along the debugging process. The guidance aims to empower the students to repair their solutions and have a proper "learning" experience. We envision that such guided debugging techniques can be integrated into programming courses early in the CS education curriculum. To perform an initial evaluation, we developed a prototypical implementation using traditional fault localization techniques and large language models. Students can use features like the automated setting of breakpoints or an interactive chatbot. We designed and executed a controlled experiment that included this IDE-integrated tooling with eight undergraduate CS students. Based on the responses, we conclude that the participants liked the systematic guidance by the assisted debugger. In particular, they rated the automated setting of breakpoints as the most effective, followed by the interactive debugging and chatting, and the explanations for how breakpoints were set. In our future work, we will improve our concept and implementation, add new features, and perform more intensive user studies.

[Arxiv](https://arxiv.org/abs/2501.09694)