# 基于大型语言模型的交通网联物理系统威胁建模框架

发布时间：2025年06月01日

`LLM应用` `交通系统` `网络安全`

> A Large Language Model-Supported Threat Modeling Framework for Transportation Cyber-Physical Systems

# 摘要

> 现代交通系统的安全性、移动性和能源效率得益于网络物理系统（CPS），其中网络系统与传感器和执行器等物理组件无缝协作。然而，自动化和连通性的提升也带来了更多的网络安全风险。现有的威胁建模框架在交通CPS领域应用受限，不仅资源消耗大，且高度依赖专业网络安全知识。为此，我们开发了TraCR-TMF框架，基于大型语言模型（LLM）设计，旨在减少专家干预。该框架通过MITRE ATT&CK矩阵，结合三种LLM方法识别威胁与攻击技术：(i) 无需专家参与的增强检索生成（RAG）方法，(ii) 低门槛专家参与的上下文学习方法，(iii) 中等专家参与的监督微调方法。此外，TraCR-TMF利用定制化LLM分析漏洞，将攻击路径与关键资产关联。通过两个实际场景验证，该框架在交通CPS应用中准确识别攻击技术，准确率高达90%。同时，在真实世界网络攻击事件中，成功预测了包括横向移动、数据外泄和勒索软件加密在内的多种攻击行为。这些结果充分证明了TraCR-TMF在CPS威胁建模中的高效性、适应性和对专业知识的低依赖性。

> Modern transportation systems rely on cyber-physical systems (CPS), where cyber systems interact seamlessly with physical systems like transportation-related sensors and actuators to enhance safety, mobility, and energy efficiency. However, growing automation and connectivity increase exposure to cyber vulnerabilities. Existing threat modeling frameworks for transportation CPS are often limited in scope, resource-intensive, and dependent on significant cybersecurity expertise. To address these gaps, we present TraCR-TMF (Transportation Cybersecurity and Resiliency Threat Modeling Framework), a large language model (LLM)-based framework that minimizes expert intervention. TraCR-TMF identifies threats, potential attack techniques, and corresponding countermeasures by leveraging the MITRE ATT&CK matrix through three LLM-based approaches: (i) a retrieval-augmented generation (RAG) method requiring no expert input, (ii) an in-context learning approach requiring low expert input, and (iii) a supervised fine-tuning method requiring moderate expert input. TraCR-TMF also maps attack paths to critical assets by analyzing vulnerabilities using a customized LLM. The framework was evaluated in two scenarios. First, it identified relevant attack techniques across transportation CPS applications, with 90% precision as validated by experts. Second, using a fine-tuned LLM, it successfully predicted multiple exploitations including lateral movement, data exfiltration, and ransomware-related encryption that occurred during a major real-world cyberattack incident. These results demonstrate TraCR-TMF's effectiveness in CPS threat modeling, its reduced reliance on cybersecurity expertise, and its adaptability across CPS domains.

[Arxiv](https://arxiv.org/abs/2506.00831)