# CBVLM: 无需训练、基于概念的大型视觉语言模型，专为医学图像分类设计，具备可解释性

发布时间：2025年01月21日

`LLM应用

理由：这篇论文主要讨论了如何利用大型视觉语言模型（LVLMs）来解决医疗工作流程中的标注数据稀缺性和系统可解释性不足的问题。具体来说，论文提出了CBVLM方法，通过提示LVLM来判断输入图像中的特定概念，并基于这些概念进行分类。这种方法利用了LVLMs的少样本能力，显著降低了标注成本，并确保了系统的可解释性。因此，这篇论文属于LLM应用类别，因为它主要关注如何将大型语言模型应用于具体的医疗场景中。`

> CBVLM: Training-free Explainable Concept-based Large Vision Language Models for Medical Image Classification

# 摘要

> # 摘要
深度学习在医疗工作流程中的应用面临两大挑战：标注数据的稀缺性和系统的可解释性不足。概念瓶颈模型（CBMs）通过将疾病预测限制在一组预定义且易于理解的概念上，解决了可解释性问题。然而，这种基于概念的解释虽然提高了可解释性，却增加了标注负担。此外，添加新概念时，整个系统需要重新训练。受大型视觉语言模型（LVLMs）在少样本场景中的卓越表现启发，我们提出了CBVLM方法，巧妙应对了上述挑战。CBVLM首先提示LVLM判断输入图像中是否存在特定概念，然后基于这些概念预测对图像进行分类。我们还引入了检索模块，用于选择最佳的上下文学习示例。通过将诊断结果与预测概念绑定，我们确保了可解释性；同时，利用LVLMs的少样本能力，大幅降低了标注成本。我们在四个医疗数据集和十二个LVLMs（包括通用和医疗专用）上进行了广泛实验，结果表明CBVLM在无需训练、仅使用少量标注示例的情况下，始终优于CBMs和特定任务的监督方法。更多信息请访问项目页面：https://cristianopatricio.github.io/CBVLM/。

> The main challenges limiting the adoption of deep learning-based solutions in medical workflows are the availability of annotated data and the lack of interpretability of such systems. Concept Bottleneck Models (CBMs) tackle the latter by constraining the final disease prediction on a set of predefined and human-interpretable concepts. However, the increased interpretability achieved through these concept-based explanations implies a higher annotation burden. Moreover, if a new concept needs to be added, the whole system needs to be retrained. Inspired by the remarkable performance shown by Large Vision-Language Models (LVLMs) in few-shot settings, we propose a simple, yet effective, methodology, CBVLM, which tackles both of the aforementioned challenges. First, for each concept, we prompt the LVLM to answer if the concept is present in the input image. Then, we ask the LVLM to classify the image based on the previous concept predictions. Moreover, in both stages, we incorporate a retrieval module responsible for selecting the best examples for in-context learning. By grounding the final diagnosis on the predicted concepts, we ensure explainability, and by leveraging the few-shot capabilities of LVLMs, we drastically lower the annotation cost. We validate our approach with extensive experiments across four medical datasets and twelve LVLMs (both generic and medical) and show that CBVLM consistently outperforms CBMs and task-specific supervised methods without requiring any training and using just a few annotated examples. More information on our project page: https://cristianopatricio.github.io/CBVLM/.

[Arxiv](https://arxiv.org/abs/2501.12266)