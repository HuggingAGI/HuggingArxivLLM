# HALLUCINOGEN：评估大型视觉语言模型中对象幻觉的基准

发布时间：2024年12月29日

`LLM应用` `视觉语言模型`

> HALLUCINOGEN: A Benchmark for Evaluating Object Hallucination in Large Visual-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在完成复杂多模态任务时表现出色。但它们仍被对象幻觉所困扰，即对图像中的对象出现错误识别或错误分类的情况。为此，我们提出了 HALLUCINOGEN，这是一种全新的视觉问答（VQA）对象幻觉攻击基准，借助多样的上下文推理提示来评估前沿 LVLMs 中的对象幻觉。我们设计了一系列上下文推理幻觉提示，用于评估 LVLMs 能否在目标图像中准确识别对象，同时让它们执行诸如识别、定位或围绕特定对象进行视觉推理等各类视觉语言任务。另外，我们将该基准拓展到高风险的医疗应用领域，引入了 MED-HALLUCINOGEN，这是针对生物医学领域定制的幻觉攻击，并评估 LVLMs 在医学图像上的幻觉表现，这是一个对精度要求极高的关键领域。最后，我们在多个数据集上对八个 LVLMs 和两种幻觉缓解策略展开了广泛评估，结果表明当前的通用和医疗 LVLMs 仍易遭受幻觉攻击。

> Large Vision-Language Models (LVLMs) have demonstrated remarkable performance in performing complex multimodal tasks. However, they are still plagued by object hallucination: the misidentification or misclassification of objects present in images. To this end, we propose HALLUCINOGEN, a novel visual question answering (VQA) object hallucination attack benchmark that utilizes diverse contextual reasoning prompts to evaluate object hallucination in state-of-the-art LVLMs. We design a series of contextual reasoning hallucination prompts to evaluate LVLMs' ability to accurately identify objects in a target image while asking them to perform diverse visual-language tasks such as identifying, locating or performing visual reasoning around specific objects. Further, we extend our benchmark to high-stakes medical applications and introduce MED-HALLUCINOGEN, hallucination attacks tailored to the biomedical domain, and evaluate the hallucination performance of LVLMs on medical images, a critical area where precision is crucial. Finally, we conduct extensive evaluations of eight LVLMs and two hallucination mitigation strategies across multiple datasets to show that current generic and medical LVLMs remain susceptible to hallucination attacks.

[Arxiv](https://arxiv.org/abs/2412.20622)