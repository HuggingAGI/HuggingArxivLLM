# BuildingBlock：结构化建筑生成的混合方法探索

发布时间：2025年05月06日

`LLM应用` `虚拟现实`

> BuildingBlock: A Hybrid Approach for Structured Building Generation

# 摘要

> 三维建筑生成在游戏、虚拟现实和数字孪生等领域具有重要意义，但现有方法在生成多样、结构合理且层次连贯的建筑方面仍存在挑战。为此，我们提出BuildingBlock，这是一种融合生成模型、程序化内容生成（PCG）和大型语言模型（LLMs）的混合方法，旨在突破这些限制。具体而言，我们设计了布局生成阶段（LGP）和建筑构建阶段（BCP）的两阶段流水线。

在布局生成阶段（LGP），我们将基于盒子的布局生成重新定义为点云生成任务，借助新构建的建筑数据集和基于Transformer的扩散模型，生成全局一致的布局。通过大型语言模型（LLMs），这些布局被扩展为基于规则的层级设计，无缝融入组件风格和空间结构。

建筑构建阶段（BCP）利用这些布局来指导程序化内容生成（PCG），实现局部可定制、高质量的结构化建筑生成。实验结果表明，BuildingBlock在生成多样且层次结构清晰的建筑方面表现出色，已在多个基准测试中达到 state-of-the-art 水平，并为可扩展且直观的建筑设计工作流程奠定了基础。

> Three-dimensional building generation is vital for applications in gaming, virtual reality, and digital twins, yet current methods face challenges in producing diverse, structured, and hierarchically coherent buildings. We propose BuildingBlock, a hybrid approach that integrates generative models, procedural content generation (PCG), and large language models (LLMs) to address these limitations. Specifically, our method introduces a two-phase pipeline: the Layout Generation Phase (LGP) and the Building Construction Phase (BCP).
  LGP reframes box-based layout generation as a point-cloud generation task, utilizing a newly constructed architectural dataset and a Transformer-based diffusion model to create globally consistent layouts. With LLMs, these layouts are extended into rule-based hierarchical designs, seamlessly incorporating component styles and spatial structures.
  The BCP leverages these layouts to guide PCG, enabling local-customizable, high-quality structured building generation. Experimental results demonstrate BuildingBlock's effectiveness in generating diverse and hierarchically structured buildings, achieving state-of-the-art results on multiple benchmarks, and paving the way for scalable and intuitive architectural workflows.

[Arxiv](https://arxiv.org/abs/2505.04051)