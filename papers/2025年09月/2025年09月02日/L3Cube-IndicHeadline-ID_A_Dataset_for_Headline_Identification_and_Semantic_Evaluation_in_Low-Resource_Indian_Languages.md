# L3Cube-IndicHeadline-ID：低资源印度语言标题识别与语义评估数据集

发布时间：2025年09月02日

`RAG` `基础理论`

> L3Cube-IndicHeadline-ID: A Dataset for Headline Identification and Semantic Evaluation in Low-Resource Indian Languages

# 摘要

> 在自然语言处理（NLP）领域，低资源语言的语义评估一直是一大难题。句子转换器在高资源语言场景中表现优异，但在印度语言中，由于缺乏高质量的基准数据集，其效果尚未得到充分研究。为填补这一空白，我们提出了L3Cube-IndicHeadline-ID——一个精心构建的标题识别数据集，覆盖十种低资源印度语言（马拉地语、印地语、泰米尔语、古吉拉特语、奥里亚语、卡纳达语、马拉雅拉姆语、旁遮普语、泰卢固语、孟加拉语）及英语。每种语言包含20,000篇新闻文章，每篇文章均配有四种标题变体：原始标题、语义相似标题、词汇相似标题和无关标题，旨在精准测试细粒度语义理解能力。该任务要求通过文章与标题的相似度从选项中选出正确标题。我们采用余弦相似度对多种句子转换器（包括多语言模型和特定语言模型）进行了基准测试，结果显示多语言模型表现稳定，而特定语言模型的效果则参差不齐。随着相似度模型在检索增强生成（RAG）管道中的应用日益广泛，该数据集也成为评估和改进此类应用中语义理解能力的重要资源。此外，它还可改用于多选题问答、标题分类或其他针对大型语言模型（LLMs）的特定任务评估，堪称印度语言NLP研究的多功能基准。该数据集已在https://github.com/l3cube-pune/indic-nlp公开。

> Semantic evaluation in low-resource languages remains a major challenge in NLP. While sentence transformers have shown strong performance in high-resource settings, their effectiveness in Indic languages is underexplored due to a lack of high-quality benchmarks. To bridge this gap, we introduce L3Cube-IndicHeadline-ID, a curated headline identification dataset spanning ten low-resource Indic languages: Marathi, Hindi, Tamil, Gujarati, Odia, Kannada, Malayalam, Punjabi, Telugu, Bengali and English. Each language includes 20,000 news articles paired with four headline variants: the original, a semantically similar version, a lexically similar version, and an unrelated one, designed to test fine-grained semantic understanding. The task requires selecting the correct headline from the options using article-headline similarity. We benchmark several sentence transformers, including multilingual and language-specific models, using cosine similarity. Results show that multilingual models consistently perform well, while language-specific models vary in effectiveness. Given the rising use of similarity models in Retrieval-Augmented Generation (RAG) pipelines, this dataset also serves as a valuable resource for evaluating and improving semantic understanding in such applications. Additionally, the dataset can be repurposed for multiple-choice question answering, headline classification, or other task-specific evaluations of LLMs, making it a versatile benchmark for Indic NLP. The dataset is shared publicly at https://github.com/l3cube-pune/indic-nlp

[Arxiv](https://arxiv.org/abs/2509.02503)