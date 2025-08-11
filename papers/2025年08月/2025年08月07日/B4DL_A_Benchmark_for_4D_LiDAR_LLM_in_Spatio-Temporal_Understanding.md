# # B4DL: A Benchmark for 4D LiDAR LLM in Spatio-Temporal Understanding  
B4DL：面向4D LiDAR大语言模型的时空理解基准测试

发布时间：2025年08月07日

`LLM应用

摘要讨论了将多模态大语言模型（MLLMs）应用于处理4D LiDAR数据，提出了一种新的基准和模型架构，属于LLM的应用领域。` `自动驾驶` `机器人`

> B4DL: A Benchmark for 4D LiDAR LLM in Spatio-Temporal Understanding

# 摘要

> 理解动态户外环境需要捕捉复杂物体的相互作用及其随时间的演变。基于LiDAR的4D点云提供了精确的空间几何信息和丰富的时序线索，使其成为表征真实场景的理想选择。然而，尽管具有巨大潜力，4D LiDAR在多模态大语言模型（MLLMs）中的应用仍未得到充分探索，这主要是由于缺乏高质量的模态特定标注以及缺乏能够处理其高维组成特性的MLLM架构。为了解决这些挑战，我们引入了B4DL，这是一个专门用于训练和评估MLLMs在4D LiDAR理解方面的新基准。此外，我们提出了一种可扩展的数据生成管道和一种MLLM模型，该模型首次通过将4D LiDAR与语言理解相结合，直接处理原始4D LiDAR数据。结合我们的数据集和基准，我们的模型为动态户外环境中的时空推理提供了一个统一的解决方案。我们提供了渲染的4D LiDAR视频、生成的数据集和在多种场景下的推理输出，访问链接为：https://mmb4dl.github.io/mmb4dl/

> Understanding dynamic outdoor environments requires capturing complex object interactions and their evolution over time. LiDAR-based 4D point clouds provide precise spatial geometry and rich temporal cues, making them ideal for representing real-world scenes. However, despite their potential, 4D LiDAR remains underexplored in the context of Multimodal Large Language Models (MLLMs) due to the absence of high-quality, modality-specific annotations and the lack of MLLM architectures capable of processing its high-dimensional composition. To address these challenges, we introduce B4DL, a new benchmark specifically designed for training and evaluating MLLMs on 4D LiDAR understanding. In addition, we propose a scalable data generation pipeline and an MLLM model that, for the first time, directly processes raw 4D LiDAR by bridging it with language understanding. Combined with our dataset and benchmark, our model offers a unified solution for spatio-temporal reasoning in dynamic outdoor environments. We provide rendered 4D LiDAR videos, generated dataset, and inference outputs on diverse scenarios at: https://mmb4dl.github.io/mmb4dl/

[Arxiv](https://arxiv.org/abs/2508.05269)