# 借助绍纳语俚语推进对话式AI：面向数字包容的数据集与混合模型

发布时间：2025年09月10日

`RAG` `教育科技`

> Advancing Conversational AI with Shona Slang: A Dataset and Hybrid Model for Digital Inclusion

# 摘要

> 非洲语言在自然语言处理（NLP）领域代表性严重不足，现有语料库多局限于正式书面语，难以展现日常交流的鲜活魅力。为填补这一空白，本研究聚焦绍纳语——一种在津巴布韦和赞比亚广泛使用的班图语，从匿名社交媒体对话中精心整理出首个绍纳语-英语俚语数据集。该数据集标注了意图、情感、对话行为、语码混合及语气等信息，已在https://github.com/HappymoreMasoka/Working_with_shona-slang公开。我们针对意图识别任务微调了多语言DistilBERT分类器，准确率达96.4%，F1分数为96.3%，模型托管于https://huggingface.co/HappymoreMasoka。该分类器已集成到混合聊天机器人中，结合基于规则的响应与检索增强生成（RAG）技术，可处理特定领域查询，并通过帮助潜在学生了解佩斯大学研究生项目信息的用例验证了效果。定性评估显示，该混合系统在文化相关性和用户参与度上均优于纯RAG基线。通过发布数据集、模型及方法，本研究丰富了非洲语言的NLP资源，助力打造更具包容性和文化共鸣的对话式AI。

> African languages remain underrepresented in natural language processing (NLP), with most corpora limited to formal registers that fail to capture the vibrancy of everyday communication. This work addresses this gap for Shona, a Bantu language spoken in Zimbabwe and Zambia, by introducing a novel Shona--English slang dataset curated from anonymized social media conversations. The dataset is annotated for intent, sentiment, dialogue acts, code-mixing, and tone, and is publicly available at https://github.com/HappymoreMasoka/Working_with_shona-slang. We fine-tuned a multilingual DistilBERT classifier for intent recognition, achieving 96.4\% accuracy and 96.3\% F1-score, hosted at https://huggingface.co/HappymoreMasoka. This classifier is integrated into a hybrid chatbot that combines rule-based responses with retrieval-augmented generation (RAG) to handle domain-specific queries, demonstrated through a use case assisting prospective students with graduate program information at Pace University. Qualitative evaluation shows the hybrid system outperforms a RAG-only baseline in cultural relevance and user engagement. By releasing the dataset, model, and methodology, this work advances NLP resources for African languages, promoting inclusive and culturally resonant conversational AI.

[Arxiv](https://arxiv.org/abs/2509.14249)