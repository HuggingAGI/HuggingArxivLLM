# MindVL：致力于在昇腾NPUs上高效且有效地训练多模态大型语言模型

发布时间：2025年09月15日

`LLM应用` `基础理论`

> MindVL: Towards Efficient and Effective Training of Multimodal Large Language Models on Ascend NPUs

# 摘要

> 我们提出了MindVL——一款基于昇腾NPUs训练的多模态大型语言模型。与Qwen2.5-VL类似，该模型采用原生分辨率视觉Transformer，能够直接以图像原始的可变分辨率进行处理。这种设计避免了固定分辨率分块导致的质量损失，同时保留细粒度细节与全局布局——这对复杂图表等视觉密集型内容而言至关重要。为确保MindVL在昇腾NPUs上高效训练，我们开发了Mindspeed-MLLM——专为昇腾NPUs定制的分布式多模态训练框架。为保证训练精度，我们对部分算子进行了等效替换。MindVL通过三阶段训练逐步提升能力：热身阶段、多任务训练阶段及监督指令微调阶段。训练过程从基础视觉与多模态预训练起步，随后进行大规模多任务训练和指令微调。我们还采用多模态数据打包与混合并行技术，大幅提升了端到端训练速度。为进一步优化模型性能，特别引入测试时分辨率搜索与模型权重平均技术。值得关注的是，尽管训练数据量仅为Qwen2.5-VL的约1/10，MindVL在通用多模态理解及文档/表格解读任务评估中性能已与Qwen2.5-VL相当。除综合得分外，MindVL在OCR评估中也表现领先。

> We propose MindVL, a multimodal large langauge model trained on Ascend NPUs. Similar to Qwen2.5-VL, MindVL adopts native-resolution Vision Transformers, which enables it to process images at their original variable resolutions. This design avoids the degradation caused by fixed-resolution tiling while preserving fine-grained details and global layouts, which is crucial for visually dense content such as complex charts and diagrams. To ensure the smooth training of MindVL on Ascend NPUs, we develop Mindspeed-MLLM, a distributed multimodal training framework tailored for Ascend NPUs. To maintain training accuracy, we implement equivalent replacements for certain operators. MindVL undergoes a three-phase training process, namely the warm-up phase, multitask training phase, and supervised instruction tuning phase, to gradually enhance its capabilities. This process starts with basic visual and multimodal pre-training, followed by large-scale multiask trainging and instruction tuning. We also adopt multimodal data packaging and hybrid parallelism techniques, which significantly improve end-to-end training speed. To further boost model performance, we specifically introduce test-time resolution search and model weight averaging. Notably, despite using about 1/10 of the training data required by Qwen2.5-VL, MindVL achieves performance on par with Qwen2.5-VL in evaluations of general multimodal understanding and document/table comprehension. Beyond overall scores, MindVL also delivers leading performance in OCR assessments.

[Arxiv](https://arxiv.org/abs/2509.11662)