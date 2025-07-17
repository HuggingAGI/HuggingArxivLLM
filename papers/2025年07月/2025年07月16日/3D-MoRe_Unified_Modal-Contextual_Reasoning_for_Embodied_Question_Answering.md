# 3D-MoRe: 针具身问答任务的多模态上下文推理统一方法

发布时间：2025年07月16日

`LLM应用` `3D场景` `语言模型`

> 3D-MoRe: Unified Modal-Contextual Reasoning for Embodied Question Answering

# 摘要

> 为满足问答和密集描述等室内场景任务对多样化和可扩展数据的需求，我们提出了3D-MoRe这一创新范式，旨在通过整合多模态嵌入、跨模态交互和语言模型解码器等关键组件，生成大规模3D语言数据集。基于ScanNet 3D场景数据集，结合ScanQA和ScanRefer中的文本标注，3D-MoRe成功生成了涵盖1,513个场景的62,000个问答对和73,000个对象描述。通过多种数据增强技术和语义过滤，我们确保了数据的高质量。实验结果表明，3D-MoRe在ScanQA上将CIDEr分数提升了2.15%，在ScanRefer上使CIDEr@0.5提高了1.84%，充分证明了其在两项任务中的有效性。我们的代码和数据集将公开发布，访问地址为https://3D-MoRe.github.io，以支持社区研究。

> With the growing need for diverse and scalable data in indoor scene tasks, such as question answering and dense captioning, we propose 3D-MoRe, a novel paradigm designed to generate large-scale 3D-language datasets by leveraging the strengths of foundational models. The framework integrates key components, including multi-modal embedding, cross-modal interaction, and a language model decoder, to process natural language instructions and 3D scene data. This approach facilitates enhanced reasoning and response generation in complex 3D environments. Using the ScanNet 3D scene dataset, along with text annotations from ScanQA and ScanRefer, 3D-MoRe generates 62,000 question-answer (QA) pairs and 73,000 object descriptions across 1,513 scenes. We also employ various data augmentation techniques and implement semantic filtering to ensure high-quality data. Experiments on ScanQA demonstrate that 3D-MoRe significantly outperforms state-of-the-art baselines, with the CIDEr score improving by 2.15\%. Similarly, on ScanRefer, our approach achieves a notable increase in CIDEr@0.5 by 1.84\%, highlighting its effectiveness in both tasks. Our code and generated datasets will be publicly released to benefit the community, and both can be accessed on the https://3D-MoRe.github.io.

[Arxiv](https://arxiv.org/abs/2507.12026)