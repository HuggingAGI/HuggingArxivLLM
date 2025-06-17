# SecurityLingua：通过安全感知的提示压缩实现LLM越狱攻击的高效防御

发布时间：2025年06月14日

`LLM理论` `人工智能安全` `网络安全`

> SecurityLingua: Efficient Defense of LLM Jailbreak Attacks via Security-Aware Prompt Compression

# 摘要

> 大型语言模型（LLMs）已在众多应用中得到广泛应用。然而，即使经过安全对齐，许多LLMs仍易受恶意攻击。这些攻击通常通过将恶意指令隐藏在对抗性越狱提示中，绕过LLMs的安全护栏。此前的研究提出了对抗训练和提示重写等方法来缓解这些安全漏洞，但这些方法往往降低了LLMs的实用性，或导致显著的计算开销和在线延迟。本文中，我们提出了SecurityLingua，这是一种有效且高效的防御方法，旨在通过安全导向的提示压缩来保护LLMs免受越狱攻击。具体而言，我们训练了一个提示压缩器，旨在识别输入提示的“真实意图”，特别关注于检测对抗性提示的恶意意图。然后，除了原始提示外，意图还会通过系统提示传递给目标LLM，以帮助其识别请求的真实意图。SecurityLingua通过保留原始输入提示，揭示用户潜在的恶意意图，并激发LLM内置的安全护栏，从而确保一致的用户体验。此外，得益于提示压缩，与所有现有防御方法相比，SecurityLingua的开销和额外的token成本均可忽略不计，使其成为LLM防御的特别实用的解决方案。实验结果表明，SecurityLingua能够有效防御恶意攻击，并在计算和延迟开销可忽略不计的情况下保持LLM的实用性。我们的代码可在https://aka.ms/SecurityLingua获得。

> Large language models (LLMs) have achieved widespread adoption across numerous applications. However, many LLMs are vulnerable to malicious attacks even after safety alignment. These attacks typically bypass LLMs' safety guardrails by wrapping the original malicious instructions inside adversarial jailbreaks prompts. Previous research has proposed methods such as adversarial training and prompt rephrasing to mitigate these safety vulnerabilities, but these methods often reduce the utility of LLMs or lead to significant computational overhead and online latency. In this paper, we propose SecurityLingua, an effective and efficient approach to defend LLMs against jailbreak attacks via security-oriented prompt compression. Specifically, we train a prompt compressor designed to discern the "true intention" of the input prompt, with a particular focus on detecting the malicious intentions of adversarial prompts. Then, in addition to the original prompt, the intention is passed via the system prompt to the target LLM to help it identify the true intention of the request. SecurityLingua ensures a consistent user experience by leaving the original input prompt intact while revealing the user's potentially malicious intention and stimulating the built-in safety guardrails of the LLM. Moreover, thanks to prompt compression, SecurityLingua incurs only a negligible overhead and extra token cost compared to all existing defense methods, making it an especially practical solution for LLM defense. Experimental results demonstrate that SecurityLingua can effectively defend against malicious attacks and maintain utility of the LLM with negligible compute and latency overhead. Our code is available at https://aka.ms/SecurityLingua.

[Arxiv](https://arxiv.org/abs/2506.12707)