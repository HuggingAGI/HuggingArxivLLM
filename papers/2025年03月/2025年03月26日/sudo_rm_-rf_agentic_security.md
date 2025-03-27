# sudo rm -rf agentic_security（使用 sudo 命令强制删除名为 'agentic_security' 的文件或目录）

发布时间：2025年03月26日

`LLM应用` `计算机安全` `计算机科学`

> sudo rm -rf agentic_security

# 摘要

> 大型语言模型 (LLMs) 正越来越多地被部署为计算机使用代理，在真实桌面或网络环境中自主执行任务。虽然这一演变极大地扩展了人类的实际应用场景，但也带来了严重的安全风险。我们提出了 SUDO（基于屏幕的通用解毒中毒攻击框架），这是一个新颖的攻击框架，系统性地绕过了商业计算机使用代理（如 Claude Computer Use）中经过训练的拒绝防护措施。其核心机制 Detox2Tox 将有害请求（代理最初会拒绝）通过解毒过程转化为看似无害的请求，从先进视觉语言模型 (VLMs) 中获取详细指令，然后在执行前通过中毒过程重新引入恶意内容。与传统越狱攻击不同，SUDO 会根据内置的拒绝反馈进行迭代攻击优化，使其对强大的策略过滤器越来越有效。在涵盖 50 个现实任务和多个最先进 VLMs 的广泛测试中，SUDO 在 Claude Computer Use 中实现了 24% 的攻击成功率（未经优化），通过迭代优化后甚至达到了 41%。本文揭示了这些漏洞，并展示了它们在现实计算环境中被轻易利用的可能性，突显了建立健壮且上下文感知的防护措施的紧迫需求。警告：本文包含有害或冒犯性的模型输出。

> Large Language Models (LLMs) are increasingly deployed as computer-use agents, autonomously performing tasks within real desktop or web environments. While this evolution greatly expands practical use cases for humans, it also creates serious security exposures. We present SUDO (Screen-based Universal Detox2Tox Offense), a novel attack framework that systematically bypasses refusal trained safeguards in commercial computer-use agents, such as Claude Computer Use. The core mechanism, Detox2Tox, transforms harmful requests (that agents initially reject) into seemingly benign requests via detoxification, secures detailed instructions from advanced vision language models (VLMs), and then reintroduces malicious content via toxification just before execution. Unlike conventional jailbreaks, SUDO iteratively refines its attacks based on a built-in refusal feedback, making it increasingly effective against robust policy filters. In extensive tests spanning 50 real-world tasks and multiple state-of-the-art VLMs, SUDO achieves a stark attack success rate of 24% (with no refinement), and up to 41% (by its iterative refinement) in Claude Computer Use. By revealing these vulnerabilities and demonstrating the ease with which they can be exploited in real-world computing environments, this paper highlights an immediate need for robust, context-aware safeguards. WARNING: This paper includes harmful or offensive model outputs.

[Arxiv](https://arxiv.org/abs/2503.20279)