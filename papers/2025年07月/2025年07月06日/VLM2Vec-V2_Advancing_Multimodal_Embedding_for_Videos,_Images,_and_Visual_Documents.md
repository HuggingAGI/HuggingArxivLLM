# VLM2Vec-V2：提升视频、图像与视觉文档的多模态嵌入研究

发布时间：2025年07月06日

`LLM应用` `人工智能` `多模态处理`

> VLM2Vec-V2: Advancing Multimodal Embedding for Videos, Images, and Visual Documents

# 摘要

> 多模态嵌入模型在实现语义相似性、信息检索和聚类等跨模态下游任务中发挥了关键作用。然而，现有的多模态嵌入模型，如VLM2Vec、E5-V和GME，主要专注于自然图像，对视频和视觉文档等其他视觉形式的支持有限。这限制了它们在实际场景中的应用，包括AI代理、多模态搜索与推荐以及增强检索生成（RAG）。为了解决这一问题，我们提出了VLM2Vec-V2，一个适用于多种视觉形式的统一嵌入学习框架。

首先，我们引入了MMEB-V2，这是一个全面的基准测试，扩展了MMEB，新增了五种任务类型：视觉文档检索、视频检索、时间定位、视频分类和视频问答，涵盖了文本、图像、视频和视觉文档输入。其次，我们训练了VLM2Vec-V2，这是一个支持文本、图像、视频和视觉文档输入的通用嵌入模型。

大量实验表明，VLM2Vec-V2不仅在新引入的视频和文档检索任务中表现优异，还在原始图像基准测试中超越了先前的基线模型。通过全面的评估，我们的研究为各种多模态嵌入模型的泛化能力提供了见解，并强调了统一嵌入学习的有效策略，为研究和实际应用中更具扩展性和适应性的表示学习奠定了基础。


> Multimodal embedding models have been crucial in enabling various downstream tasks such as semantic similarity, information retrieval, and clustering over different modalities. However, existing multimodal embeddings like VLM2Vec, E5-V, GME are predominantly focused on natural images, with limited support for other visual forms such as videos and visual documents. This restricts their applicability in real-world scenarios, including AI agents, multi-modal search and recommendation, and retrieval-augmented generation (RAG). To close this gap, we propose VLM2Vec-V2, a unified framework for learning embeddings across diverse visual forms. First, we introduce MMEB-V2, a comprehensive benchmark that extends MMEB with five new task types: visual document retrieval, video retrieval, temporal grounding, video classification and video question answering - spanning text, image, video, and visual document inputs. Next, we train VLM2Vec-V2, a general-purpose embedding model that supports text, image, video, and visual document inputs. Extensive experiments show that VLM2Vec-V2 achieves strong performance not only on the newly introduced video and document retrieval tasks, but also improves over prior baselines on the original image benchmarks. Through extensive evaluation, our study offers insights into the generalizability of various multimodal embedding models and highlights effective strategies for unified embedding learning, laying the groundwork for more scalable and adaptable representation learning in both research and real-world settings.

[Arxiv](https://arxiv.org/abs/2507.04590)