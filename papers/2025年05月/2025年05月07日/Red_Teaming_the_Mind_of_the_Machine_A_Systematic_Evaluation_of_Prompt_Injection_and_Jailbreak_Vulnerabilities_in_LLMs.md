# 红队评估机器思维：LLMs中提示注入与越狱漏洞的系统评估

发布时间：2025年05月07日

`LLM应用` `消费级` `企业级`

> Red Teaming the Mind of the Machine: A Systematic Evaluation of Prompt Injection and Jailbreak Vulnerabilities in LLMs

# 摘要

> 大型语言模型（LLMs）正被越来越多地应用于消费级和企业级场景。尽管其功能强大，但它们仍然容易受到提示注入和越狱攻击等对抗攻击的影响，这些攻击能够绕过对齐防护机制。本文系统性地研究了针对各种先进LLMs的越狱攻击策略。我们对1,400多个对抗提示进行了分类，分析了它们对GPT-4、Claude 2、Mistral 7B和Vicuna的成功率，并探讨了它们的通用性和构建逻辑。此外，我们提出了分层缓解策略，并建议采用混合红队和沙盒方法来增强LLM的安全性。

> Large Language Models (LLMs) are increasingly integrated into consumer and enterprise applications. Despite their capabilities, they remain susceptible to adversarial attacks such as prompt injection and jailbreaks that override alignment safeguards. This paper provides a systematic investigation of jailbreak strategies against various state-of-the-art LLMs. We categorize over 1,400 adversarial prompts, analyze their success against GPT-4, Claude 2, Mistral 7B, and Vicuna, and examine their generalizability and construction logic. We further propose layered mitigation strategies and recommend a hybrid red-teaming and sandboxing approach for robust LLM security.

[Arxiv](https://arxiv.org/abs/2505.04806)