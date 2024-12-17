# 大型语言模型中的精确长度控制

发布时间：2024年12月16日

`LLM应用` `生产系统` `语言模型`

> Precise Length Control in Large Language Models

# 摘要

> 大型语言模型（LLMs）在生产系统中的应用愈发广泛，为诸如聊天机器人、摘要生成和问答等应用注入了强大动力。尽管成绩斐然，但控制其响应长度仍是一项艰巨挑战，特别是对于那些需要结构化输出或特定详细程度的任务而言。在本研究中，我们提出了一种让预先训练的仅解码器型 LLMs 适应精确控制响应长度的方法。我们的方案将二次长度差位置编码（LDPE）融入输入嵌入中，它会倒计时至用户设定的响应终止长度。通过 LDPE 进行微调，使得模型能够学会在期望长度上连贯地终止响应，实现平均令牌误差小于 3 个令牌。我们还引入了 Max New Tokens++，这一扩展实现了灵活的上限长度控制，而非精确的目标。在问答和文档摘要等任务上的实验结果表明，我们的方法能够实现精确的长度控制，且不影响响应质量。

> Large Language Models (LLMs) are increasingly used in production systems, powering applications such as chatbots, summarization, and question answering. Despite their success, controlling the length of their response remains a significant challenge, particularly for tasks requiring structured outputs or specific levels of detail. In this work, we propose a method to adapt pre-trained decoder-only LLMs for precise control of response length. Our approach incorporates a secondary length-difference positional encoding (LDPE) into the input embeddings, which counts down to a user-set response termination length. Fine-tuning with LDPE allows the model to learn to terminate responses coherently at the desired length, achieving mean token errors of less than 3 tokens. We also introduce Max New Tokens++, an extension that enables flexible upper-bound length control, rather than an exact target. Experimental results on tasks such as question answering and document summarization demonstrate that our method enables precise length control without compromising response quality.

[Arxiv](https://arxiv.org/abs/2412.11937)