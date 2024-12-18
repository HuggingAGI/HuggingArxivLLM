# 一个用于癌症诊断的知识增强型病理学视觉语言基础模型

发布时间：2024年12月17日

`LLM应用` `癌症诊断`

> A Knowledge-enhanced Pathology Vision-language Foundation Model for Cancer Diagnosis

# 摘要

> 深度学习助力开发出了针对不同疾病和患者群体的各类病理任务的高度稳健的基础模型。在这些模型里，视觉语言预训练借助大规模的配对数据来对齐病理图像和文本的嵌入空间，为下游任务提供了全新的零样本范式。然而，现有的模型多为数据驱动，缺少特定领域知识的融入，这限制了它们在癌症诊断方面的表现，尤其是针对罕见肿瘤亚型。为克服这一局限，我们构建了知识增强病理学（KEEP）基础模型，利用疾病知识来推动视觉语言预训练。具体而言，我们先是构建了一个涵盖 11454 种人类疾病、拥有 139143 个疾病属性（包括同义词、定义和上位关系）的疾病知识图谱（KG）。接着，我们将数百万公开可用的杂乱病理图像 - 文本对系统地重新整理为 143K 个通过疾病 KG 的层级关系相连接的结构良好的语义组。为获取更精细的图像和文本表征，我们提出了一种新颖的知识增强视觉语言预训练方法，将疾病知识融入到层级语义组内的对齐中，而非非结构化的图像 - 文本对。在超过 14000 个全切片图像（WSIs）的 18 个不同基准上进行验证，KEEP 在零样本癌症诊断任务中达到了最先进的性能。值得注意的是，在癌症检测方面，KEEP 在 7 种癌症类型中特异性为 95.0％时，平均灵敏度达 89.8％。在癌症亚型分类中，KEEP 对 30 种罕见脑癌进行亚型分类时，中位平衡准确率达 0.456，显示出其在诊断罕见肿瘤方面强大的泛化能力。

> Deep learning has enabled the development of highly robust foundation models for various pathological tasks across diverse diseases and patient cohorts. Among these models, vision-language pre-training, which leverages large-scale paired data to align pathology image and text embedding spaces, and provides a novel zero-shot paradigm for downstream tasks. However, existing models have been primarily data-driven and lack the incorporation of domain-specific knowledge, which limits their performance in cancer diagnosis, especially for rare tumor subtypes. To address this limitation, we establish a Knowledge-enhanced Pathology (KEEP) foundation model that harnesses disease knowledge to facilitate vision-language pre-training. Specifically, we first construct a disease knowledge graph (KG) that covers 11,454 human diseases with 139,143 disease attributes, including synonyms, definitions, and hypernym relations. We then systematically reorganize the millions of publicly available noisy pathology image-text pairs, into 143K well-structured semantic groups linked through the hierarchical relations of the disease KG. To derive more nuanced image and text representations, we propose a novel knowledge-enhanced vision-language pre-training approach that integrates disease knowledge into the alignment within hierarchical semantic groups instead of unstructured image-text pairs. Validated on 18 diverse benchmarks with more than 14,000 whole slide images (WSIs), KEEP achieves state-of-the-art performance in zero-shot cancer diagnostic tasks. Notably, for cancer detection, KEEP demonstrates an average sensitivity of 89.8% at a specificity of 95.0% across 7 cancer types. For cancer subtyping, KEEP achieves a median balanced accuracy of 0.456 in subtyping 30 rare brain cancers, indicating strong generalizability for diagnosing rare tumors.

[Arxiv](https://arxiv.org/abs/2412.13126)