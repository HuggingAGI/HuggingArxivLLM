# 基于伪恶意网络安全数据微调的大型语言模型的安全风险分析

发布时间：2025年05月15日

`LLM应用` `网络安全` `人工智能`

> Analysing Safety Risks in LLMs Fine-Tuned with Pseudo-Malicious Cyber Security Data

# 摘要

> 将大型语言模型（LLMs）应用于网络安全领域，既带来了显著机遇，也伴随着重大风险。我们对用于网络安全的微调LLMs进行了全面的安全性评估，基于OWASP LLM应用十大安全风险框架，对七款开源模型进行了深入分析。研究发现，微调过程普遍降低了模型的安全性，但通过重新设计指令-响应对并加入显式安全预防措施，可以在不牺牲技术性能的前提下提升模型安全性。这项研究为LLMs的安全应用提供了系统性评估框架，为开发更安全可靠的生成式AI奠定了基础。

> The integration of large language models (LLMs) into cyber security applications presents significant opportunities, such as enhancing threat analysis and malware detection, but can also introduce critical risks and safety concerns, including personal data leakage and automated generation of new malware. We present a systematic evaluation of safety risks in fine-tuned LLMs for cyber security applications. Using the OWASP Top 10 for LLM Applications framework, we assessed seven open-source LLMs: Phi 3 Mini 3.8B, Mistral 7B, Qwen 2.5 7B, Llama 3 8B, Llama 3.1 8B, Gemma 2 9B, and Llama 2 70B. Our evaluation shows that fine-tuning reduces safety resilience across all tested LLMs (e.g., the safety score of Llama 3.1 8B against prompt injection drops from 0.95 to 0.15). We propose and evaluate a safety alignment approach that carefully rewords instruction-response pairs to include explicit safety precautions and ethical considerations. This approach demonstrates that it is possible to maintain or even improve model safety while preserving technical utility, offering a practical path forward for developing safer fine-tuning methodologies. This work offers a systematic evaluation for safety risks in LLMs, enabling safer adoption of generative AI in sensitive domains, and contributing towards the development of secure, trustworthy, and ethically aligned LLMs.

[Arxiv](https://arxiv.org/abs/2505.09974)