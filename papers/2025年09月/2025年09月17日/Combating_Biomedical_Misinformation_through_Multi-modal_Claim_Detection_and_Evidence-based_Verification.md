# 通过多模态声明检测与循证验证打击生物医学虚假信息

发布时间：2025年09月17日

`RAG` `医疗健康`

> Combating Biomedical Misinformation through Multi-modal Claim Detection and Evidence-based Verification

# 摘要

> 医疗领域的错误信息——从疫苗犹豫到未经证实的疗法——对公众健康和医疗系统信任度构成威胁。尽管机器学习和自然语言处理已推动自动化事实核查技术进步，但生物医学声明的验证仍面临独特挑战：术语复杂、需领域专业知识支撑，且必须以科学证据为依据。为此，我们提出了一种名为CER（结合证据与推理）的新型生物医学事实核查框架，该框架整合了科学证据检索、基于大型语言模型的推理以及监督式真实性预测。CER将大型语言模型的文本生成能力与高质量生物医学科学证据的先进检索技术相结合，有效降低了幻觉风险，确保生成结果基于可验证的循证来源。在专家标注数据集（HealthFC、BioASQ-7b、SciFact）上的评估结果表明，该框架性能达到当前最优，且跨数据集泛化能力良好。为确保透明度和可复现性，相关代码与数据已公开：https://github.com/PRAISELab-PicusLab/CER

> Misinformation in healthcare, from vaccine hesitancy to unproven treatments, poses risks to public health and trust in medical systems. While machine learning and natural language processing have advanced automated fact-checking, validating biomedical claims remains uniquely challenging due to complex terminology, the need for domain expertise, and the critical importance of grounding in scientific evidence. We introduce CER (Combining Evidence and Reasoning), a novel framework for biomedical fact-checking that integrates scientific evidence retrieval, reasoning via large language models, and supervised veracity prediction. By integrating the text-generation capabilities of large language models with advanced retrieval techniques for high-quality biomedical scientific evidence, CER effectively mitigates the risk of hallucinations, ensuring that generated outputs are grounded in verifiable, evidence-based sources. Evaluations on expert-annotated datasets (HealthFC, BioASQ-7b, SciFact) demonstrate state-of-the-art performance and promising cross-dataset generalization. Code and data are released for transparency and reproducibility: https://github.com/PRAISELab-PicusLab/CER

[Arxiv](https://arxiv.org/abs/2509.13888)