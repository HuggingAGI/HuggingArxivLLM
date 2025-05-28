# 突破天花板：通过扩展策略空间探索模型越狱攻击的潜力

发布时间：2025年05月27日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在安全方面的应用，特别是针对越狱攻击的研究。它提出了一种新的框架来扩展策略空间，以提高攻击的成功率，并进行了实验验证。因此，它属于LLM应用类别。` `人工智能安全` `网络安全`

> Breaking the Ceiling: Exploring the Potential of Jailbreak Attacks through Expanding Strategy Space

# 摘要

> 尽管大型语言模型（LLMs）具备强大的通用能力，但其仍然面临诸多安全风险，尤其是能够绕过安全协议的越狱攻击。通过更能反映现实场景的黑盒越狱攻击，我们能够深入理解这些漏洞，从而为模型的鲁棒性提供关键洞见。尽管现有方法通过各种提示工程手段取得了一定的改进，但面对安全对齐的模型，其成功率仍然有限。这忽视了一个更根本性的问题：其有效性本质上受限于预定义的策略空间。然而，扩展这一空间在系统性捕获关键攻击模式和高效应对复杂性增加方面都面临巨大挑战。为了更好地探索扩展策略空间的潜力，我们提出了一种基于详尽可能性模型（ELM）理论的新型框架，该框架将越狱策略分解为关键组件，并结合意图评估机制的遗传优化。令人瞩目的是，我们的实验揭示了通过扩展策略空间前所未有的越狱能力：我们在Claude-3.5上实现了超过90%的成功率，而之前的方法完全失败。同时，我们的方法展示了强大的跨模型迁移能力，并在评估准确性上超越了专用的防护模型。代码已开源：https://github.com/Aries-iai/CL-GSO。

> Large Language Models (LLMs), despite advanced general capabilities, still suffer from numerous safety risks, especially jailbreak attacks that bypass safety protocols. Understanding these vulnerabilities through black-box jailbreak attacks, which better reflect real-world scenarios, offers critical insights into model robustness. While existing methods have shown improvements through various prompt engineering techniques, their success remains limited against safety-aligned models, overlooking a more fundamental problem: the effectiveness is inherently bounded by the predefined strategy spaces. However, expanding this space presents significant challenges in both systematically capturing essential attack patterns and efficiently navigating the increased complexity. To better explore the potential of expanding the strategy space, we address these challenges through a novel framework that decomposes jailbreak strategies into essential components based on the Elaboration Likelihood Model (ELM) theory and develops genetic-based optimization with intention evaluation mechanisms. To be striking, our experiments reveal unprecedented jailbreak capabilities by expanding the strategy space: we achieve over 90% success rate on Claude-3.5 where prior methods completely fail, while demonstrating strong cross-model transferability and surpassing specialized safeguard models in evaluation accuracy. The code is open-sourced at: https://github.com/Aries-iai/CL-GSO.

[Arxiv](https://arxiv.org/abs/2505.21277)