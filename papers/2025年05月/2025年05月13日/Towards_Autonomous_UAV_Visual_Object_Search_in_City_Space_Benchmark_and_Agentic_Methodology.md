# # 摘要
探索无人机自主视觉目标搜索在城市空间中的基准与方法论

发布时间：2025年05月13日

`Agent` `无人机`

> Towards Autonomous UAV Visual Object Search in City Space: Benchmark and Agentic Methodology

# 摘要

> 城市环境中的空中视觉目标搜索 (AVOS) 任务要求无人机 (UAV) 在无需外部指导的情况下，利用视觉和文本线索自主搜索并识别目标物体。然而，现有方法在复杂城市环境中面临冗余语义处理、相似物体区分以及探索与利用平衡的挑战。为解决这一问题，我们提出了 CityAVOS，这是首个用于城市常见物体自主搜索的基准数据集。该数据集包含六类物体，共 2,420 个任务，难度各异，为全面评估无人机搜索能力提供了支持。

为高效解决 AVOS 任务，我们提出了 PRPSearcher（感知-推理-规划搜索器），这是一种基于多模态大语言模型 (MLLMs) 的新型智能体方法，模拟人类的三层认知过程。PRPSearcher 构建了三个专用地图：以物体为中心的动态语义图以增强空间感知，基于语义吸引力值的 3D 认知图用于目标推理，以及用于平衡探索与利用搜索的 3D 不确定性图。此外，我们的方法还引入了去噪机制以减少相似物体干扰，并采用灵感促进思维 (IPT) 提示机制进行自适应行动规划。

实验结果表明，PRPSearcher 在 CityAVOS 数据集上表现出色，成功率平均提升了 37.69%，搜索效率显著提高（路径长度效率提升 28.96%，搜索步数减少 30.69%，导航效率减少 46.40%）。尽管如此，与人类相比仍存在性能差距，这表明 AVOS 任务中更优的语义推理和空间探索能力仍有待提升。这项研究为未来具身目标搜索的进展奠定了基础。数据集和源代码可在 https://anonymous.4open.science/r/CityAVOS-3DF8 获取。

> Aerial Visual Object Search (AVOS) tasks in urban environments require Unmanned Aerial Vehicles (UAVs) to autonomously search for and identify target objects using visual and textual cues without external guidance. Existing approaches struggle in complex urban environments due to redundant semantic processing, similar object distinction, and the exploration-exploitation dilemma. To bridge this gap and support the AVOS task, we introduce CityAVOS, the first benchmark dataset for autonomous search of common urban objects. This dataset comprises 2,420 tasks across six object categories with varying difficulty levels, enabling comprehensive evaluation of UAV agents' search capabilities. To solve the AVOS tasks, we also propose PRPSearcher (Perception-Reasoning-Planning Searcher), a novel agentic method powered by multi-modal large language models (MLLMs) that mimics human three-tier cognition. Specifically, PRPSearcher constructs three specialized maps: an object-centric dynamic semantic map enhancing spatial perception, a 3D cognitive map based on semantic attraction values for target reasoning, and a 3D uncertainty map for balanced exploration-exploitation search. Also, our approach incorporates a denoising mechanism to mitigate interference from similar objects and utilizes an Inspiration Promote Thought (IPT) prompting mechanism for adaptive action planning. Experimental results on CityAVOS demonstrate that PRPSearcher surpasses existing baselines in both success rate and search efficiency (on average: +37.69% SR, +28.96% SPL, -30.69% MSS, and -46.40% NE). While promising, the performance gap compared to humans highlights the need for better semantic reasoning and spatial exploration capabilities in AVOS tasks. This work establishes a foundation for future advances in embodied target search. Dataset and source code are available at https://anonymous.4open.science/r/CityAVOS-3DF8.

[Arxiv](https://arxiv.org/abs/2505.08765)