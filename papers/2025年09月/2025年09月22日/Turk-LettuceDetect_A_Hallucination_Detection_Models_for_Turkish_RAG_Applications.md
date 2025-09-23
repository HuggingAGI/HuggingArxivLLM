# Turk-LettuceDetect：面向土耳其语RAG应用的幻觉检测模型

发布时间：2025年09月22日

`RAG` `基础理论`

> Turk-LettuceDetect: A Hallucination Detection Models for Turkish RAG Applications

# 摘要

> 大型语言模型（LLMs）的广泛应用一直受限于其幻觉问题——它们常常生成看似合理却与事实不符的信息。尽管检索增强生成（RAG）系统尝试通过将回答锚定在外部知识中来解决这一问题，但幻觉仍是一个顽疾，尤其在土耳其语这类形态复杂的低资源语言中。本文提出Turk-LettuceDetect——首个专为土耳其语RAG应用设计的幻觉检测模型套件。基于LettuceDetect框架，我们将幻觉检测构建为token级分类任务，并对三种不同的编码器架构进行了微调：土耳其语专用的ModernBERT、TurkEmbed4STS以及多语言的EuroBERT。这些模型在机器翻译的RAGTruth基准数据集上训练——该数据集涵盖问答、数据到文本生成和摘要任务，共包含17,790个实例。实验结果显示，基于ModernBERT的模型在完整测试集上F1分数达到0.7266，在结构化任务上表现尤为突出。这些模型在支持长达8192个token的长上下文时仍保持计算效率，非常适合实时部署。对比分析发现，尽管最先进的LLMs召回率很高，但由于过度生成幻觉内容，精确率却很低，这凸显了专用检测机制的必要性。通过开源我们的模型和翻译数据集，这项工作填补了多语言NLP领域的关键空白，为开发土耳其语及其他语言的更可靠、更可信AI应用奠定了基础。

> The widespread adoption of Large Language Models (LLMs) has been hindered by their tendency to hallucinate, generating plausible but factually incorrect information. While Retrieval-Augmented Generation (RAG) systems attempt to address this issue by grounding responses in external knowledge, hallucination remains a persistent challenge, particularly for morphologically complex, low-resource languages like Turkish. This paper introduces Turk-LettuceDetect, the first suite of hallucination detection models specifically designed for Turkish RAG applications. Building on the LettuceDetect framework, we formulate hallucination detection as a token-level classification task and fine-tune three distinct encoder architectures: a Turkish-specific ModernBERT, TurkEmbed4STS, and multilingual EuroBERT. These models were trained on a machine-translated version of the RAGTruth benchmark dataset containing 17,790 instances across question answering, data-to-text generation, and summarization tasks. Our experimental results show that the ModernBERT-based model achieves an F1-score of 0.7266 on the complete test set, with particularly strong performance on structured tasks. The models maintain computational efficiency while supporting long contexts up to 8,192 tokens, making them suitable for real-time deployment. Comparative analysis reveals that while state-of-the-art LLMs demonstrate high recall, they suffer from low precision due to over-generation of hallucinated content, underscoring the necessity of specialized detection mechanisms. By releasing our models and translated dataset, this work addresses a critical gap in multilingual NLP and establishes a foundation for developing more reliable and trustworthy AI applications for Turkish and other languages.

[Arxiv](https://arxiv.org/abs/2509.17671)