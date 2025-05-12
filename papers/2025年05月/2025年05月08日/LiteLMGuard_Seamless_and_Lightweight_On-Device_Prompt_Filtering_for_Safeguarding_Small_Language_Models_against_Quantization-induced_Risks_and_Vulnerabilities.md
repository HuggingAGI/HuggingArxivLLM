# # LiteLMGuard：守护小型语言模型，抵御量化引发的风险与漏洞，实现无缝轻量级设备端提示过滤

发布时间：2025年05月08日

`LLM应用` `移动计算` `边缘计算`

> LiteLMGuard: Seamless and Lightweight On-Device Prompt Filtering for Safeguarding Small Language Models against Quantization-induced Risks and Vulnerabilities

# 摘要

> 大型语言模型（LLMs）的广泛应用推动了其轻量化版本——小型语言模型（SLMs）的发展，使其能够实现在智能手机和边缘设备上的本地部署。这些SLMs带来了更高的隐私性、更低的延迟、无服务器运行以及更佳的用户体验。然而，受限于本地环境的资源限制，SLMs通常需要通过量化等压缩技术进行尺寸优化，这可能无意中引发公平性、伦理和隐私风险。至关重要的是，经过量化的SLMs可能直接对有害查询做出回应，无需经过对抗性操作，这引发了严重的安全性和可信度问题。
    为了解决这一问题，我们提出了LiteLMGuard（LLMG），这是一种针对量化SLMs的本地提示守护机制，能够实现实时、基于提示级别的防御。此外，我们的提示守护机制设计为模型不可知论，这意味着它可以无缝集成到任何SLM中，独立于底层架构运行。我们的LLMG将提示过滤形式化为一个基于深度学习（DL）的提示可回答性分类任务，通过语义理解来判断某个查询是否应由任何SLM回答。利用我们整理的Answerable-or-Not数据集，我们训练并微调了多个DL模型，并选择了ELECTRA作为候选模型，其可回答性分类准确率达到97.75%。
    在安全性有效性评估中，LLMG成功防御了超过87%的有害提示，涵盖直接指令和越狱攻击策略。我们进一步展示了其在缓解开放知识攻击方面的能力，即在无对抗性提示的情况下，被攻破的SLMs提供不安全的响应。在提示过滤有效性方面，LLMG实现了接近最先进水平的94%过滤准确率，平均延迟为135毫秒，对用户造成的额外开销可以忽略不计。

> The growing adoption of Large Language Models (LLMs) has influenced the development of their lighter counterparts-Small Language Models (SLMs)-to enable on-device deployment across smartphones and edge devices. These SLMs offer enhanced privacy, reduced latency, server-free functionality, and improved user experience. However, due to resource constraints of on-device environment, SLMs undergo size optimization through compression techniques like quantization, which can inadvertently introduce fairness, ethical and privacy risks. Critically, quantized SLMs may respond to harmful queries directly, without requiring adversarial manipulation, raising significant safety and trust concerns.
  To address this, we propose LiteLMGuard (LLMG), an on-device prompt guard that provides real-time, prompt-level defense for quantized SLMs. Additionally, our prompt guard is designed to be model-agnostic such that it can be seamlessly integrated with any SLM, operating independently of underlying architectures. Our LLMG formalizes prompt filtering as a deep learning (DL)-based prompt answerability classification task, leveraging semantic understanding to determine whether a query should be answered by any SLM. Using our curated dataset, Answerable-or-Not, we trained and fine-tuned several DL models and selected ELECTRA as the candidate, with 97.75% answerability classification accuracy.
  Our safety effectiveness evaluations demonstrate that LLMG defends against over 87% of harmful prompts, including both direct instruction and jailbreak attack strategies. We further showcase its ability to mitigate the Open Knowledge Attacks, where compromised SLMs provide unsafe responses without adversarial prompting. In terms of prompt filtering effectiveness, LLMG achieves near state-of-the-art filtering accuracy of 94%, with an average latency of 135 ms, incurring negligible overhead for users.

[Arxiv](https://arxiv.org/abs/2505.05619)