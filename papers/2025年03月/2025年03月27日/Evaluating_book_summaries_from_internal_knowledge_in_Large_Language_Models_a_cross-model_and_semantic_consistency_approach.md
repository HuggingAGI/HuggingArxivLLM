# 从大型语言模型内部知识评估书籍摘要：跨模型与语义一致性方法

发布时间：2025年03月27日

`LLM应用

论文摘要：我们研究了大型语言模型（LLMs）仅凭内部知识生成全面且准确书籍摘要的能力。通过使用多样化的书籍和多种LLM架构，我们探讨这些模型是否能够合成与人类已有解读相契合的有意义叙述。评估采用了以LLM为评估者的范式：每个AI生成的摘要都会与高质量的人类编写摘要进行跨模型对比评估，所有参与的LLMs不仅评估自己的输出，也会评估他人的生成内容。这种评估方法能够识别潜在偏见，例如模型倾向于偏好自己的摘要风格而非他人的。此外，通过ROUGE和BERTScore指标量化人类编写与LLM生成摘要之间的一致性，评估其在语法和语义层面的深度对应。研究结果揭示了不同模型在内容表达和风格偏好上的细微差异，突显了仅依赖内部知识进行摘要任务的优缺点。这些发现有助于深入理解LLMs对事实信息的内部编码方式以及跨模型评估的动态，为构建更强大的自然语言生成系统提供了重要启示。` `自然语言生成` `书籍摘要`

> Evaluating book summaries from internal knowledge in Large Language Models: a cross-model and semantic consistency approach

# 摘要

> 我们研究了大型语言模型（LLMs）仅凭内部知识生成全面且准确书籍摘要的能力。通过使用多样化的书籍和多种LLM架构，我们探讨这些模型是否能够合成与人类已有解读相契合的有意义叙述。评估采用了以LLM为评估者的范式：每个AI生成的摘要都会与高质量的人类编写摘要进行跨模型对比评估，所有参与的LLMs不仅评估自己的输出，也会评估他人的生成内容。这种评估方法能够识别潜在偏见，例如模型倾向于偏好自己的摘要风格而非他人的。此外，通过ROUGE和BERTScore指标量化人类编写与LLM生成摘要之间的一致性，评估其在语法和语义层面的深度对应。研究结果揭示了不同模型在内容表达和风格偏好上的细微差异，突显了仅依赖内部知识进行摘要任务的优缺点。这些发现有助于深入理解LLMs对事实信息的内部编码方式以及跨模型评估的动态，为构建更强大的自然语言生成系统提供了重要启示。

> We study the ability of large language models (LLMs) to generate comprehensive and accurate book summaries solely from their internal knowledge, without recourse to the original text. Employing a diverse set of books and multiple LLM architectures, we examine whether these models can synthesize meaningful narratives that align with established human interpretations. Evaluation is performed with a LLM-as-a-judge paradigm: each AI-generated summary is compared against a high-quality, human-written summary via a cross-model assessment, where all participating LLMs evaluate not only their own outputs but also those produced by others. This methodology enables the identification of potential biases, such as the proclivity for models to favor their own summarization style over others. In addition, alignment between the human-crafted and LLM-generated summaries is quantified using ROUGE and BERTScore metrics, assessing the depth of grammatical and semantic correspondence. The results reveal nuanced variations in content representation and stylistic preferences among the models, highlighting both strengths and limitations inherent in relying on internal knowledge for summarization tasks. These findings contribute to a deeper understanding of LLM internal encodings of factual information and the dynamics of cross-model evaluation, with implications for the development of more robust natural language generative systems.

[Arxiv](https://arxiv.org/abs/2503.21613)