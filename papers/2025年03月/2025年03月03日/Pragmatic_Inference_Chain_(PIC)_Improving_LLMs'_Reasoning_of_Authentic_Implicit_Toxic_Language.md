# 实用推理链 (PIC) 助力大型语言模型更精准识别隐含毒性语言

发布时间：2025年03月03日

`LLM应用

摘要讨论了将大型语言模型应用于检测隐含毒性语言，并提出了一种新的提示方法来提升模型的推理能力。这属于LLM的应用层面，因此归类为LLM应用。` `语言模型`

> Pragmatic Inference Chain (PIC) Improving LLMs' Reasoning of Authentic Implicit Toxic Language

# 摘要

> 大型语言模型（LLMs）的快速发展带来了伦理争议，同时也为检测有毒语言提供了新思路。然而，现有研究主要在简单的语义关联场景下测试 LLMs 的不当输出和毒性检测能力，例如将 'he' 与程序员、'she' 与家庭主妇进行刻板联想。如今，得益于审查技术的进步，有毒语言采用了更加隐晦复杂的表达形式。本研究收集了真实且复杂的有毒互动数据，这些数据经过人工标注员验证，具有较强的推理需求。为了提升 LLMs 对真实隐含毒性语言的推理能力，我们提出了一种新的提示方法——语用推理链（PIC），该方法结合了认知科学和语言学领域的跨学科研究成果。实验结果显示，与直接提示和思维链方法相比，PIC 提示方法显著提高了 GPT-4o、Llama-3.1-70B-Instruct 和 DeepSeek-v2.5 在识别隐含毒性语言方面的成功率。此外，它还帮助模型生成更加明确和连贯的推理过程，因此可以潜在地推广到其他需要复杂推理的任务中，例如理解幽默和隐喻。

> The rapid development of large language models (LLMs) gives rise to ethical concerns about their performance, while opening new avenues for developing toxic language detection techniques. However, LLMs' unethical output and their capability of detecting toxicity have primarily been tested on language data that do not demand complex meaning inference, such as the biased associations of 'he' with programmer and 'she' with household. Nowadays toxic language adopts a much more creative range of implicit forms, thanks to advanced censorship. In this study, we collect authentic toxic interactions that evade online censorship and that are verified by human annotators as inference intensive. To evaluate and improve LLMs' reasoning of the authentic implicit toxic language, we propose a new prompting method, Pragmatic Inference Chain (PIC), drawn on interdisciplinary findings from cognitive science and linguistics. The PIC prompting significantly improves the success rate of GPT-4o, Llama-3.1-70B-Instruct, and DeepSeek-v2.5 in identifying implicit toxic language, compared to both direct prompting and Chain-of-Thought. In addition, it also facilitates the models to produce more explicit and coherent reasoning processes, hence can potentially be generalized to other inference-intensive tasks, e.g., understanding humour and metaphors.

[Arxiv](https://arxiv.org/abs/2503.01539)