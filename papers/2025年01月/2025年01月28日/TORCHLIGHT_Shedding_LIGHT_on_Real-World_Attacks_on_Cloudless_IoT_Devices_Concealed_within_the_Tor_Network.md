# TORCHLIGHT: 照亮隐藏在Tor网络中的无云物联网设备的现实攻击

发布时间：2025年01月28日

`LLM应用

**解释**：这篇论文主要讨论了利用大型语言模型（LLMs）的链式思维（CoT）过程来开发TORCHLIGHT工具，用于检测针对无云物联网设备的威胁。虽然论文涉及物联网和网络安全，但其核心应用了LLM技术来解决实际问题，因此归类为LLM应用。` `物联网` `网络安全`

> TORCHLIGHT: Shedding LIGHT on Real-World Attacks on Cloudless IoT Devices Concealed within the Tor Network

# 摘要

> 物联网（IoT）领域正迅速向无云架构转型，减少了对集中式云服务的依赖，但也将设备直接暴露在互联网上，增加了遭受网络攻击的风险。我们的研究发现，针对无云物联网设备的Tor网络流量显著增加，表明攻击者可能通过Tor匿名利用未公开的漏洞（可能来自地下市场）。为此，我们开发了TORCHLIGHT工具，通过分析Tor流量来检测针对无云物联网设备的已知和未知威胁。TORCHLIGHT通过特定IP模式过滤流量，并战略性地部署虚拟专用服务器（VPS）节点，结合大型语言模型（LLMs）的链式思维（CoT）过程，实现高效且准确的威胁识别。
    研究结果意义重大：我们首次证实攻击者确实利用Tor隐藏身份，针对无云物联网设备发起攻击。在12个月内，TORCHLIGHT分析了26 TB的流量，发现了45个漏洞，包括29个零日漏洞，其中25个已分配CVE-ID（5个严重，3个高，16个中，1个低），估计价值约31.2万美元。这些漏洞影响了148个国家约1271万台设备，使其面临信息泄露、认证绕过和任意命令执行等严重风险。这一发现引发了网络安全圈的广泛讨论，登上了Hacker News前25名，并获得了超过19万次浏览量。

> The rapidly expanding Internet of Things (IoT) landscape is shifting toward cloudless architectures, removing reliance on centralized cloud services but exposing devices directly to the internet and increasing their vulnerability to cyberattacks. Our research revealed an unexpected pattern of substantial Tor network traffic targeting cloudless IoT devices. suggesting that attackers are using Tor to anonymously exploit undisclosed vulnerabilities (possibly obtained from underground markets). To delve deeper into this phenomenon, we developed TORCHLIGHT, a tool designed to detect both known and unknown threats targeting cloudless IoT devices by analyzing Tor traffic. TORCHLIGHT filters traffic via specific IP patterns, strategically deploys virtual private server (VPS) nodes for cost-effective detection, and uses a chain-of-thought (CoT) process with large language models (LLMs) for accurate threat identification.
  Our results are significant: for the first time, we have demonstrated that attackers are indeed using Tor to conceal their identities while targeting cloudless IoT devices. Over a period of 12 months, TORCHLIGHT analyzed 26 TB of traffic, revealing 45 vulnerabilities, including 29 zero-day exploits with 25 CVE-IDs assigned (5 CRITICAL, 3 HIGH, 16 MEDIUM, and 1 LOW) and an estimated value of approximately $312,000. These vulnerabilities affect around 12.71 million devices across 148 countries, exposing them to severe risks such as information disclosure, authentication bypass, and arbitrary command execution. The findings have attracted significant attention, sparking widespread discussion in cybersecurity circles, reaching the top 25 on Hacker News, and generating over 190,000 views.

[Arxiv](https://arxiv.org/abs/2501.16784)