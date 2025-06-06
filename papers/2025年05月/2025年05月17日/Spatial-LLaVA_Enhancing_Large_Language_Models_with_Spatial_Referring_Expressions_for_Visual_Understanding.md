# 空间-LLaVA：通过空间指代表达式增强大型语言模型，提升视觉理解能力

发布时间：2025年05月17日

`LLM应用` `自动驾驶` `机器人`

> Spatial-LLaVA: Enhancing Large Language Models with Spatial Referring Expressions for Visual Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在处理视觉和文本输入方面表现出色，但面对数据匮乏的专用任务时表现欠佳。为此，我们推出了SUN-Spot v2.0数据集，包含9万张图片-文字描述对，并引入基于标记集的提示方法进行标注。我们还推出了Spatial-LLaVA，这是一个通过先进语言模型生成的对话数据训练而成的多模态模型。该方法确保图像物体与文字描述的一致性，使模型能够无偏见地学习空间指代表达。Spatial-LLaVA在零样本视觉推理任务中表现优异，尤其适用于需要精准对象识别的现实场景，如自动驾驶和交互式机器人。

> Multimodal large language models (MLLMs) have demonstrated remarkable abilities in comprehending visual input alongside text input. Typically, these models are trained on extensive data sourced from the internet, which are sufficient for general tasks such as scene understanding and question answering. However, they often underperform on specialized tasks where online data is scarce, such as determining spatial relationships between objects or localizing unique target objects within a group of objects sharing similar features. In response to this challenge, we introduce the SUN-Spot v2.0 dataset1, now comprising a total of 90k image-caption pairs and additional annotations on the landmark objects. Each image-caption pair utilizes Set-of-Marks prompting as an additional indicator, mapping each landmark object in the image to the corresponding object mentioned in the caption. Furthermore, we present Spatial-LLaVA, an MLLM trained on conversational data generated by a state-of-the-art language model using the SUNSpot v2.0 dataset. Our approach ensures a robust alignment between the objects in the images and their corresponding object mentions in the captions, enabling our model to learn spatial referring expressions without bias from the semantic information of the objects. Spatial-LLaVA outperforms previous methods by 3.15% on the zero-shot Visual Spatial Reasoning benchmark dataset. Spatial-LLaVA is specifically designed to precisely understand spatial referring expressions, making it highly applicable for tasks in real-world scenarios such as autonomous navigation and interactive robotics, where precise object recognition is critical.

[Arxiv](https://arxiv.org/abs/2505.12194)