# LLMTrace：面向AI生成文本分类与细粒度定位的语料库

发布时间：2025年09月25日

`LLM应用` `基础理论`

> LLMTrace: A Corpus for Classification and Fine-Grained Localization of AI-Written Text

# 摘要

> 大型语言模型（LLMs）生成的类人文本广泛应用，亟需开发稳健的检测系统。但由于严重缺乏合适的训练数据，相关进展受限：现有数据集多由过时模型生成，且以英文为主，无法应对日益普遍的人机混合创作场景。关键的是，尽管部分数据集涉及混合创作，但均未提供文本中AI生成片段精确定位所需的字符级注释。为填补这些空白，我们推出了LLMTrace——一个用于AI生成文本检测的新型大规模双语（英语和俄语）语料库。该数据集采用多种现代专有及开源LLM构建，旨在支持两项核心任务：传统的全文本二分类（人类vs AI），以及借助字符级注释实现的新型AI生成区间检测任务。我们相信，LLMTrace将成为训练和评估下一代更精细、更实用的AI检测模型的重要资源。项目页面详见\href{https://sweetdream779.github.io/LLMTrace-info/}{iitolstykh/LLMTrace}。

> The widespread use of human-like text from Large Language Models (LLMs) necessitates the development of robust detection systems. However, progress is limited by a critical lack of suitable training data; existing datasets are often generated with outdated models, are predominantly in English, and fail to address the increasingly common scenario of mixed human-AI authorship. Crucially, while some datasets address mixed authorship, none provide the character-level annotations required for the precise localization of AI-generated segments within a text. To address these gaps, we introduce LLMTrace, a new large-scale, bilingual (English and Russian) corpus for AI-generated text detection. Constructed using a diverse range of modern proprietary and open-source LLMs, our dataset is designed to support two key tasks: traditional full-text binary classification (human vs. AI) and the novel task of AI-generated interval detection, facilitated by character-level annotations. We believe LLMTrace will serve as a vital resource for training and evaluating the next generation of more nuanced and practical AI detection models. The project page is available at \href{https://sweetdream779.github.io/LLMTrace-info/}{iitolstykh/LLMTrace}.

[Arxiv](https://arxiv.org/abs/2509.21269)