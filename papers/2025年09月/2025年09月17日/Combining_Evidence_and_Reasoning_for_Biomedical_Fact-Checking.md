# 融合证据与推理：助力生物医学事实核查

发布时间：2025年09月17日

`RAG` `医疗健康`

> Combining Evidence and Reasoning for Biomedical Fact-Checking

# 摘要

> 医疗领域的错误信息——从疫苗犹豫到未经证实的疗法——不仅威胁公众健康，还损害对医疗系统的信任。尽管机器学习和自然语言处理推动了自动化事实核查的进步，但生物医学声明的验证仍独具挑战：术语复杂、需领域专业知识，且必须以科学证据为坚实基础。为此，我们提出了CER（结合证据与推理）——一种新型生物医学事实核查框架，它整合了科学证据检索、基于大型语言模型的推理以及有监督的真实性预测。CER将大型语言模型的文本生成能力与高质量生物医学科学证据的先进检索技术相结合，有效降低了幻觉风险，确保生成内容有可验证的循证来源作为支撑。在专家标注的数据集（HealthFC、BioASQ-7b、SciFact）上的评估表明，CER实现了最先进的性能，并展现出良好的跨数据集泛化能力。为确保透明度和可复现性，我们已开源相关代码和数据：https: //github.com/PRAISELab-PicusLab/CER。

> Misinformation in healthcare, from vaccine hesitancy to unproven treatments, poses risks to public health and trust in medical systems. While machine learning and natural language processing have advanced automated fact-checking, validating biomedical claims remains uniquely challenging due to complex terminology, the need for domain expertise, and the critical importance of grounding in scientific evidence. We introduce CER (Combining Evidence and Reasoning), a novel framework for biomedical fact-checking that integrates scientific evidence retrieval, reasoning via large language models, and supervised veracity prediction. By integrating the text-generation capabilities of large language models with advanced retrieval techniques for high-quality biomedical scientific evidence, CER effectively mitigates the risk of hallucinations, ensuring that generated outputs are grounded in verifiable, evidence-based sources. Evaluations on expert-annotated datasets (HealthFC, BioASQ-7b, SciFact) demonstrate state-of-the-art performance and promising cross-dataset generalization. Code and data are released for transparency and reproducibility: https: //github.com/PRAISELab-PicusLab/CER.

[Arxiv](https://arxiv.org/abs/2509.13879)