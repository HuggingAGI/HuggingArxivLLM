# ProVision：通过编程为多模态语言模型规模化以视觉为核心的指令数据

发布时间：2024年12月09日

`LLM应用` `多模态`

> ProVision: Programmatically Scaling Vision-centric Instruction Data for Multimodal Language Models

# 摘要

> 随着多模态应用的兴起，指令数据对于训练能理解复杂图像查询的多模态语言模型至关重要。现有的实践依靠强大却昂贵的大型语言模型（LLMs）或多模态语言模型（MLMs）来生成指令数据，这些常常容易出现幻觉、许可问题，而且生成过程难以扩展和解释。在本研究中，我们提出一种编程方法，利用场景图作为图像的符号表示以及人工编写的程序，系统地合成以视觉为中心的指令数据。我们的方法保证了数据生成过程的可解释性和可控性，在保持事实准确性的同时能有效扩展。通过实现 24 个单图像、14 个多图像指令生成器和一个场景图生成管道，我们构建了一个可扩展、性价比高的系统：ProVision，它能为任何给定图像生成有关对象、属性、关系、深度等的多样问答对。应用于 Visual Genome 和 DataComp 数据集，我们生成了超 1000 万个指令数据点 ProVision-10M，并在 MLMs 的预训练和指令调整阶段加以利用。在指令调整阶段采用时，我们的单图像指令数据使 CVBench 的 2D 分割提升多达 7%，3D 分割提升 8%，QBench2、RealWorldQA 和 MMMU 的性能提升 3%。我们的多图像指令数据让 Mantis-Eval 提升 8%。将我们的数据纳入 xGen-MM-4B 的预训练和微调阶段，在 11 个基准测试中平均提升 1.6%。

> With the rise of multimodal applications, instruction data has become critical for training multimodal language models capable of understanding complex image-based queries. Existing practices rely on powerful but costly large language models (LLMs) or multimodal language models (MLMs) to produce instruction data. These are often prone to hallucinations, licensing issues and the generation process is often hard to scale and interpret. In this work, we present a programmatic approach that employs scene graphs as symbolic representations of images and human-written programs to systematically synthesize vision-centric instruction data. Our approach ensures the interpretability and controllability of the data generation process and scales efficiently while maintaining factual accuracy. By implementing a suite of 24 single-image, 14 multi-image instruction generators, and a scene graph generation pipeline, we build a scalable, cost-effective system: ProVision which produces diverse question-answer pairs concerning objects, attributes, relations, depth, etc., for any given image. Applied to Visual Genome and DataComp datasets, we generate over 10 million instruction data points, ProVision-10M, and leverage them in both pretraining and instruction tuning stages of MLMs. When adopted in the instruction tuning stage, our single-image instruction data yields up to a 7% improvement on the 2D split and 8% on the 3D split of CVBench, along with a 3% increase in performance on QBench2, RealWorldQA, and MMMU. Our multi-image instruction data leads to an 8% improvement on Mantis-Eval. Incorporation of our data in both pre-training and fine-tuning stages of xGen-MM-4B leads to an averaged improvement of 1.6% across 11 benchmarks.

[Arxiv](https://arxiv.org/abs/2412.07012)