# Face-LLaVA：通过指令微调探索面部表情与属性理解

发布时间：2025年04月09日

`LLM应用` `计算机视觉` `社交媒体`

> Face-LLaVA: Facial Expression and Attribute Understanding through Instruction Tuning

# 摘要

> 面部在社交互动中至关重要，因此开发高性能的计算机视觉工具对于以人为中心的应用至关重要。我们提出了一种名为Face-LLaVA的多模态大型语言模型，专注于面部为中心的上下文学习，涵盖面部表情和属性识别。此外，Face-LLaVA还能生成自然语言描述，支持推理任务。基于现有的视觉数据库，我们首先构建了FaceInstruct-1M，这是一个专注于面部的数据库，用于对多模态大型语言模型进行指令微调，以优化面部处理任务。随后，我们开发了一种新型的特定于面部的视觉编码器，该编码器采用基于面部区域引导的交叉注意力机制，将面部几何结构与局部视觉特征相结合。我们在九个不同的数据集和五个面部处理任务上评估了Face-LLaVA，包括面部表情识别、动作单元检测、面部属性检测、年龄估计和深度伪造检测。Face-LLaVA在现有开源多模态大型语言模型中表现优异，并与商业解决方案相比也具有竞争力。在零样本设置下，我们的模型输出在所有任务上均获得了GPT更高的推理评分。我们的数据集和模型将在https://face-llava.github.io开源，以支持社交AI和基础视觉-语言研究的未来发展。

> The human face plays a central role in social communication, necessitating the use of performant computer vision tools for human-centered applications. We propose Face-LLaVA, a multimodal large language model for face-centered, in-context learning, including facial expression and attribute recognition. Additionally, Face-LLaVA is able to generate natural language descriptions that can be used for reasoning. Leveraging existing visual databases, we first developed FaceInstruct-1M, a face-centered database for instruction tuning MLLMs for face processing. We then developed a novel face-specific visual encoder powered by Face-Region Guided Cross-Attention that integrates face geometry with local visual features. We evaluated the proposed method across nine different datasets and five different face processing tasks, including facial expression recognition, action unit detection, facial attribute detection, age estimation and deepfake detection. Face-LLaVA achieves superior results compared to existing open-source MLLMs and competitive performance compared to commercial solutions. Our model output also receives a higher reasoning rating by GPT under a zero-shot setting across all the tasks. Both our dataset and model wil be released at https://face-llava.github.io to support future advancements in social AI and foundational vision-language research.

[Arxiv](https://arxiv.org/abs/2504.07198)