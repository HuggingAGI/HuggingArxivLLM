# 利用指令微调的大型语言模型和Transformer架构进行AI生成文本检测

发布时间：2025年07月07日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在生成文本中的应用及其滥用情况，并研究了检测这些生成文本的方法，属于LLM的实际应用分析和对策。` `网络安全` `文本检测`

> AI Generated Text Detection Using Instruction Fine-tuned Large Language and Transformer-Based Models

# 摘要

> 大型语言模型（LLMs）不仅能够生成连贯且上下文相关的文本，还能产出与人类写作极为相似的内容。它们能够适应各种文体和风格，生成语法正确且语义丰富的内容。然而，最近LLMs被滥用以生成高度逼真的钓鱼邮件、传播虚假新闻、编写自动化网络犯罪的代码以及撰写欺诈性科学文章。此外，在许多实际应用中，生成的内容风格、主题以及生成模型事先并不为人所知。人工智能（AI）生成文本的日益普遍和复杂化，使得检测它们变得越来越具有挑战性。人们尝试使用语言学、统计学、机器学习和基于集成的方法来区分机器生成文本与人类撰写的内容。本研究主要聚焦于两个核心目标：任务A，区分人类撰写文本与机器生成文本；任务B，识别具体负责生成文本的LLM模型。这两个任务均基于对生成式预训练变换器（GPT_4o-mini）、大型语言模型Meta AI（LLaMA）3 8B以及双向编码器表示变换器（BERT）的微调。GPT_4o-mini和BERT模型的微调版本在任务A中达到了0.9547的准确率，在任务B中达到了0.4698的准确率。

> Large Language Models (LLMs) possess an extraordinary capability to produce text that is not only coherent and contextually relevant but also strikingly similar to human writing. They adapt to various styles and genres, producing content that is both grammatically correct and semantically meaningful. Recently, LLMs have been misused to create highly realistic phishing emails, spread fake news, generate code to automate cyber crime, and write fraudulent scientific articles. Additionally, in many real-world applications, the generated content including style and topic and the generator model are not known beforehand. The increasing prevalence and sophistication of artificial intelligence (AI)-generated texts have made their detection progressively more challenging. Various attempts have been made to distinguish machine-generated text from human-authored content using linguistic, statistical, machine learning, and ensemble-based approaches. This work focuses on two primary objectives Task-A, which involves distinguishing human-written text from machine-generated text, and Task-B, which attempts to identify the specific LLM model responsible for the generation. Both of these tasks are based on fine tuning of Generative Pre-trained Transformer (GPT_4o-mini), Large Language Model Meta AI (LLaMA) 3 8B, and Bidirectional Encoder Representations from Transformers (BERT). The fine-tuned version of GPT_4o-mini and the BERT model has achieved accuracies of 0.9547 for Task-A and 0.4698 for Task-B.

[Arxiv](https://arxiv.org/abs/2507.05157)