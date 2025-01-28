# HumanOmni: 面向以人为中心的视频理解的大型视觉-语音语言模型

发布时间：2025年01月25日

`LLM应用

理由：这篇论文描述了一个名为HumanOmni的多模态大模型，旨在处理以人为中心的视觉和听觉信息。该模型通过构建大规模数据集和专门的分支架构来提升对多样化场景的理解能力，并在多个任务中表现出色。虽然论文中提到了多模态大模型，但其核心是应用这些模型来解决实际问题（如情感识别、面部表情描述和动作理解），因此归类为LLM应用更为合适。` `人机交互` `多媒体`

> HumanOmni: A Large Vision-Speech Language Model for Human-Centric Video Understanding

# 摘要

> 在以人为中心的场景中，同时理解视觉和听觉信息至关重要。尽管现有的全能模型能处理多种模态，但由于缺乏大规模专用数据集和非针对性架构，它们在这些场景中表现欠佳。为此，我们开发了业界首个以人为中心的全能多模态大模型——HumanOmni。我们构建了一个包含240万条以人为中心的视频片段和详细字幕的数据集，以及1400万条指令，助力多样化场景的理解。HumanOmni包含三个专门分支，用于理解不同类型的场景，并根据用户指令自适应融合特征，显著提升了对以个人为中心的视觉理解。此外，HumanOmni还集成了音频特征，确保对环境和个人的全面理解。实验表明，HumanOmni在情感识别、面部表情描述和动作理解等任务中表现出色。我们将开源该模型，推动学术界和工业界的进一步合作与发展。

> In human-centric scenes, the ability to simultaneously understand visual and auditory information is crucial. While recent omni models can process multiple modalities, they generally lack effectiveness in human-centric scenes due to the absence of large-scale, specialized datasets and non-targeted architectures. In this work, we developed HumanOmni, the industry's first human-centric Omni-multimodal large language model. We constructed a dataset containing over 2.4 million human-centric video clips with detailed captions and more than 14 million instructions, facilitating the understanding of diverse human-centric scenes. HumanOmni includes three specialized branches for understanding different types of scenes. It adaptively fuses features from these branches based on user instructions, significantly enhancing visual understanding in scenes centered around individuals. Moreover, HumanOmni integrates audio features to ensure a comprehensive understanding of environments and individuals. Our experiments validate HumanOmni's advanced capabilities in handling human-centric scenes across a variety of tasks, including emotion recognition, facial expression description, and action understanding. Our model will be open-sourced to facilitate further development and collaboration within both academia and industry.

[Arxiv](https://arxiv.org/abs/2501.15111)