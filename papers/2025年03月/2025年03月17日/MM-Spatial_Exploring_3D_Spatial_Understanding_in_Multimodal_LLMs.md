# MM-Spatial：多模态大语言模型的三维空间理解探索

发布时间：2025年03月17日

`LLM应用` `计算机视觉` `人工智能`

> MM-Spatial: Exploring 3D Spatial Understanding in Multimodal LLMs

# 摘要

> 多模态大型语言模型（MLLMs）在2D视觉理解方面表现出色，但在3D空间推理能力上仍显不足。为此，我们利用大规模高质量的3D场景数据和开放集标注，提出了两个创新成果：1）全新的监督微调数据集，以及2）专注于室内场景的新评估基准。我们的Cubify Anything VQA（CA-VQA）涵盖了多样化的空间任务，包括空间关系预测、度量尺寸和距离估计，以及3D定位。通过CA-VQA，我们成功训练出一个强大的通用MLLM——MM-Spatial，它在包括我们自己的在内的3D空间理解基准测试中达到了最先进的性能。我们还展示了如何通过整合度量深度和多视图输入（在CA-VQA中提供）来进一步提升3D理解能力，并证明仅通过数据即可使我们的模型实现与专用单目深度估计模型相当的深度感知能力。我们的SFT数据集和基准测试即将发布，为研究者提供宝贵资源。


> Multimodal large language models (MLLMs) excel at 2D visual understanding but remain limited in their ability to reason about 3D space. In this work, we leverage large-scale high-quality 3D scene data with open-set annotations to introduce 1) a novel supervised fine-tuning dataset and 2) a new evaluation benchmark, focused on indoor scenes. Our Cubify Anything VQA (CA-VQA) data covers diverse spatial tasks including spatial relationship prediction, metric size and distance estimation, and 3D grounding. We show that CA-VQA enables us to train MM-Spatial, a strong generalist MLLM that also achieves state-of-the-art performance on 3D spatial understanding benchmarks, including our own. We show how incorporating metric depth and multi-view inputs (provided in CA-VQA) can further improve 3D understanding, and demonstrate that data alone allows our model to achieve depth perception capabilities comparable to dedicated monocular depth estimation models. We will publish our SFT dataset and benchmark.

[Arxiv](https://arxiv.org/abs/2503.13111)