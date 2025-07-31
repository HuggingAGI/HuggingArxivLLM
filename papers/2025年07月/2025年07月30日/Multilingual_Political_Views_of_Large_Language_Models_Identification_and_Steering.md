# 大型语言模型的多语言政治立场：识别与调控

发布时间：2025年07月30日

`LLM应用` `人工智能`

> Multilingual Political Views of Large Language Models: Identification and Steering

# 摘要

> 大型语言模型 (LLMs) 在日常工具中的广泛应用引发了对其可能对政治观点产生影响的担忧。尽管研究发现 LLMs 经常表现出倾向于自由派或进步立场的政治偏见，但仍存在关键空白。现有研究仅限于有限的模型和语言，跨架构、规模和多语言设置下的政治偏见普遍性尚未可知。此外，如何主动控制这些偏见的研究也十分有限。

本研究通过大规模研究现代开源指令微调的 LLMs 的政治倾向来填补这些空白。我们使用包含 11 个语义等价的同义句的《政治指南针测试》，对七种模型（包括 LLaMA-3.1、Qwen-3 和 Aya-Expanse）进行了涵盖 14 种语言的评估，确保测量的稳健性。结果显示，规模更大的模型始终向自由派左翼立场偏移，且在不同语言和模型家族间存在显著差异。为了测试政治立场的可操控性，我们采用了一种简单的质心激活干预技术，并展示了它能够可靠地将模型回应引导至多种语言下的替代意识形态立场。我们的代码可在 https://github.com/d-gurgurov/Political-Ideologies-LLMs 公开获取。

> Large language models (LLMs) are increasingly used in everyday tools and applications, raising concerns about their potential influence on political views. While prior research has shown that LLMs often exhibit measurable political biases--frequently skewing toward liberal or progressive positions--key gaps remain. Most existing studies evaluate only a narrow set of models and languages, leaving open questions about the generalizability of political biases across architectures, scales, and multilingual settings. Moreover, few works examine whether these biases can be actively controlled.
  In this work, we address these gaps through a large-scale study of political orientation in modern open-source instruction-tuned LLMs. We evaluate seven models, including LLaMA-3.1, Qwen-3, and Aya-Expanse, across 14 languages using the Political Compass Test with 11 semantically equivalent paraphrases per statement to ensure robust measurement. Our results reveal that larger models consistently shift toward libertarian-left positions, with significant variations across languages and model families. To test the manipulability of political stances, we utilize a simple center-of-mass activation intervention technique and show that it reliably steers model responses toward alternative ideological positions across multiple languages. Our code is publicly available at https://github.com/d-gurgurov/Political-Ideologies-LLMs.

[Arxiv](https://arxiv.org/abs/2507.22623)