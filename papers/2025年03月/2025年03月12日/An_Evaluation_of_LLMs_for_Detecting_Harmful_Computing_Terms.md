# # 评估大型语言模型检测恶意计算术语的能力
大型语言模型检测恶意计算术语的能力评估

发布时间：2025年03月12日

`LLM应用

摘要讨论了将大型语言模型应用于检测有害和非包容性语言的任务，评估了不同模型在该任务中的表现。这属于LLM的应用层面研究，因此归类为LLM应用。` `人工智能`

> An Evaluation of LLMs for Detecting Harmful Computing Terms

# 摘要

> 营造包容的计算环境需要重视技术环境中有害和非包容性术语的检测。本研究聚焦模型架构对有害语言检测的影响，通过精心整理的技术术语数据库进行评估，每个术语都配有特定的使用场景。我们测试了BERT-base-uncased、RoBERTa large-mnli、Gemini Flash 1.5和2.0、GPT-4、Claude AI Sonnet 3.5、T5-large以及BART-large-mnli等多种语言模型。每个模型均接受标准化提示，以识别64个术语中的有害和非包容性语言。结果显示，Gemini Flash 2.0和Claude AI等解码器模型在细微语境分析方面表现出色，而BERT等编码器模型则在模式识别方面表现强劲，但在分类确定性上存在不足。这些发现对改进自动化检测工具具有重要意义，同时凸显了各模型在技术领域促进包容性沟通时的独特优势和局限性。

> Detecting harmful and non-inclusive terminology in technical contexts is critical for fostering inclusive environments in computing. This study explores the impact of model architecture on harmful language detection by evaluating a curated database of technical terms, each paired with specific use cases. We tested a range of encoder, decoder, and encoder-decoder language models, including BERT-base-uncased, RoBERTa large-mnli, Gemini Flash 1.5 and 2.0, GPT-4, Claude AI Sonnet 3.5, T5-large, and BART-large-mnli. Each model was presented with a standardized prompt to identify harmful and non-inclusive language across 64 terms. Results reveal that decoder models, particularly Gemini Flash 2.0 and Claude AI, excel in nuanced contextual analysis, while encoder models like BERT exhibit strong pattern recognition but struggle with classification certainty. We discuss the implications of these findings for improving automated detection tools and highlight model-specific strengths and limitations in fostering inclusive communication in technical domains.

[Arxiv](https://arxiv.org/abs/2503.09341)