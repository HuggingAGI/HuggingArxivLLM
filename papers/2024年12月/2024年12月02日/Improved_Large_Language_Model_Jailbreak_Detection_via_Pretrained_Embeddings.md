# 借助预训练嵌入提升大型语言模型越狱检测能力

发布时间：2024年12月02日

`LLM应用` `语言模型` `安全保障`

> Improved Large Language Model Jailbreak Detection via Pretrained Embeddings

# 摘要

> 大型语言模型（LLMs）已被广泛应用于诸多领域，如客户服务聊天机器人、软件开发助手，乃至更强大的智能体系统。这就使得如何保障这些系统的安全性成为了必须研究的课题。像提示注入和越狱这样的攻击手段，试图让模型给出不符合使用该模型的组织的安全、隐私或内容政策的响应和行动。为了避免LLMs被滥用从而生成可能有害的回复或做出不良行为，LLM所有者在训练时必须采取保障措施，并整合额外的工具来阻止LLM生成违规文本。越狱提示对于诱导LLM生成潜在有害内容起着关键作用，所以识别越狱尝试以阻止后续步骤至关重要。在本研究中，我们提出了一种新颖的方法，通过将适用于检索的文本嵌入与传统机器学习分类算法相结合来检测越狱提示。我们的方法优于开源LLM安全应用中的所有公开可用方法。

> The adoption of large language models (LLMs) in many applications, from customer service chat bots and software development assistants to more capable agentic systems necessitates research into how to secure these systems. Attacks like prompt injection and jailbreaking attempt to elicit responses and actions from these models that are not compliant with the safety, privacy, or content policies of organizations using the model in their application. In order to counter abuse of LLMs for generating potentially harmful replies or taking undesirable actions, LLM owners must apply safeguards during training and integrate additional tools to block the LLM from generating text that abuses the model. Jailbreaking prompts play a vital role in convincing an LLM to generate potentially harmful content, making it important to identify jailbreaking attempts to block any further steps. In this work, we propose a novel approach to detect jailbreak prompts based on pairing text embeddings well-suited for retrieval with traditional machine learning classification algorithms. Our approach outperforms all publicly available methods from open source LLM security applications.

[Arxiv](https://arxiv.org/abs/2412.01547)