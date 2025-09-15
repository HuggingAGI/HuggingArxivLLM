# 借助合成数据扩展阿拉伯语医疗聊天机器人：通过合成患者记录提升生成式人工智能

发布时间：2025年09月12日

`LLM应用` `医疗健康`

> Scaling Arabic Medical Chatbots Using Synthetic Data: Enhancing Generative AI with Synthetic Patient Records

# 摘要

> 大规模高质量标注数据集的匮乏，严重制约了阿拉伯语医疗聊天机器人的发展。尽管已有研究从社交媒体构建了含20,000条阿拉伯语医患对话的数据集，用于微调大型语言模型（LLMs），但模型的可扩展性与泛化能力仍显不足。本研究提出一种可扩展的合成数据增强策略，将训练语料库扩展至100,000条记录。我们借助先进的生成式AI系统ChatGPT-4o与Gemini 2.5 Pro，以原始数据集结构为基础，生成了80,000条上下文相关、医学逻辑连贯的合成问答对。这些合成样本经语义过滤、人工验证后，被整合至训练流程。我们微调了五个大型语言模型（包括Mistral-7B和AraGPT2），并通过BERTScore指标与专家定性评估相结合的方式，对其性能进行了评测。为深入分析不同合成数据源的有效性，我们开展了消融研究，对ChatGPT-4o与Gemini生成的数据进行了独立对比。结果显示，在所有模型中，ChatGPT-4o生成的数据均能持续提升F1分数，并显著减少幻觉现象。综上，本研究证实，合成数据增强可作为低资源医疗NLP领域中提升特定领域语言模型性能的实用方案，这为构建更具包容性、可扩展性和准确性的阿拉伯语医疗聊天机器人系统奠定了基础。

> The development of medical chatbots in Arabic is significantly constrained by the scarcity of large-scale, high-quality annotated datasets. While prior efforts compiled a dataset of 20,000 Arabic patient-doctor interactions from social media to fine-tune large language models (LLMs), model scalability and generalization remained limited. In this study, we propose a scalable synthetic data augmentation strategy to expand the training corpus to 100,000 records. Using advanced generative AI systems ChatGPT-4o and Gemini 2.5 Pro we generated 80,000 contextually relevant and medically coherent synthetic question-answer pairs grounded in the structure of the original dataset. These synthetic samples were semantically filtered, manually validated, and integrated into the training pipeline. We fine-tuned five LLMs, including Mistral-7B and AraGPT2, and evaluated their performance using BERTScore metrics and expert-driven qualitative assessments. To further analyze the effectiveness of synthetic sources, we conducted an ablation study comparing ChatGPT-4o and Gemini-generated data independently. The results showed that ChatGPT-4o data consistently led to higher F1-scores and fewer hallucinations across all models. Overall, our findings demonstrate the viability of synthetic augmentation as a practical solution for enhancing domain-specific language models in-low resource medical NLP, paving the way for more inclusive, scalable, and accurate Arabic healthcare chatbot systems.

[Arxiv](https://arxiv.org/abs/2509.10108)