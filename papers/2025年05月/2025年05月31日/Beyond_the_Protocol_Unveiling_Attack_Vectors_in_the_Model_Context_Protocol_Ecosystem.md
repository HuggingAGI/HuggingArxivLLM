# 超越协议：探索模型上下文协议生态中的攻击向量

发布时间：2025年05月31日

`LLM应用` `网络安全` `人工智能`

> Beyond the Protocol: Unveiling Attack Vectors in the Model Context Protocol Ecosystem

# 摘要

> 模型上下文协议（MCP）是一项新兴标准，旨在实现大型语言模型（LLM）应用与外部工具或资源之间的无缝交互。短短时间内，已有数千个MCP服务被开发和部署。然而，MCP固有的客户端-服务器集成架构可能扩大针对LLM代理系统的攻击面，引入新的漏洞，使攻击者能够通过设计恶意MCP服务器进行利用。本文首次系统性地研究针对MCP生态系统的攻击向量。我们的分析识别出四类攻击，即工具投毒攻击、傀儡攻击、拉地毯攻击以及通过恶意外部资源的利用。为了评估这些攻击的可行性，我们按照通过恶意MCP服务器发起攻击的典型步骤：上传-下载-攻击，进行了实验。具体而言，我们首先构建了恶意MCP服务器，并成功将其上传至三个广泛使用的MCP聚合平台。实验结果表明，当前的审核机制不足以识别和阻止我们提出的攻击方法。其次，通过一项针对20名参与者的用户研究和访谈，我们证明用户难以识别恶意MCP服务器，常常在不知情的情况下从聚合平台安装它们。最后，我们通过部署一个概念验证（PoC）框架，针对五个领先的LLM，展示了这些攻击能够在用户的本地环境中触发有害行为，例如访问私人文件或控制设备以转移数字资产。此外，基于访谈结果，我们讨论了当前围绕MCP服务器的安全生态系统所面临四个关键挑战。这些发现强调了建立强大的安全机制以防御恶意MCP服务器的迫切需求。

> The Model Context Protocol (MCP) is an emerging standard designed to enable seamless interaction between Large Language Model (LLM) applications and external tools or resources. Within a short period, thousands of MCP services have already been developed and deployed. However, the client-server integration architecture inherent in MCP may expand the attack surface against LLM Agent systems, introducing new vulnerabilities that allow attackers to exploit by designing malicious MCP servers. In this paper, we present the first systematic study of attack vectors targeting the MCP ecosystem. Our analysis identifies four categories of attacks, i.e., Tool Poisoning Attacks, Puppet Attacks, Rug Pull Attacks, and Exploitation via Malicious External Resources. To evaluate the feasibility of these attacks, we conduct experiments following the typical steps of launching an attack through malicious MCP servers: upload-download-attack. Specifically, we first construct malicious MCP servers and successfully upload them to three widely used MCP aggregation platforms. The results indicate that current audit mechanisms are insufficient to identify and prevent the proposed attack methods. Next, through a user study and interview with 20 participants, we demonstrate that users struggle to identify malicious MCP servers and often unknowingly install them from aggregator platforms. Finally, we demonstrate that these attacks can trigger harmful behaviors within the user's local environment-such as accessing private files or controlling devices to transfer digital assets-by deploying a proof-of-concept (PoC) framework against five leading LLMs. Additionally, based on interview results, we discuss four key challenges faced by the current security ecosystem surrounding MCP servers. These findings underscore the urgent need for robust security mechanisms to defend against malicious MCP servers.

[Arxiv](https://arxiv.org/abs/2506.02040)