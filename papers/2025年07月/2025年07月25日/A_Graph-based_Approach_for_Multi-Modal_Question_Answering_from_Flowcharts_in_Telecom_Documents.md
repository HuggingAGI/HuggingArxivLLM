# 一种基于图的多模态问答方法，用于从电信文档中的流程图中提取信息

发布时间：2025年07月25日

`RAG` `问答系统`

> A Graph-based Approach for Multi-Modal Question Answering from Flowcharts in Telecom Documents

# 摘要

> 从技术文档中进行问答 (QA) 时，经常需要回答的问题其答案存在于图表中，例如流程图或流程图。基于文本的检索增强生成 (RAG) 系统可能无法回答此类问题。我们利用从视觉大语言模型 (VLMs) 获取的流程图的图表示，并将其整合到基于文本的 RAG 系统中，以展示这种方法可以实现图像检索用于电信领域的问答。我们展示了从处理技术文档、分类图像类型、构建图表示，到将其与文本嵌入管道结合以实现高效检索的端到端方法。我们在一个基于专有电信产品信息文档创建的问答数据集上进行了基准测试。结果显示，使用经过微调的 VLM 模型获得的图表示与真实值的编辑距离更小，这表明这些表示在流程图图像上的鲁棒性。此外，使用这些表示进行问答的方法在基于文本的嵌入模型中也获得了良好的检索性能，包括一个适应电信领域的模型。我们的方法还减轻了推理过程中对 VLM 的需求，这对部署的问答系统来说是一个重要的成本优势。

> Question-Answering (QA) from technical documents often involves questions whose answers are present in figures, such as flowcharts or flow diagrams. Text-based Retrieval Augmented Generation (RAG) systems may fail to answer such questions. We leverage graph representations of flowcharts obtained from Visual large Language Models (VLMs) and incorporate them in a text-based RAG system to show that this approach can enable image retrieval for QA in the telecom domain. We present the end-to-end approach from processing technical documents, classifying image types, building graph representations, and incorporating them with the text embedding pipeline for efficient retrieval. We benchmark the same on a QA dataset created based on proprietary telecom product information documents. Results show that the graph representations obtained using a fine-tuned VLM model have lower edit distance with respect to the ground truth, which illustrate the robustness of these representations for flowchart images. Further, the approach for QA using these representations gives good retrieval performance using text-based embedding models, including a telecom-domain adapted one. Our approach also alleviates the need for a VLM in inference, which is an important cost benefit for deployed QA systems.

[Arxiv](https://arxiv.org/abs/2507.22938)