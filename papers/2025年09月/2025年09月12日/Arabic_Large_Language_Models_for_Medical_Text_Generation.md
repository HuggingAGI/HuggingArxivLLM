# 面向医学文本生成的阿拉伯语大型语言模型

发布时间：2025年09月12日

`LLM应用` `医疗健康`

> Arabic Large Language Models for Medical Text Generation

# 摘要

> 高效的医院管理系统（HMS）在全球都不可或缺，能有效应对过度拥挤、资源紧张及紧急医疗服务可及性低等难题。然而现有方法常无法提供准确、实时的医疗建议，尤其在处理不规则输入和小众语言时。为此，本研究提出通过微调大型语言模型（LLMs）来生成阿拉伯语医疗文本的新方法。该系统专为患者设计，可根据用户输入提供精准的医疗建议、诊断结果、药物推荐及治疗方案。研究过程中，团队从社交媒体平台收集了独特数据集，捕捉患者与医生间真实的医疗对话。这些包含患者主诉和医生建议的数据，经清洗与预处理后能适配多种阿拉伯方言。通过微调Mistral-7B-Instruct-v0.2、LLaMA-2-7B及GPT-2 Medium等前沿生成模型，系统生成可靠医疗文本的能力得到优化。评估显示，微调后的Mistral-7B模型性能最佳，其BERT（来自Transformer的双向编码器表示）评分中，精确率、召回率和F1值的平均值分别达68.5%、69.08%和68.5%。对比基准测试与定性评估进一步证实，该系统能针对非正式输入生成连贯且贴合需求的医疗回复。这项研究凸显了生成式AI在推动HMS发展中的潜力，为全球医疗挑战提供了可扩展、适应性强的解决方案，尤其适用于语言和文化多元的场景。

> Efficient hospital management systems (HMS) are critical worldwide to address challenges such as overcrowding, limited resources, and poor availability of urgent health care. Existing methods often lack the ability to provide accurate, real-time medical advice, particularly for irregular inputs and underrepresented languages. To overcome these limitations, this study proposes an approach that fine-tunes large language models (LLMs) for Arabic medical text generation. The system is designed to assist patients by providing accurate medical advice, diagnoses, drug recommendations, and treatment plans based on user input. The research methodology required the collection of a unique dataset from social media platforms, capturing real-world medical conversations between patients and doctors. The dataset, which includes patient complaints together with medical advice, was properly cleaned and preprocessed to account for multiple Arabic dialects. Fine-tuning state-of-the-art generative models, such as Mistral-7B-Instruct-v0.2, LLaMA-2-7B, and GPT-2 Medium, optimized the system's ability to generate reliable medical text. Results from evaluations indicate that the fine-tuned Mistral-7B model outperformed the other models, achieving average BERT (Bidirectional Encoder Representations from Transformers) Score values in precision, recall, and F1-scores of 68.5\%, 69.08\%, and 68.5\%, respectively. Comparative benchmarking and qualitative assessments validate the system's ability to produce coherent and relevant medical replies to informal input. This study highlights the potential of generative artificial intelligence (AI) in advancing HMS, offering a scalable and adaptable solution for global healthcare challenges, especially in linguistically and culturally diverse environments.

[Arxiv](https://arxiv.org/abs/2509.10095)