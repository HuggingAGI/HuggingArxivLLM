# LLM生成文本的风格变异基准

发布时间：2025年09月12日

`LLM应用` `基础理论`

> Benchmark of stylistic variation in LLM-generated texts

# 摘要

> 本研究探究了人类撰写文本与大型语言模型（LLMs）生成的可比文本之间的语域差异。研究采用Biber的多维分析（MDA），对人类撰写文本样本及与其对应的AI生成文本进行考察，旨在找出LLMs与人类在哪些差异维度上表现得最为显著和系统。研究选用新构建的LLM生成语料库AI-Brown作为文本材料，它与BE-21（代表当代英国英语的Brown系列语料库）具有可比性。鉴于前沿LLMs的训练数据中除英语外其他语言的代表性均不足，研究还利用AI-Koditex语料库和捷克语多维模型，在捷克语上重复了类似分析。研究考察了16个不同设置和提示词条件下的前沿模型，重点关注基础模型与指令微调模型的差异。基于上述研究，团队构建了一个基准，借助该基准可对模型进行相互比较，并在可解释维度上进行排名。

> This study investigates the register variation in texts written by humans and comparable texts produced by large language models (LLMs). Biber's multidimensional analysis (MDA) is applied to a sample of human-written texts and AI-created texts generated to be their counterparts to find the dimensions of variation in which LLMs differ most significantly and most systematically from humans. As textual material, a new LLM-generated corpus AI-Brown is used, which is comparable to BE-21 (a Brown family corpus representing contemporary British English). Since all languages except English are underrepresented in the training data of frontier LLMs, similar analysis is replicated on Czech using AI-Koditex corpus and Czech multidimensional model. Examined were 16 frontier models in various settings and prompts, with emphasis placed on the difference between base models and instruction-tuned models. Based on this, a benchmark is created through which models can be compared with each other and ranked in interpretable dimensions.

[Arxiv](https://arxiv.org/abs/2509.10179)