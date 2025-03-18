# 谁写的？辨别豪萨语中的机器生成文本与人类创作内容

发布时间：2025年03月17日

`LLM应用` `文本生成`

> Who Wrote This? Identifying Machine vs Human-Generated Text in Hausa

# 摘要

> 大型语言模型（LLMs）的进步使它们在各种任务中表现出色，包括内容生成。然而，大型语言模型的无序使用可能导致恶意行为，例如剽窃、生成和传播虚假新闻，尤其是对资源匮乏的语言而言。现有的大多数机器生成文本检测器都是在英语、法语等高资源语言上进行训练的。在这项研究中，我们开发了首个大规模检测器，能够区分豪萨语的人类生成内容与机器生成内容。我们从七家豪萨语媒体网站上抓取了人类生成的文本，并使用Gemini-2.0闪模型根据这些文章的标题自动生成对应的豪萨语文章。我们对四个预训练的以非洲为中心的模型（AfriTeVa、AfriBERTa、AfroXLMR 和 AfroXLMR-76L）进行了微调，并使用准确率和F1分数评估了它们的性能。AfroXLMR表现最佳，准确率达到99.23%，F1分数为99.21%，证明其在豪萨语文本检测中的有效性。我们的数据集已公开发布，以支持进一步的研究。

> The advancement of large language models (LLMs) has allowed them to be proficient in various tasks, including content generation. However, their unregulated usage can lead to malicious activities such as plagiarism and generating and spreading fake news, especially for low-resource languages. Most existing machine-generated text detectors are trained on high-resource languages like English, French, etc. In this study, we developed the first large-scale detector that can distinguish between human- and machine-generated content in Hausa. We scrapped seven Hausa-language media outlets for the human-generated text and the Gemini-2.0 flash model to automatically generate the corresponding Hausa-language articles based on the human-generated article headlines. We fine-tuned four pre-trained Afri-centric models (AfriTeVa, AfriBERTa, AfroXLMR, and AfroXLMR-76L) on the resulting dataset and assessed their performance using accuracy and F1-score metrics. AfroXLMR achieved the highest performance with an accuracy of 99.23% and an F1 score of 99.21%, demonstrating its effectiveness for Hausa text detection. Our dataset is made publicly available to enable further research.

[Arxiv](https://arxiv.org/abs/2503.13101)