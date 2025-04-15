# 视频异常检测新方法：SlowFastVAD结合简单检测器与RAG增强视觉语言模型

发布时间：2025年04月14日

`LLM应用` `视频监控`

> SlowFastVAD: Video Anomaly Detection via Integrating Simple Detector and RAG-Enhanced Vision-Language Model

# 摘要

> 视频异常检测（VAD）致力于识别视频中的异常事件，在安全关键领域有着广泛应用。尽管半监督方法因其仅需正常样本训练而备受关注，但它们常面临高误报率和解释性差的挑战。近期，视觉语言模型（VLMs）凭借强大的多模态推理能力，为实现可解释的异常检测开辟了新路径。然而，高昂的计算成本和领域适应性不足的问题限制了其在实时部署和可靠性方面的应用。受人类视觉感知中双通路互补机制的启发，我们提出了SlowFastVAD，一个融合快速和慢速异常检测器（后者基于检索增强生成（RAG）增强的VLM）的混合框架，以突破这些限制。具体而言，快速检测器首先提供粗略的异常置信度评分，仅一小部分模糊片段会被进一步送入更慢但更具解释性的VLM进行详细检测和推理。此外，为使VLM更好地适应特定领域的VAD场景，我们基于少量正常样本和VLM推理的异常模式构建了一个知识库。推理过程中，相关模式会被检索并用于增强提示以辅助异常推理。最后，我们通过平滑融合快速和慢速检测器的异常置信度，增强了检测的鲁棒性。在四个基准数据集上的大量实验表明，SlowFastVAD成功整合了快速和慢速检测器的优势，实现了显著的检测准确性和解释性，同时大幅降低了计算开销，使其非常适合对可靠性要求高的实际VAD应用。

> Video anomaly detection (VAD) aims to identify unexpected events in videos and has wide applications in safety-critical domains. While semi-supervised methods trained on only normal samples have gained traction, they often suffer from high false alarm rates and poor interpretability. Recently, vision-language models (VLMs) have demonstrated strong multimodal reasoning capabilities, offering new opportunities for explainable anomaly detection. However, their high computational cost and lack of domain adaptation hinder real-time deployment and reliability. Inspired by dual complementary pathways in human visual perception, we propose SlowFastVAD, a hybrid framework that integrates a fast anomaly detector with a slow anomaly detector (namely a retrieval augmented generation (RAG) enhanced VLM), to address these limitations. Specifically, the fast detector first provides coarse anomaly confidence scores, and only a small subset of ambiguous segments, rather than the entire video, is further analyzed by the slower yet more interpretable VLM for elaborate detection and reasoning. Furthermore, to adapt VLMs to domain-specific VAD scenarios, we construct a knowledge base including normal patterns based on few normal samples and abnormal patterns inferred by VLMs. During inference, relevant patterns are retrieved and used to augment prompts for anomaly reasoning. Finally, we smoothly fuse the anomaly confidence of fast and slow detectors to enhance robustness of anomaly detection. Extensive experiments on four benchmarks demonstrate that SlowFastVAD effectively combines the strengths of both fast and slow detectors, and achieves remarkable detection accuracy and interpretability with significantly reduced computational overhead, making it well-suited for real-world VAD applications with high reliability requirements.

[Arxiv](https://arxiv.org/abs/2504.10320)