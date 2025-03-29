# # 大型视觉语言模型在自动驾驶中的细致评测

发布时间：2025年03月27日

`LLM应用

理由：这篇论文探讨了视觉语言模型（VLM）在自动驾驶（AD）中的应用，特别是通过引入VLADBench基准测试来评估和提升VLM在复杂驾驶场景中的能力。研究涉及模型在不同领域的表现和训练，属于将大语言模型应用于具体领域的范畴。` `自动驾驶` `视觉问答`

> Fine-Grained Evaluation of Large Vision-Language Models in Autonomous Driving

# 摘要

> 现有针对自动驾驶（AD）的视觉语言模型（VLM）基准测试主要通过粗粒度任务中的开放形式视觉问答（QA）来评估可解释性，但这种方法仍不足以评估复杂驾驶场景下的能力。为此，我们引入了$	extbf{VLADBench}$，这是一个具有挑战性且细粒度的数据集，其特点是通过从静态基础知识点和元素到动态道路情况下的高级推理的封闭形式问答。精心设计的$	extbf{VLADBench}$涵盖了5个关键领域：交通知识理解、通用元素识别、交通图生成、目标属性理解以及自我决策与规划。这些领域进一步细分为11个二级方面和29个三级任务，以实现细致的评估。对通用和领域特定（DS）VLM在该基准上的全面评估揭示了它们在AD场景中的优势与关键限制。为了进一步挖掘5个领域在AD理解中的认知与推理交互，我们从小规模的VLM开始，分别在各个领域的数据集上训练DS模型（数据集来自公共来源的140万个DS问答）。实验结果表明，所提出的基准为更全面地评估AD中的VLM提供了一个关键步骤，并为开发更具认知深度和推理能力的AD系统铺平了道路。

> Existing benchmarks for Vision-Language Model (VLM) on autonomous driving (AD) primarily assess interpretability through open-form visual question answering (QA) within coarse-grained tasks, which remain insufficient to assess capabilities in complex driving scenarios. To this end, we introduce $\textbf{VLADBench}$, a challenging and fine-grained dataset featuring close-form QAs that progress from static foundational knowledge and elements to advanced reasoning for dynamic on-road situations. The elaborate $\textbf{VLADBench}$ spans 5 key domains: Traffic Knowledge Understanding, General Element Recognition, Traffic Graph Generation, Target Attribute Comprehension, and Ego Decision-Making and Planning. These domains are further broken down into 11 secondary aspects and 29 tertiary tasks for a granular evaluation. A thorough assessment of general and domain-specific (DS) VLMs on this benchmark reveals both their strengths and critical limitations in AD contexts. To further exploit the cognitive and reasoning interactions among the 5 domains for AD understanding, we start from a small-scale VLM and train the DS models on individual domain datasets (collected from 1.4M DS QAs across public sources). The experimental results demonstrate that the proposed benchmark provides a crucial step toward a more comprehensive assessment of VLMs in AD, paving the way for the development of more cognitively sophisticated and reasoning-capable AD systems.

[Arxiv](https://arxiv.org/abs/2503.21505)