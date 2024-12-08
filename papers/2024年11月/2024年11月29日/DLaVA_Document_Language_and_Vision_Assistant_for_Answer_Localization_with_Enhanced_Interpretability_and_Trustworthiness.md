# DLaVA：具备增强的可解释性和可信度的用于答案定位的文档语言和视觉助手

发布时间：2024年11月29日

`LLM应用` `文档处理` `视觉问答`

> DLaVA: Document Language and Vision Assistant for Answer Localization with Enhanced Interpretability and Trustworthiness

# 摘要

> 文档视觉问答（VQA）需要模型解读复杂视觉布局中的文本信息，领会空间关系，从而依据文档图像回答问题。现有的方法通常缺乏可解释性，难以在文档内精准定位答案，这阻碍了用户对响应的验证和对推理过程的理解。此外，诸如平均归一化莱文斯坦相似度（ANLS）之类的标准指标注重文本准确性，却忽视了空间正确性。我们推出了 DLaVA，这是一种为文档 VQA 增强多模态大型语言模型（MLLMs）答案定位能力的新方法。我们的方法将图像注释直接融入 MLLM 流程，使用户能够追踪模型的推理过程，从而提升了可解释性。我们给出了依赖 OCR 和不依赖 OCR 的架构，不依赖 OCR 的方式无需单独的文本识别组件，降低了复杂性。据我们了解，DLaVA 是在多模态 QA 中引入答案定位的首例，在增强用户信任和降低 AI 幻觉风险方面迈出了重要一步。我们的贡献在于通过在有空间标注的视觉内容中确定响应来提高可解释性和可靠性，在 MLLMs 中引入答案定位，提出将 MLLM 与文本检测模块相结合的简化流程，并运用包括交并比（IoU）在内的文本和空间准确性指标进行全面评估。在标准数据集上的实验结果显示，DLaVA 达到了 SOTA 性能，显著增强了模型的透明度和可靠性。我们的方法为文档 VQA 树立了新标杆，凸显了精确答案定位和模型可解释性的至关重要性。

> Document Visual Question Answering (VQA) requires models to interpret textual information within complex visual layouts and comprehend spatial relationships to answer questions based on document images. Existing approaches often lack interpretability and fail to precisely localize answers within the document, hindering users' ability to verify responses and understand the reasoning process. Moreover, standard metrics like Average Normalized Levenshtein Similarity (ANLS) focus on text accuracy but overlook spatial correctness. We introduce DLaVA, a novel method that enhances Multimodal Large Language Models (MLLMs) with answer localization capabilities for Document VQA. Our approach integrates image annotation directly into the MLLM pipeline, improving interpretability by enabling users to trace the model's reasoning. We present both OCR-dependent and OCR-free architectures, with the OCR-free approach eliminating the need for separate text recognition components, thus reducing complexity. To the best of our knowledge, DLaVA is the first approach to introduce answer localization within multimodal QA, marking a significant step forward in enhancing user trust and reducing the risk of AI hallucinations. Our contributions include enhancing interpretability and reliability by grounding responses in spatially annotated visual content, introducing answer localization in MLLMs, proposing a streamlined pipeline that combines an MLLM with a text detection module, and conducting comprehensive evaluations using both textual and spatial accuracy metrics, including Intersection over Union (IoU). Experimental results on standard datasets demonstrate that DLaVA achieves SOTA performance, significantly enhancing model transparency and reliability. Our approach sets a new benchmark for Document VQA, highlighting the critical importance of precise answer localization and model interpretability.

[Arxiv](https://arxiv.org/abs/2412.00151)