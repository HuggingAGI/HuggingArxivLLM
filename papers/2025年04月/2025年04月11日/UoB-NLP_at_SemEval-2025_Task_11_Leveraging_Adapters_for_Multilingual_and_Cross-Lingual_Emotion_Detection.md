# 伯明翰大学NLP团队在SemEval-2025任务11中，通过利用适配器技术实现多语言与跨语言情感检测

发布时间：2025年04月11日

`LLM应用` `跨语言处理`

> UoB-NLP at SemEval-2025 Task 11: Leveraging Adapters for Multilingual and Cross-Lingual Emotion Detection

# 摘要

> 情感检测在自然语言处理中是一项充满挑战的任务，原因在于人类情感的复杂性和语言的多样性。尽管在高资源语言方面取得了显著进展，但低资源语言的情感检测仍处于探索不足的阶段。在本研究中，我们通过利用基于适配器的微调策略，结合多语言预训练语言模型，来解决多语言和跨语言的情感检测问题。适配器引入少量可训练参数，同时保持预训练模型权重不变，提供了一种参数高效的适应方法。我们尝试了不同的适配器微调策略，包括任务专用适配器、目标语言准备的任务适配器以及基于语言家族的适配器。实验结果显示，目标语言准备的任务适配器在整体性能上表现最佳。在Track A中，我们的团队在提格里尼亚语中排名第七，在基尼亚卢旺达语中排名第八。在Track C中，我们的系统在阿姆哈拉语中排名第三，在奥罗莫语、提格里尼亚语、基尼亚卢旺达语、豪萨语和伊博语中均排名第四。我们的方法在11种语言中超越了大型语言模型的性能，并在另外四种语言中与其持平，尽管我们的模型参数数量要少得多。此外，我们发现基于适配器的模型在保持跨语言迁移能力的同时，相较于对每种语言进行完整的微调，所需的计算资源更少。

> Emotion detection in natural language processing is a challenging task due to the complexity of human emotions and linguistic diversity. While significant progress has been made in high-resource languages, emotion detection in low-resource languages remains underexplored. In this work, we address multilingual and cross-lingual emotion detection by leveraging adapter-based fine-tuning with multilingual pre-trained language models. Adapters introduce a small number of trainable parameters while keeping the pre-trained model weights fixed, offering a parameter-efficient approach to adaptation. We experiment with different adapter tuning strategies, including task-only adapters, target-language-ready task adapters, and language-family-based adapters. Our results show that target-language-ready task adapters achieve the best overall performance, particularly for low-resource African languages with our team ranking 7th for Tigrinya, and 8th for Kinyarwanda in Track A. In Track C, our system ranked 3rd for Amharic, and 4th for Oromo, Tigrinya, Kinyarwanda, Hausa, and Igbo. Our approach outperforms large language models in 11 languages and matches their performance in four others, despite our models having significantly fewer parameters. Furthermore, we find that adapter-based models retain cross-linguistic transfer capabilities while requiring fewer computational resources compared to full fine-tuning for each language.

[Arxiv](https://arxiv.org/abs/2504.08543)