# 高效Token注入攻击：利用自适应压缩技术引发LLM推理终止

发布时间：2025年04月29日

`LLM理论` `人工智能`

> Token-Efficient Prompt Injection Attack: Provoking Cessation in LLM Reasoning via Adaptive Token Compression

# 摘要

> 推理大语言模型（LLMs）在各类任务中表现出色，但同时也存在显著的安全隐患。近期研究发现，DeepSeek-R1中存在一种“思考停止”漏洞，模型生成的推理令牌可强制中断推理过程，导致空白响应，从而危及集成LLM的应用程序。然而，现有触发该漏洞的方法需要复杂的数学问题和冗长的提示——甚至超过5,000个令牌。为降低令牌成本并正式定义这一漏洞，我们提出了一种基于自适应令牌压缩的新型提示注入攻击，命名为“推理中断攻击”。我们发现，简单的独立算术任务即可有效触发此漏洞，且基于此类任务的提示相较于数学问题具有更简单的逻辑结构。我们开发了一种系统化方法来高效收集攻击提示，并构建了一个自适应令牌压缩框架，利用LLMs自动压缩这些提示。实验表明，我们的压缩框架在保持有效攻击能力的同时，显著减少了提示长度。我们进一步通过输出前缀分析攻击性能，并探究漏洞的根本原因，为提升推理LLMs的安全性提供了宝贵的见解。
    

> While reasoning large language models (LLMs) demonstrate remarkable performance across various tasks, they also contain notable security vulnerabilities. Recent research has uncovered a "thinking-stopped" vulnerability in DeepSeek-R1, where model-generated reasoning tokens can forcibly interrupt the inference process, resulting in empty responses that compromise LLM-integrated applications. However, existing methods triggering this vulnerability require complex mathematical word problems with long prompts--even exceeding 5,000 tokens. To reduce the token cost and formally define this vulnerability, we propose a novel prompt injection attack named "Reasoning Interruption Attack", based on adaptive token compression. We demonstrate that simple standalone arithmetic tasks can effectively trigger this vulnerability, and the prompts based on such tasks exhibit simpler logical structures than mathematical word problems. We develop a systematic approach to efficiently collect attack prompts and an adaptive token compression framework that utilizes LLMs to automatically compress these prompts. Experiments show our compression framework significantly reduces prompt length while maintaining effective attack capabilities. We further investigate the attack's performance via output prefix and analyze the underlying causes of the vulnerability, providing valuable insights for improving security in reasoning LLMs.

[Arxiv](https://arxiv.org/abs/2504.20493)