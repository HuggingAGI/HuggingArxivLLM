# Text-Scene：面向3D场景理解的场景-语言解析框架

发布时间：2025年09月20日

`Agent` `基础理论`

> Text-Scene: A Scene-to-Language Parsing Framework for 3D Scene Understanding

# 摘要

> 让智能体理解并与复杂3D场景交互，是具身人工智能系统的核心难题。尽管多模态大型语言模型（MLLMs）已在2D图像理解上成效显著，但要将这些能力拓展到3D场景仍面临两大难点：一是3D环境包含更丰富的概念，如空间关系、功能可供性、物理特性、布局等；二是缺乏大规模3D视觉-语言数据集，这成为了主要瓶颈。为此，本文提出Text-Scene框架，它能自动将3D场景解析为文本描述，助力场景理解。面对3D场景时，该模型会先识别物体属性与空间关系，再生成整个场景的连贯摘要，无需人工干预就能架起3D观察与语言间的桥梁。Text-Scene结合几何分析与MLLMs，生成的描述准确详实、易于人类理解，既能捕捉物体级细节，又能兼顾全局上下文。基准测试结果显示，我们的文本解析能准确还原3D场景，且对下游任务大有裨益。为评估MLLMs的推理能力，我们还构建了InPlan3D——一个全面的3D任务规划基准，涵盖636个室内场景中的3174项长期规划任务。我们的方法注重清晰易懂与实用性，目标是让3D场景内容通过语言变得直观可懂。相关代码与数据集将开源发布。

> Enabling agents to understand and interact with complex 3D scenes is a fundamental challenge for embodied artificial intelligence systems. While Multimodal Large Language Models (MLLMs) have achieved significant progress in 2D image understanding, extending such capabilities to 3D scenes remains difficult: 1) 3D environment involves richer concepts such as spatial relationships, affordances, physics, layout, and so on, 2) the absence of large-scale 3D vision-language datasets has posed a significant obstacle. In this paper, we introduce Text-Scene, a framework that automatically parses 3D scenes into textual descriptions for scene understanding. Given a 3D scene, our model identifies object attributes and spatial relationships, and then generates a coherent summary of the whole scene, bridging the gap between 3D observation and language without requiring human-in-the-loop intervention. By leveraging both geometric analysis and MLLMs, Text-Scene produces descriptions that are accurate, detailed, and human-interpretable, capturing object-level details and global-level context. Experimental results on benchmarks demonstrate that our textual parses can faithfully represent 3D scenes and benefit downstream tasks. To evaluate the reasoning capability of MLLMs, we present InPlan3D, a comprehensive benchmark for 3D task planning, consisting of 3174 long-term planning tasks across 636 indoor scenes. We emphasize clarity and accessibility in our approach, aiming to make 3D scene content understandable through language. Code and datasets will be released.

[Arxiv](https://arxiv.org/abs/2509.16721)