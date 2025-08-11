# # 幻觉与真相：大型语言模型的事实核查与评估综述

发布时间：2025年08月05日

`LLM应用` `事实核查` `内容评估`

> Hallucination to Truth: A Review of Fact-Checking and Factuality Evaluation in Large Language Models

# 摘要

> 大型语言模型（LLMs）经过大规模多样化网络语料库训练，这些语料库通常包含不准确或误导性内容。因此，LLMs可能生成错误信息，这就需要强大的事实核查能力。本文系统分析了如何评估LLM生成内容的事实准确性，探讨了幻觉、数据集限制和评估指标可靠性等关键挑战。文章强调了构建整合先进提示策略、领域特定微调和基于检索增强生成（RAG）方法的事实核查框架的重要性。本文提出了五个研究问题，用于分析2020年至2025年的最新文献，重点关注评估方法和缓解技术。文章还探讨了指令微调、多智能体推理以及通过RAG框架访问外部知识的作用。关键发现揭示了现有指标的局限性、基于验证外部证据 grounding 输出的价值，以及为提高事实一致性进行领域特定定制的重要性。总体而言，本文强调了构建不仅准确、可解释，而且针对特定领域事实核查进行定制的LLMs的重要性。这些见解推动了研究向更值得信赖和语境感知的语言模型发展。


> Large Language Models (LLMs) are trained on vast and diverse internet corpora that often include inaccurate or misleading content. Consequently, LLMs can generate misinformation, making robust fact-checking essential. This review systematically analyzes how LLM-generated content is evaluated for factual accuracy by exploring key challenges such as hallucinations, dataset limitations, and the reliability of evaluation metrics. The review emphasizes the need for strong fact-checking frameworks that integrate advanced prompting strategies, domain-specific fine-tuning, and retrieval-augmented generation (RAG) methods. It proposes five research questions that guide the analysis of the recent literature from 2020 to 2025, focusing on evaluation methods and mitigation techniques. The review also discusses the role of instruction tuning, multi-agent reasoning, and external knowledge access via RAG frameworks. Key findings highlight the limitations of current metrics, the value of grounding outputs with validated external evidence, and the importance of domain-specific customization to improve factual consistency. Overall, the review underlines the importance of building LLMs that are not only accurate and explainable but also tailored for domain-specific fact-checking. These insights contribute to the advancement of research toward more trustworthy and context-aware language models.

[Arxiv](https://arxiv.org/abs/2508.03860)