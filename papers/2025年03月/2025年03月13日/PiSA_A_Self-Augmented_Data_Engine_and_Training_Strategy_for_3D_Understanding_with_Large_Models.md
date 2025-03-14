# PiSA：自增强数据引擎与训练策略，助力大型模型实现三维理解

发布时间：2025年03月13日

`LLM应用` `3D建模` `多模态`

> PiSA: A Self-Augmented Data Engine and Training Strategy for 3D Understanding with Large Models

# 摘要

> 3D多模态大型语言模型（MLLMs）近年来取得了显著进展，但其潜力仍未被充分挖掘，这主要受限于3D数据集数量有限且质量有待提升。当前方法尝试通过迁移2D MLLMs的知识来扩展3D指令数据，但仍然面临模态和领域差距的挑战。为解决这一问题，我们提出了PiSA-Engine（Point-Self-Augmented-Engine），一个用于生成富含3D空间语义的指令点-语言数据集的新框架。我们发现，现有的3D MLLMs能够全面理解点云以支持标注任务，而2D MLLMs则擅长通过提供互补信息来进行跨模态验证。通过整合现成MLLMs提供的2D和3D整体见解，PiSA-Engine实现了高质量数据生成的持续循环。我们以PointLLM为基线，并采用这种协同进化训练框架开发了一个增强的3D MLLM，命名为PointLLM-PiSA。此外，我们识别出以往3D基准测试的局限性，这些问题通常表现为粗略的语言描述和类别多样性不足，导致评估结果不够准确。为填补这一空白，我们进一步推出了PiSA-Bench，一个涵盖六个关键方面的全面3D基准测试，配有详细且多样的标签。实验结果表明，在我们的PiSA-Bench上，PointLLM-PiSA在零样本3D对象描述和生成分类任务中达到了最新技术水平，分别取得了46.45%（+8.33%）和63.75%（+16.25%）的显著提升。我们将发布代码、数据集和基准测试。


> 3D Multimodal Large Language Models (MLLMs) have recently made substantial advancements. However, their potential remains untapped, primarily due to the limited quantity and suboptimal quality of 3D datasets. Current approaches attempt to transfer knowledge from 2D MLLMs to expand 3D instruction data, but still face modality and domain gaps. To this end, we introduce PiSA-Engine (Point-Self-Augmented-Engine), a new framework for generating instruction point-language datasets enriched with 3D spatial semantics. We observe that existing 3D MLLMs offer a comprehensive understanding of point clouds for annotation, while 2D MLLMs excel at cross-validation by providing complementary information. By integrating holistic 2D and 3D insights from off-the-shelf MLLMs, PiSA-Engine enables a continuous cycle of high-quality data generation. We select PointLLM as the baseline and adopt this co-evolution training framework to develop an enhanced 3D MLLM, termed PointLLM-PiSA. Additionally, we identify limitations in previous 3D benchmarks, which often feature coarse language captions and insufficient category diversity, resulting in inaccurate evaluations. To address this gap, we further introduce PiSA-Bench, a comprehensive 3D benchmark covering six key aspects with detailed and diverse labels. Experimental results demonstrate PointLLM-PiSA's state-of-the-art performance in zero-shot 3D object captioning and generative classification on our PiSA-Bench, achieving significant improvements of 46.45% (+8.33%) and 63.75% (+16.25%), respectively. We will release the code, datasets, and benchmark.

[Arxiv](https://arxiv.org/abs/2503.10529)