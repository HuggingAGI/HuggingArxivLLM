# VideoCAD：从CAD软件中学习用户界面交互与三维推理的大规模视频数据集。

发布时间：2025年05月30日

`LLM应用` `计算机视觉`

> VideoCAD: A Large-Scale Video Dataset for Learning UI Interactions and 3D Reasoning from CAD Software

# 摘要

> 计算机辅助设计（CAD）是一项耗时且复杂的任务，需要用户与复杂的3D界面进行精确且长期的交互操作。尽管基于AI的用户界面（UI）代理技术近年来取得了进展，但现有大多数数据集和方法主要集中在移动端或网页应用中的短期、低复杂度任务上，未能满足专业工程工具的需求。在本研究中，我们引入了VideoCAD，这是首个专注于高精度任务的工程UI交互学习尝试。VideoCAD是一个包含超过41,000个标注的CAD操作视频记录的大型合成数据集，通过自动化框架从人工设计的CAD作品中收集高保真UI动作数据生成。与现有数据集相比，VideoCAD在真实工程任务中的UI交互学习复杂度提高了1个数量级，时间跨度最长是其他数据集的20倍。我们展示了VideoCAD的两个重要应用：从专业精密的3D CAD工具中学习UI交互，以及一个用于评估多模态大型语言模型（LLM）空间推理和视频理解能力的视觉问答（VQA）基准测试。为了学习UI交互，我们提出了VideoCADFormer——一种直接从视频学习CAD交互的先进模型，其性能优于多种行为克隆基线模型。无论是VideoCADFormer，还是基于VideoCAD的VQA基准测试，都揭示了当前基于视频的UI理解所面临的关键挑战，包括对精准动作定位、多模态与空间推理能力的需求，以及对长期依赖关系的处理要求。

> Computer-Aided Design (CAD) is a time-consuming and complex process, requiring precise, long-horizon user interactions with intricate 3D interfaces. While recent advances in AI-driven user interface (UI) agents show promise, most existing datasets and methods focus on short, low-complexity tasks in mobile or web applications, failing to capture the demands of professional engineering tools. In this work, we introduce VideoCAD, the first attempt at engineering UI interaction learning for precision tasks. Specifically, VideoCAD is a large-scale synthetic dataset consisting of over 41K annotated video recordings of CAD operations, generated using an automated framework for collecting high-fidelity UI action data from human-made CAD designs. Compared to existing datasets, VideoCAD offers an order of magnitude higher complexity in UI interaction learning for real-world engineering tasks, having up to a 20x longer time horizon than other datasets. We show two important downstream applications of VideoCAD: learning UI interactions from professional precision 3D CAD tools and a visual question-answering (VQA) benchmark designed to evaluate multimodal large language models' (LLM) spatial reasoning and video understanding abilities. To learn the UI interactions, we propose VideoCADFormer - a state-of-the-art model in learning CAD interactions directly from video, which outperforms multiple behavior cloning baselines. Both VideoCADFormer and the VQA benchmark derived from VideoCAD reveal key challenges in the current state of video-based UI understanding, including the need for precise action grounding, multi-modal and spatial reasoning, and long-horizon dependencies.

[Arxiv](https://arxiv.org/abs/2505.24838)