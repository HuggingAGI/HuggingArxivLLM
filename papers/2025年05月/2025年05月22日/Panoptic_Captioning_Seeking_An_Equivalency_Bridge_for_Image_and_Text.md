# 全知式图像描述：构建连接图像与文本的等效桥梁

发布时间：2025年05月22日

`LLM应用` `计算机视觉` `多模态生成`

> Panoptic Captioning: Seeking An Equivalency Bridge for Image and Text

# 摘要

> 我们提出了全景式图像描述（panoptic captioning），一个旨在用最少文字完整表达图像内容的创新任务。通过将其定义为生成图像全面文本描述的任务，我们开启了实现全景式描述的第一步。这种描述不仅包含图像中的所有实体、它们的位置和属性，还包括实体间的关系以及整体图像状态。研究发现，当前最先进的多模态大型语言模型（MLLMs）在处理全景式描述任务时表现有限。为解决这一问题，我们开发了PancapEngine数据引擎和PancapChain方法。PancapEngine通过一套详尽的检测工具识别图像实体，并生成基于实体感知的描述。PancapChain将复杂的描述任务分解为多个阶段，逐步生成描述。我们还提出了PancapScore评估指标和人工整理的测试集，以确保评估的可靠性。实验结果显示，我们的PancapChain-13B模型不仅超越了开源模型InternVL-2.5-78B，甚至在某些方面超过了GPT-4和Gemini-2.0-Pro，证明了我们的方法的有效性。项目页面：https://visual-ai.github.io/pancap/

> This work introduces panoptic captioning, a novel task striving to seek the minimum text equivalence of images. We take the first step towards panoptic captioning by formulating it as a task of generating a comprehensive textual description for an image, which encapsulates all entities, their respective locations and attributes, relationships among entities, as well as global image state.Through an extensive evaluation, our work reveals that state-of-the-art Multi-modal Large Language Models (MLLMs) have limited performance in solving panoptic captioning. To address this, we propose an effective data engine named PancapEngine to produce high-quality data and a novel method named PancapChain to improve panoptic captioning. Specifically, our PancapEngine first detects diverse categories of entities in images by an elaborate detection suite, and then generates required panoptic captions using entity-aware prompts. Additionally, our PancapChain explicitly decouples the challenging panoptic captioning task into multiple stages and generates panoptic captions step by step. More importantly, we contribute a comprehensive metric named PancapScore and a human-curated test set for reliable model evaluation.Experiments show that our PancapChain-13B model can beat state-of-the-art open-source MLLMs like InternVL-2.5-78B and even surpass proprietary models like GPT-4o and Gemini-2.0-Pro, demonstrating the effectiveness of our data engine and method. Project page: https://visual-ai.github.io/pancap/

[Arxiv](https://arxiv.org/abs/2505.16334)