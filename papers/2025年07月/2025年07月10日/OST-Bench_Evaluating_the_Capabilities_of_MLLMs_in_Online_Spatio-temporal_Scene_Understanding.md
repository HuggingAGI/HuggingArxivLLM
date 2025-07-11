# OST-Bench：评测多语言大模型的在线时空场景理解能力

发布时间：2025年07月10日

`LLM应用` `计算机视觉` `机器人学`

> OST-Bench: Evaluating the Capabilities of MLLMs in Online Spatio-temporal Scene Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在视觉与语言结合的复杂推理方面展现出非凡的能力。然而，现有的基准测试大多基于离线设置，使用固定预设的输入来评估模型。我们推出OST-Bench，一个全新的基准测试，从智能体主动探索场景的视角评估在线时空理解能力。在线特性强调了对增量获取的观察进行处理和推理的必要性，而时空组件则要求将当前视觉输入与历史记忆结合，支持动态空间推理。OST-Bench更贴近现实世界中具身感知的挑战。它基于高效的数据收集管道构建，包含从ScanNet、Matterport3D和ARKitScenes收集的1.4千个场景和1万条问答对。我们在OST-Bench上评估了多种领先的MLLMs，发现它们在复杂时空推理任务上表现欠佳。在在线设置下，随着探索范围扩大和记忆增长，模型准确性下降。通过深入实验分析，我们发现模型间存在共同的错误模式，并揭示了复杂线索推理需求和长期记忆检索要求分别在两个维度上显著降低了模型性能，突显了提升在线具身推理能力的核心挑战。为了推动该领域的发展，我们的代码、数据集和基准测试已公开。项目页面：https://rbler1234.github.io/OSTBench.github.io/

> Recent advances in multimodal large language models (MLLMs) have shown remarkable capabilities in integrating vision and language for complex reasoning. While most existing benchmarks evaluate models under offline settings with a fixed set of pre-recorded inputs, we introduce OST-Bench, a benchmark designed to evaluate Online Spatio-Temporal understanding from the perspective of an agent actively exploring a scene. The Online aspect emphasizes the need to process and reason over incrementally acquired observations, while the Spatio-Temporal component requires integrating current visual inputs with historical memory to support dynamic spatial reasoning. OST-Bench better reflects the challenges of real-world embodied perception. Built on an efficient data collection pipeline, OST-Bench consists of 1.4k scenes and 10k question-answer pairs collected from ScanNet, Matterport3D, and ARKitScenes. We evaluate several leading MLLMs on OST-Bench and observe that they fall short on tasks requiring complex spatio-temporal reasoning. Under the online setting, their accuracy declines as the exploration horizon extends and the memory grows. Through further experimental analysis, we identify common error patterns across models and find that both complex clue-based spatial reasoning demands and long-term memory retrieval requirements significantly drop model performance along two separate axes, highlighting the core challenges that must be addressed to improve online embodied reasoning. To foster further research and development in the field, our codes, dataset, and benchmark are available. Our project page is: https://rbler1234.github.io/OSTBench.github.io/

[Arxiv](https://arxiv.org/abs/2507.07984)