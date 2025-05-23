# # 评估增强型检索多模态生成在文档问答中的表现

发布时间：2025年05月22日

`RAG` `问答系统` `文档处理`

> Benchmarking Retrieval-Augmented Multimomal Generation for Document Question Answering

# 摘要

> 文档视觉问答（DocVQA）在处理长篇多模态文档和跨模态推理方面面临双重挑战。当前的文档检索增强生成（DocRAG）方法以文本为中心，常忽略关键视觉信息，且缺乏评估多模态证据选择和整合的强健基准。我们推出MMDocRAG，一个包含4055个专家标注问答对的全面基准，涵盖多页、跨模态证据链。我们的框架引入了创新的多模态引用选择评估指标，并支持在答案中交错呈现文本与相关视觉元素。通过使用60个VLM/LLM模型和14个检索系统的大型实验，我们识别出多模态证据检索、选择和整合方面的持续挑战。结果显示，先进的专有LVMs比开源替代方案表现更优，且在使用多模态输入时具有适度优势，而开源方案则性能显著下降。值得注意的是，经过微调的LLMs在使用详细图像描述时表现大幅提升。MMDocRAG为开发更强大的多模态DocVQA系统提供了严格的测试环境和实用见解。我们的基准和代码可在https://mmdocrag.github.io/MMDocRAG/获取。

> Document Visual Question Answering (DocVQA) faces dual challenges in processing lengthy multimodal documents (text, images, tables) and performing cross-modal reasoning. Current document retrieval-augmented generation (DocRAG) methods remain limited by their text-centric approaches, frequently missing critical visual information. The field also lacks robust benchmarks for assessing multimodal evidence selection and integration. We introduce MMDocRAG, a comprehensive benchmark featuring 4,055 expert-annotated QA pairs with multi-page, cross-modal evidence chains. Our framework introduces innovative metrics for evaluating multimodal quote selection and enables answers that interleave text with relevant visual elements. Through large-scale experiments with 60 VLM/LLM models and 14 retrieval systems, we identify persistent challenges in multimodal evidence retrieval, selection, and integration.Key findings reveal advanced proprietary LVMs show superior performance than open-sourced alternatives. Also, they show moderate advantages using multimodal inputs over text-only inputs, while open-source alternatives show significant performance degradation. Notably, fine-tuned LLMs achieve substantial improvements when using detailed image descriptions. MMDocRAG establishes a rigorous testing ground and provides actionable insights for developing more robust multimodal DocVQA systems. Our benchmark and code are available at https://mmdocrag.github.io/MMDocRAG/.

[Arxiv](https://arxiv.org/abs/2505.16470)