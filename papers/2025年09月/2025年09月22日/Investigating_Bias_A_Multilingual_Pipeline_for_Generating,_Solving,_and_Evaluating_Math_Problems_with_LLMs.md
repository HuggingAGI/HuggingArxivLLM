# # 探究偏见：基于LLMs生成、解决和评估数学问题的多语言流程

发布时间：2025年09月22日

`LLM应用` `教育科技`

> Investigating Bias: A Multilingual Pipeline for Generating, Solving, and Evaluating Math Problems with LLMs

# 摘要

> 大型语言模型（LLMs）在教育支持领域的应用日益广泛，但其响应质量会因交互语言的不同而有所差异。本文提出了一套自动化多语言处理流程，可生成、求解并评估符合德国K-10课程标准的数学题目。我们共设计了628道数学练习题，并将其译为英语、德语和阿拉伯语三种语言。随后，我们让三个商业LLM（GPT-4o-mini、Gemini 2.5 Flash和Qwen-plus）用每种语言生成详细的分步解答。一组独立的LLM评审模型（含Claude 3.5 Haiku）通过比较框架对解答质量进行了评估。结果显示，不同语言的解答质量差距显著：英语解答评分始终位居榜首，阿拉伯语解答则常常排名靠后。这些发现揭示了语言偏见的长期存在，并强调了教育领域亟需构建更公平的多语言AI系统。

> Large Language Models (LLMs) are increasingly used for educational support, yet their response quality varies depending on the language of interaction. This paper presents an automated multilingual pipeline for generating, solving, and evaluating math problems aligned with the German K-10 curriculum. We generated 628 math exercises and translated them into English, German, and Arabic. Three commercial LLMs (GPT-4o-mini, Gemini 2.5 Flash, and Qwen-plus) were prompted to produce step-by-step solutions in each language. A held-out panel of LLM judges, including Claude 3.5 Haiku, evaluated solution quality using a comparative framework. Results show a consistent gap, with English solutions consistently rated highest, and Arabic often ranked lower. These findings highlight persistent linguistic bias and the need for more equitable multilingual AI systems in education.

[Arxiv](https://arxiv.org/abs/2509.17701)