# # UniBiomed：一款专为医学影像解读打造的通用型基础模型

发布时间：2025年04月30日

`LLM应用

摘要中的论文主要探讨了大型语言模型（LLMs）在生物医学图像分析中的应用，展示了其在多模态数据处理和实际临床任务中的有效性。因此，这篇论文属于LLM应用类别。` `生物医学` `图像分析`

> UniBiomed: A Universal Foundation Model for Grounded Biomedical Image Interpretation

# 摘要

> 多模态生物医学图像解释开启了生物医学图像分析的全新机遇。传统AI方法通常采用独立的训练流程：大型语言模型（LLMs）用于生成临床文本，分割模型用于提取目标区域。这种方式不仅导致实际部署僵化，也未能充分利用整体生物医学信息。为此，我们推出UniBiomed——首个专注于基于图像的生物医学解释的通用基础模型。

UniBiomed创新性地融合了多模态大型语言模型（MLLM）与SAM分割模型，实现了临床文本生成与生物医学对象分割的有效统一，从而支持基于图像的解释任务。通过这种方式，UniBiomed能够处理跨十大不同生物医学成像模式的广泛任务。

为了开发UniBiomed，我们整理了一个包含十大成像模式下超过2700万个图像、标注和文本描述三元组的大型数据集。在84个内部和外部数据集上的广泛验证表明，UniBiomed在分割、疾病识别、区域感知诊断、视觉问答和报告生成等方面均达到了目前最优的性能水平。

与依赖临床专家预先诊断图像并手动创建精确文本或视觉提示的先前模型不同，UniBiomed能够为生物医学图像分析提供自动化、端到端的基于图像的解释。这标志着临床工作流程中的一项范式转变，将显著提升诊断效率。综上所述，UniBiomed代表了生物医学AI领域的一项重要突破，通过强大的基于图像的解释能力，推动了生物医学图像分析的准确性和效率的提升。


> Multi-modal interpretation of biomedical images opens up novel opportunities in biomedical image analysis. Conventional AI approaches typically rely on disjointed training, i.e., Large Language Models (LLMs) for clinical text generation and segmentation models for target extraction, which results in inflexible real-world deployment and a failure to leverage holistic biomedical information. To this end, we introduce UniBiomed, the first universal foundation model for grounded biomedical image interpretation. UniBiomed is based on a novel integration of Multi-modal Large Language Model (MLLM) and Segment Anything Model (SAM), which effectively unifies the generation of clinical texts and the segmentation of corresponding biomedical objects for grounded interpretation. In this way, UniBiomed is capable of tackling a wide range of biomedical tasks across ten diverse biomedical imaging modalities. To develop UniBiomed, we curate a large-scale dataset comprising over 27 million triplets of images, annotations, and text descriptions across ten imaging modalities. Extensive validation on 84 internal and external datasets demonstrated that UniBiomed achieves state-of-the-art performance in segmentation, disease recognition, region-aware diagnosis, visual question answering, and report generation. Moreover, unlike previous models that rely on clinical experts to pre-diagnose images and manually craft precise textual or visual prompts, UniBiomed can provide automated and end-to-end grounded interpretation for biomedical image analysis. This represents a novel paradigm shift in clinical workflows, which will significantly improve diagnostic efficiency. In summary, UniBiomed represents a novel breakthrough in biomedical AI, unlocking powerful grounded interpretation capabilities for more accurate and efficient biomedical image analysis.

[Arxiv](https://arxiv.org/abs/2504.21336)