# FairTranslate: 一个通过克服性别二元性来评估机器翻译中性别偏见问题的英法语数据集

发布时间：2025年04月22日

`LLM应用` `性别研究`

> FairTranslate: An English-French Dataset for Gender Bias Evaluation in Machine Translation by Overcoming Gender Binarity

# 摘要

> 大型语言模型（LLMs）被广泛应用于翻译领域，但在处理包容性语言时表现欠佳，例如涉及单数'他们'或公平语言协议的文本。鉴于这些挑战横跨计算与社科领域，我们亟需一个扎实的框架来全面评估LLMs的包容性翻译能力。

    本文推出FairTranslate，一个全新的人工标注数据集，专注于评估英法翻译中的非二元性别偏见。该数据集包含2418对英法句子，涵盖职业主题，并标注了职业刻板印象对齐、语法性别模糊性和真实性别标签（男/女/包容）等丰富元数据。

    我们对四个主流LLMs（Gemma2-2B、Mistral-7B、Llama3.1-8B、Llama3.3-70B）进行了全面测试，采用了多种提示策略。结果显示，LLMs在性别表达方面存在明显偏见，凸显了机器翻译实现公平性的持续挑战。这些发现强调了开发专门策略和干预措施的重要性，以确保基于LLMs的翻译系统能够公平、包容地使用语言。

    FairTranslate数据集已在Hugging Face平台公开，实验代码亦可在GitHub上获取。
    

> Large Language Models (LLMs) are increasingly leveraged for translation tasks but often fall short when translating inclusive language -- such as texts containing the singular 'they' pronoun or otherwise reflecting fair linguistic protocols. Because these challenges span both computational and societal domains, it is imperative to critically evaluate how well LLMs handle inclusive translation with a well-founded framework.
  This paper presents FairTranslate, a novel, fully human-annotated dataset designed to evaluate non-binary gender biases in machine translation systems from English to French. FairTranslate includes 2418 English-French sentence pairs related to occupations, annotated with rich metadata such as the stereotypical alignment of the occupation, grammatical gender indicator ambiguity, and the ground-truth gender label (male, female, or inclusive).
  We evaluate four leading LLMs (Gemma2-2B, Mistral-7B, Llama3.1-8B, Llama3.3-70B) on this dataset under different prompting procedures. Our results reveal substantial biases in gender representation across LLMs, highlighting persistent challenges in achieving equitable outcomes in machine translation. These findings underscore the need for focused strategies and interventions aimed at ensuring fair and inclusive language usage in LLM-based translation systems.
  We make the FairTranslate dataset publicly available on Hugging Face, and disclose the code for all experiments on GitHub.

[Arxiv](https://arxiv.org/abs/2504.15941)