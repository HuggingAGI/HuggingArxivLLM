# # 前沿大语言模型隐写术能力初现端倪

发布时间：2025年07月03日

`LLM理论` `AI监控` `隐写术`

> Early Signs of Steganographic Capabilities in Frontier LLMs

# 摘要

> 监控大型语言模型（LLM）的输出对于缓解滥用和对齐风险至关重要。然而，LLMs可能通过隐写术来逃避监控：将隐藏的信息编码在看似无害的生成内容中。本文旨在评估前沿LLMs的隐写能力，以更好地理解其潜在风险。我们重点研究了两种隐写类型：传递编码消息和进行编码推理。我们发现，在标准辅助功能下，当前模型无法在输出中编码短消息而不被监控系统察觉。然而，如果提供额外的辅助功能，例如使用未被监控的临时存储区或协调编码方案的使用，它们则能够成功。此外，我们还发现了一些早期迹象，表明模型可以在简单状态跟踪问题中执行基本的编码推理，包括一定程度上能够利用自身定义的编码方案（如十六进制）进行推理。尽管如此，它们很少能将推理巧妙地隐藏在覆盖任务中以欺骗监控系统。总体而言，我们的研究结果表明，当前LLMs表现出初步的隐写能力。尽管这些能力目前可能不足以绕过设计良好的监控系统，但未来这一状况可能发生变化。

> Monitoring Large Language Model (LLM) outputs is crucial for mitigating risks from misuse and misalignment. However, LLMs could evade monitoring through steganography: Encoding hidden information within seemingly benign generations. In this paper, we evaluate the steganography capabilities in frontier LLMs to better understand the risk they pose. We focus on two types of steganography: passing encoded messages and performing encoded reasoning. We find that current models are unable to encode short messages in their outputs without a monitor noticing under standard affordances. They can succeed, however, if given additional affordances such as using an unmonitored scratchpad and coordinating on what encoding scheme to use. We additionally find early signs that models can perform basic encoded reasoning in a simple state-tracking problem. This includes some ability to reason with their own and pre-defined schemes, including encoding schemes such as Hexadecimal. Despite this, they can rarely hide reasoning subtly within a cover task to fool a monitor. Overall, our results indicate that current LLMs exhibit nascent steganographic capabilities. While these capabilities are likely insufficient to bypass well-designed monitors at present, this could change in the future.

[Arxiv](https://arxiv.org/abs/2507.02737)