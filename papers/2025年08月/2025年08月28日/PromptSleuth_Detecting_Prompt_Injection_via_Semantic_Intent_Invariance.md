# PromptSleuth：基于语义意图不变性检测提示词注入

发布时间：2025年08月28日

`LLM应用` `基础理论`

> PromptSleuth: Detecting Prompt Injection via Semantic Intent Invariance

# 摘要

> 大型语言模型（LLMs）正日益融入现实世界的各类应用，从虚拟助手到自主智能体不一而足。然而，这种灵活性也带来了新的攻击途径——尤其是提示注入（PI），攻击者通过精心构造的输入来操控模型行为。随着攻击者不断升级策略，采用改写、混淆甚至多任务注入等手段，现有的基准测试已难以覆盖新兴威胁的全貌。
  为填补这一空白，我们构建了全新的基准测试，对现有研究成果进行了系统性拓展。该基准测试不仅整合了两个广泛使用的现有测试集，还引入了新的操纵技术和多任务场景，进而构建了更全面的评估体系。我们发现，现有防御措施虽在原测试集上表现有效，但在我们的基准测试中暴露出明显短板，这表明亟需更可靠的解决方案。我们的核心发现是：无论攻击形式如何变化，攻击者的核心意图始终未变，即注入未授权任务。基于这一发现，我们提出了PromptSleuth——一个面向语义的防御框架，它通过对任务级意图而非表面特征进行推理，来检测提示注入行为。在主流先进基准测试中评估发现，PromptSleuth在保持相近运行时间和成本效率的前提下，性能持续优于现有防御方法。这些结果证实，基于意图的语义推理为保护LLMs抵御不断演变的提示注入威胁，提供了一种强大、高效且具有普适性的防御策略。

> Large Language Models (LLMs) are increasingly integrated into real-world applications, from virtual assistants to autonomous agents. However, their flexibility also introduces new attack vectors-particularly Prompt Injection (PI), where adversaries manipulate model behavior through crafted inputs. As attackers continuously evolve with paraphrased, obfuscated, and even multi-task injection strategies, existing benchmarks are no longer sufficient to capture the full spectrum of emerging threats.
  To address this gap, we construct a new benchmark that systematically extends prior efforts. Our benchmark subsumes the two widely-used existing ones while introducing new manipulation techniques and multi-task scenarios, thereby providing a more comprehensive evaluation setting. We find that existing defenses, though effective on their original benchmarks, show clear weaknesses under our benchmark, underscoring the need for more robust solutions. Our key insight is that while attack forms may vary, the adversary's intent-injecting an unauthorized task-remains invariant. Building on this observation, we propose PromptSleuth, a semantic-oriented defense framework that detects prompt injection by reasoning over task-level intent rather than surface features. Evaluated across state-of-the-art benchmarks, PromptSleuth consistently outperforms existing defense while maintaining comparable runtime and cost efficiency. These results demonstrate that intent-based semantic reasoning offers a robust, efficient, and generalizable strategy for defending LLMs against evolving prompt injection threats.

[Arxiv](https://arxiv.org/abs/2508.20890)