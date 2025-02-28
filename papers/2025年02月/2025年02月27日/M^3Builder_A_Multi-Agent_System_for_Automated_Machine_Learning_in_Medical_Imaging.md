# M^3Builder：医学影像自动机器学习的多智能体系统

发布时间：2025年02月27日

`Agent` `医学影像`

> M^3Builder: A Multi-Agent System for Automated Machine Learning in Medical Imaging

# 摘要

> 智能体AI系统因能自主执行复杂任务而备受关注，但其对预先准备好的工具的依赖限制了在医疗领域的应用。本文提出三项创新：(i) M3Builder，一个专为医学影像机器学习（ML）设计的新型多智能体系统。该系统通过四个专业智能体协同工作，从数据处理到模型训练，全流程自动化处理复杂医学ML任务。智能体在一个结构化环境中运行，可自由访问数据集、代码和工具，实现高效沟通与执行。 (ii) 我们开发了M3Bench基准测试，包含14个数据集，覆盖五个解剖部位、三种成像模态，支持2D和3D数据，用于评估医学影像ML的自动化进展。 (iii) 我们尝试了七种先进大型语言模型作为智能体核心，包括Claude系列、GPT-4o和DeepSeek-V3。实验表明，M3Builder在医学影像ML任务中表现优异，使用Claude-3.7-Sonnet作为核心时，成功率达94.29%，展现了全自动医学影像ML的光明前景。

> Agentic AI systems have gained significant attention for their ability to autonomously perform complex tasks. However, their reliance on well-prepared tools limits their applicability in the medical domain, which requires to train specialized models. In this paper, we make three contributions: (i) We present M3Builder, a novel multi-agent system designed to automate machine learning (ML) in medical imaging. At its core, M3Builder employs four specialized agents that collaborate to tackle complex, multi-step medical ML workflows, from automated data processing and environment configuration to self-contained auto debugging and model training. These agents operate within a medical imaging ML workspace, a structured environment designed to provide agents with free-text descriptions of datasets, training codes, and interaction tools, enabling seamless communication and task execution. (ii) To evaluate progress in automated medical imaging ML, we propose M3Bench, a benchmark comprising four general tasks on 14 training datasets, across five anatomies and three imaging modalities, covering both 2D and 3D data. (iii) We experiment with seven state-of-the-art large language models serving as agent cores for our system, such as Claude series, GPT-4o, and DeepSeek-V3. Compared to existing ML agentic designs, M3Builder shows superior performance on completing ML tasks in medical imaging, achieving a 94.29% success rate using Claude-3.7-Sonnet as the agent core, showing huge potential towards fully automated machine learning in medical imaging.

[Arxiv](https://arxiv.org/abs/2502.20301)