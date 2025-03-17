# 通过表示工程揭示大型语言模型的通用长链式推理能力

发布时间：2025年03月14日

`LLM理论

摘要讨论了大型语言模型（LLMs）的长链式推理能力，从表示学习的角度分析了其作为通用能力的性质，并提出了一种新的方法GLoRE来释放这种能力。这属于对LLMs内在能力的理论分析和方法改进，因此归类为LLM理论。` `人工智能`

> Unlocking General Long Chain-of-Thought Reasoning Capabilities of Large Language Models via Representation Engineering

# 摘要

> 长链式思维（long CoTs）的最新进展显著提升了大型语言模型（LLMs）的推理能力。研究发现，仅需少量示例微调即可有效激发长链式推理能力，并轻松迁移到其他任务。这激发了我们探索长链式推理是否为LLMs通用能力的兴趣。从表示学习的角度，我们进行了实证分析，发现LLMs确实将长链式推理编码为一种通用能力，与普通链式推理（vanilla CoTs）有明显区别。此外，领域特定的表示对迁移长链式推理能力至关重要。基于此，我们提出了一种名为GLoRE的新型表示工程方法，旨在释放LLMs中长链式推理的通用能力。大量实验表明，GLoRE在同领域和跨领域场景中均展现出显著的有效性和效率。

> Recent advancements in long chain-of-thoughts(long CoTs) have significantly improved the reasoning capabilities of large language models(LLMs). Existing work finds that the capability of long CoT reasoning can be efficiently elicited by tuning on only a few examples and can easily transfer to other tasks. This motivates us to investigate whether long CoT reasoning is a general capability for LLMs. In this work, we conduct an empirical analysis for this question from the perspective of representation. We find that LLMs do encode long CoT reasoning as a general capability, with a clear distinction from vanilla CoTs. Furthermore, domain-specific representations are also required for the effective transfer of long CoT reasoning. Inspired by these findings, we propose GLoRE, a novel representation engineering method to unleash the general long CoT reasoning capabilities of LLMs. Extensive experiments demonstrate the effectiveness and efficiency of GLoRE in both in-domain and cross-domain scenarios.

[Arxiv](https://arxiv.org/abs/2503.11314)