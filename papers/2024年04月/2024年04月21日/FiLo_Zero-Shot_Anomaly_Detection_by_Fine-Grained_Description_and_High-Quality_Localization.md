# FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。

发布时间：2024年04月21日

`分类：LLM应用

这篇论文摘要介绍了一种零样本异常检测（ZSAD）方法——FiLo，它利用大型语言模型（LLM）来提供异常的细致描述，并通过自适应学习的文本模板提高检测的精确度和可解释性。此外，FiLo结合了多种技术来更准确地定位异常。由于该方法涉及到使用大型语言模型进行异常检测和定位，因此可以归类为LLM应用。` `异常检测` `跨模态学习`

> FiLo: Zero-Shot Anomaly Detection by Fine-Grained Description and High-Quality Localization

# 摘要

> 零样本异常检测（ZSAD）技术能够在无需任何已知正常或异常样本的情况下直接识别异常。传统方法多依赖于多模态预训练模型的泛化能力，通过比较文本和图像特征的相似度来识别并定位异常。但这些方法在精确描述不同类别中的多样化异常时常常力不从心，且在确定异常具体位置时也存在挑战。为此，我们引入了一种创新的ZSAD方法——FiLo，它由两个核心组件构成：细粒度描述（FG-Des）和高质量定位（HQ-Loc）。FG-Des利用大型语言模型为不同类别提供细致的异常描述，并通过自适应学习的文本模板提升检测的精确度和可解释性。HQ-Loc则结合了初步定位技术Grounding DINO、位置增强文本提示和多尺度多形状跨模态交互模块（MMCI），以更准确地定位各种尺寸和形状的异常。在MVTec和VisA等数据集上的测试显示，FiLo在异常检测和定位方面均有显著提升，尤其在VisA数据集上，图像级AUC达到了83.9%，像素级AUC更是高达95.9%，刷新了行业标准。

> Zero-shot anomaly detection (ZSAD) methods entail detecting anomalies directly without access to any known normal or abnormal samples within the target item categories. Existing approaches typically rely on the robust generalization capabilities of multimodal pretrained models, computing similarities between manually crafted textual features representing "normal" or "abnormal" semantics and image features to detect anomalies and localize anomalous patches. However, the generic descriptions of "abnormal" often fail to precisely match diverse types of anomalies across different object categories. Additionally, computing feature similarities for single patches struggles to pinpoint specific locations of anomalies with various sizes and scales. To address these issues, we propose a novel ZSAD method called FiLo, comprising two components: adaptively learned Fine-Grained Description (FG-Des) and position-enhanced High-Quality Localization (HQ-Loc). FG-Des introduces fine-grained anomaly descriptions for each category using Large Language Models (LLMs) and employs adaptively learned textual templates to enhance the accuracy and interpretability of anomaly detection. HQ-Loc, utilizing Grounding DINO for preliminary localization, position-enhanced text prompts, and Multi-scale Multi-shape Cross-modal Interaction (MMCI) module, facilitates more accurate localization of anomalies of different sizes and shapes. Experimental results on datasets like MVTec and VisA demonstrate that FiLo significantly improves the performance of ZSAD in both detection and localization, achieving state-of-the-art performance with an image-level AUC of 83.9% and a pixel-level AUC of 95.9% on the VisA dataset.

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x1.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x2.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x3.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x4.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x5.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x6.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x7.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x8.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x9.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x10.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x11.png)

![FiLo：一种零样本异常检测方法，它利用细致的描述和精准的定位技术。](../../..//opt/data/Projects/HuggingArxiv/paper_images/2404.13671/x12.png)

[Arxiv](https://arxiv.org/abs/2404.13671)