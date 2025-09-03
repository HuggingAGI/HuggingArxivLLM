# IndusGCC：面向工业自动化中基于图形用户界面的通用计算机控制的数据基准与评估框架

发布时间：2025年09月01日

`LLM应用` `工业与制造`

> IndusGCC: A Data Benchmark and Evaluation Framework for GUI-Based General Computer Control in Industrial Automation

# 摘要

> 工业4.0浪潮下，柔性制造已成为现代工业体系的核心，设备自动化更是其中的关键支柱。然而，现有工业设备控制软件多依赖图形用户界面（GUIs），需通过鼠标点击、屏幕触摸等人工操作实现交互，这给基于代码的设备自动化普及造成了巨大阻碍。近年来，基于大型语言模型的通用计算机控制（LLM-GCC）崭露头角，为自动化GUI操作提供了新的可能。但工业场景存在其特殊性：界面视觉多样且高度专业化，任务关键且对精度要求极高，这些都构成了独特挑战。为此，本文推出IndusGCC——首个面向工业环境LLM-GCC的数据集与基准，涵盖机械臂控制、生产线配置等七个领域的448项真实任务。该数据集包含设备软件的多模态人机交互数据，可为GUI级代码生成提供可靠监督。此外，我们还提出了一种融合功能与结构指标的新型评估框架，用于评估LLM生成的控制脚本。在主流LLM上的实验结果表明，LLM-GCC虽潜力巨大但仍面临挑战，为未来全自动化工厂的研究奠定了坚实基础。相关数据与代码已公开，地址为：\href{https://github.com/Golden-Arc/IndustrialLLM}{https://github.com/Golden-Arc/IndustrialLLM.}

> As Industry 4.0 progresses, flexible manufacturing has become a cornerstone of modern industrial systems, with equipment automation playing a pivotal role. However, existing control software for industrial equipment, typically reliant on graphical user interfaces (GUIs) that require human interactions such as mouse clicks or screen touches, poses significant barriers to the adoption of code-based equipment automation. Recently, Large Language Model-based General Computer Control (LLM-GCC) has emerged as a promising approach to automate GUI-based operations. However, industrial settings pose unique challenges, including visually diverse, domain-specific interfaces and mission-critical tasks demanding high precision. This paper introduces IndusGCC, the first dataset and benchmark tailored to LLM-GCC in industrial environments, encompassing 448 real-world tasks across seven domains, from robotic arm control to production line configuration. IndusGCC features multimodal human interaction data with the equipment software, providing robust supervision for GUI-level code generation. Additionally, we propose a novel evaluation framework with functional and structural metrics to assess LLM-generated control scripts. Experimental results on mainstream LLMs demonstrate both the potential of LLM-GCC and the challenges it faces, establishing a strong foundation for future research toward fully automated factories. Our data and code are publicly available at: \href{https://github.com/Golden-Arc/IndustrialLLM}{https://github.com/Golden-Arc/IndustrialLLM.

[Arxiv](https://arxiv.org/abs/2509.01199)