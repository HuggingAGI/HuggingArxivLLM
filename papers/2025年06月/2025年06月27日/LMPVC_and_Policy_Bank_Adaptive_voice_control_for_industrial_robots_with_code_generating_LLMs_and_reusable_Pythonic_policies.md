# LMPVC 和 Policy Bank：基于代码生成的 LLM 和可重用 Python 策略库的工业机器人自适应语音控制

发布时间：2025年06月27日

`LLM应用

LLM应用` `机器人` `人机交互`

> LMPVC and Policy Bank: Adaptive voice control for industrial robots with code generating LLMs and reusable Pythonic policies

# 摘要

> 现代工业正从传统的批量生产模式向专业化和个性化生产转型。随着制造任务复杂性的提升，全自动化并非总能实现，人类的参与变得愈发重要。这一趋势推动了先进人机协作（HRC）技术的发展，尤其是语音控制等交互方式的创新。人工智能（AI）驱动的自然语言处理技术的突破为这一需求提供了有力支持。大语言模型（LLMs）在通用推理能力上取得了显著进展，多种将其应用于机器人技术的方法相继涌现，包括基于代码生成的方案。本文提出了一种名为语言模型程序语音控制（LMPVC）的基于大语言模型的原型语音控制架构，该系统集成了策略编程和教学功能，专为与Robot Operating System 2（ROS2）兼容的机器人设计。该架构在先前基于代码生成的语音控制研究基础上，引入了策略库（Policy Bank）这一额外的编程和教学系统。通过这一创新，LMPVC能够克服底层大语言模型的局限性，无需经历漫长且昂贵的训练过程，即可灵活适应不同下游任务。该架构及相关成果已在GitHub上开源（https://github.com/ozzyuni/LMPVC）。

> Modern industry is increasingly moving away from mass manufacturing, towards more specialized and personalized products. As manufacturing tasks become more complex, full automation is not always an option, human involvement may be required. This has increased the need for advanced human robot collaboration (HRC), and with it, improved methods for interaction, such as voice control. Recent advances in natural language processing, driven by artificial intelligence (AI), have the potential to answer this demand. Large language models (LLMs) have rapidly developed very impressive general reasoning capabilities, and many methods of applying this to robotics have been proposed, including through the use of code generation. This paper presents Language Model Program Voice Control (LMPVC), an LLM-based prototype voice control architecture with integrated policy programming and teaching capabilities, built for use with Robot Operating System 2 (ROS2) compatible robots. The architecture builds on prior works using code generation for voice control by implementing an additional programming and teaching system, the Policy Bank. We find this system can compensate for the limitations of the underlying LLM, and allow LMPVC to adapt to different downstream tasks without a slow and costly training process. The architecture and additional results are released on GitHub (https://github.com/ozzyuni/LMPVC).

[Arxiv](https://arxiv.org/abs/2506.22028)