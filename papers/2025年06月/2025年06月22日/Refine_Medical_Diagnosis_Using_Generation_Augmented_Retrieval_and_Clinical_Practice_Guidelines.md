# 基于生成增强检索和临床实践指南优化医学诊断

发布时间：2025年06月22日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）与临床实践指南（CPGs）相结合，以改进医学诊断。GARMLE-G框架展示了LLM在医疗领域的具体应用，特别是在提升诊断的准确性和实用性方面。因此，这篇论文属于LLM应用类别。` `临床诊断`

> Refine Medical Diagnosis Using Generation Augmented Retrieval and Clinical Practice Guidelines

# 摘要

> 当前医学语言模型通常从电子健康记录（EHRs）预测基于ICD代码的诊断，但ICD代码无法反映临床医生诊断时的细致推理过程。临床医生整合患者数据并参考临床实践指南（CPGs）做出决策，这种差异限制了现有模型的临床应用价值。

我们提出GARMLE-G框架，将医学语言模型与权威CPGs相结合，实现无幻觉输出。该框架通过直接检索权威指南内容，避免依赖模型生成文本，具有三大核心优势：（1）结合LLM预测与EHR数据生成语义查询；（2）通过嵌入相似度检索相关知识片段；（3）融合指南内容与模型输出生成临床建议。

在高血压诊断任务中，GARMLE-G原型系统在检索精度、语义相关性和指南遵循性方面超越传统RAG方法，同时保持轻量化架构，适合医疗场景部署。这项研究为医学语言模型与临床实践结合提供了创新解决方案，具有广阔应用前景。

> Current medical language models, adapted from large language models (LLMs), typically predict ICD code-based diagnosis from electronic health records (EHRs) because these labels are readily available. However, ICD codes do not capture the nuanced, context-rich reasoning clinicians use for diagnosis. Clinicians synthesize diverse patient data and reference clinical practice guidelines (CPGs) to make evidence-based decisions. This misalignment limits the clinical utility of existing models. We introduce GARMLE-G, a Generation-Augmented Retrieval framework that grounds medical language model outputs in authoritative CPGs. Unlike conventional Retrieval-Augmented Generation based approaches, GARMLE-G enables hallucination-free outputs by directly retrieving authoritative guideline content without relying on model-generated text. It (1) integrates LLM predictions with EHR data to create semantically rich queries, (2) retrieves relevant CPG knowledge snippets via embedding similarity, and (3) fuses guideline content with model output to generate clinically aligned recommendations. A prototype system for hypertension diagnosis was developed and evaluated on multiple metrics, demonstrating superior retrieval precision, semantic relevance, and clinical guideline adherence compared to RAG-based baselines, while maintaining a lightweight architecture suitable for localized healthcare deployment. This work provides a scalable, low-cost, and hallucination-free method for grounding medical language models in evidence-based clinical practice, with strong potential for broader clinical deployment.

[Arxiv](https://arxiv.org/abs/2506.21615)