# 解码器与编码器笑声同样响亮

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Decoders Laugh as Loud as Encoders

# 摘要

> 计算机刚问世时，艾伦·图灵就畅想过能像人类一样用语言交流的机器人。近年来，大型语言模型（LLMs）的突破性进展震撼了科学界：单个模型就能胜任多种自然语言处理（NLP）任务，输出结果有时甚至超越了大多数人类的沟通水平。GPT、Claude、Grok等模型已在科学界崭露头角。但这些模型对自身生成内容的理解程度仍不明确，尤其是在幽默这类需要细腻感知的主题上。计算机能否理解幽默仍是未解之谜（在解码器中，最新接受测试的是GPT-2）。本文就此展开研究，结果显示：经过微调的解码器（GPT-4o）表现（平均F1宏分数0.85）与最佳微调编码器（RoBERTa，平均F1分数0.86）不相上下。

> From the dawn of the computer, Allen Turing dreamed of a robot that could communicate using language as a human being. The recent advances in the field of Large Language Models (LLMs) shocked the scientific community when a single model can apply for various natural language processing (NLP) tasks, while the output results are sometimes even better than most human communication skills. Models such as GPT, Claude, Grok, etc. have left their mark on the scientific community. However, it is unclear how much these models understand what they produce, especially in a nuanced theme such as humor. The question of whether computers understand humor is still open (among the decoders, the latest to be checked was GPT-2). We addressed this issue in this paper; we have showed that a fine-tuned decoder (GPT-4o) performed (Mean F1-macro score of 0.85) as well as the best fine-tuned encoder (RoBERTa with a Mean of F1-score 0.86)

[Arxiv](https://arxiv.org/abs/2509.04779)