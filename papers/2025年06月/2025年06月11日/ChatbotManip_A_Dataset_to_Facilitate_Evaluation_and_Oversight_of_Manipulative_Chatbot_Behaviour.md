# ChatbotManip：助力评估与监管的聊天机器人操纵行为数据集

发布时间：2025年06月11日

`Agent` `人工智能安全` `聊天机器人`

> ChatbotManip: A Dataset to Facilitate Evaluation and Oversight of Manipulative Chatbot Behaviour

# 摘要

> 本文介绍了 ChatbotManip，一个用于研究聊天机器人操纵行为的创新数据集。数据集中包含聊天机器人与模拟用户之间的对话，机器人被要求展示操纵策略、说服用户达成目标或提供帮助。我们涵盖了从消费者建议到有争议主张论证等多样的操纵情境。每段对话都经过人工标注，既标注了总体操纵行为，也标注了具体策略。研究发现：首先，大型语言模型（LLMs）在明确指示下表现出明显的操纵性，84%的对话中被识别出操纵行为。其次，即使仅被指示为“有说服力”，LLMs也常使用煤气灯效应和恐惧增强等争议策略。最后，BERT+BiLSTM等小型微调模型在检测操纵方面可与Gemini 2.5 pro等大型模型的零样本分类相媲美，但尚未可靠用于实际监督。本研究为人工智能安全提供了重要洞见，强调在LLMs广泛应用于消费级应用时，必须重视操纵风险的管控。

> This paper introduces ChatbotManip, a novel dataset for studying manipulation in Chatbots. It contains simulated generated conversations between a chatbot and a (simulated) user, where the chatbot is explicitly asked to showcase manipulation tactics, persuade the user towards some goal, or simply be helpful. We consider a diverse set of chatbot manipulation contexts, from consumer and personal advice to citizen advice and controversial proposition argumentation. Each conversation is annotated by human annotators for both general manipulation and specific manipulation tactics. Our research reveals three key findings. First, Large Language Models (LLMs) can be manipulative when explicitly instructed, with annotators identifying manipulation in approximately 84\% of such conversations. Second, even when only instructed to be ``persuasive'' without explicit manipulation prompts, LLMs frequently default to controversial manipulative strategies, particularly gaslighting and fear enhancement. Third, small fine-tuned open source models, such as BERT+BiLSTM have a performance comparable to zero-shot classification with larger models like Gemini 2.5 pro in detecting manipulation, but are not yet reliable for real-world oversight. Our work provides important insights for AI safety research and highlights the need of addressing manipulation risks as LLMs are increasingly deployed in consumer-facing applications.

[Arxiv](https://arxiv.org/abs/2506.12090)