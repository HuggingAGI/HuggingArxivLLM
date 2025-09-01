# # CyberSleuth：面向Web攻击取证的蓝队自主LLM智能体

发布时间：2025年08月28日

`Agent` `基础理论`

> CyberSleuth: Autonomous Blue-Team LLM Agent for Web Attack Forensics

# 摘要

> 大型语言模型（LLM）智能体是自动化复杂任务的得力工具。在网络安全领域，研究人员主要探索了其在红队操作中的应用，如漏洞发现和渗透测试。而用于事件响应与取证的防御性应用则关注较少，尚处于起步阶段。本研究针对真实Web应用攻击的取证调查，对LLM智能体设计展开了系统性探究。我们提出了CyberSleuth——一个自主智能体，它通过处理数据包级痕迹与应用日志，识别目标服务、被利用的漏洞（CVE）及攻击是否成功。我们评估了核心设计决策（涵盖工具集成与智能体架构）的影响，并为从业者提供了可解释的指导建议。在20个复杂度递增的事件场景中，我们对四种智能体架构和六种LLM后端进行了基准测试，结果显示CyberSleuth性能最优。在2025年的另一组10起事件中，CyberSleuth在80%的案例中准确识别出了具体的CVE。最后，我们邀请22位专家开展了人工评估，专家们认为CyberSleuth的报告完整、实用且逻辑连贯。他们还对DeepSeek R1表现出轻微偏好，这对开源LLM来说无疑是个好消息。为推动防御性LLM研究的发展，我们发布了基准测试与CyberSleuth平台，为取证智能体的公平、可复现评估奠定了基础。

> Large Language Model (LLM) agents are powerful tools for automating complex tasks. In cybersecurity, researchers have primarily explored their use in red-team operations such as vulnerability discovery and penetration tests. Defensive uses for incident response and forensics have received comparatively less attention and remain at an early stage. This work presents a systematic study of LLM-agent design for the forensic investigation of realistic web application attacks. We propose CyberSleuth, an autonomous agent that processes packet-level traces and application logs to identify the targeted service, the exploited vulnerability (CVE), and attack success. We evaluate the consequences of core design decisions - spanning tool integration and agent architecture - and provide interpretable guidance for practitioners. We benchmark four agent architectures and six LLM backends on 20 incident scenarios of increasing complexity, identifying CyberSleuth as the best-performing design. In a separate set of 10 incidents from 2025, CyberSleuth correctly identifies the exact CVE in 80% of cases. At last, we conduct a human study with 22 experts, which rated the reports of CyberSleuth as complete, useful, and coherent. They also expressed a slight preference for DeepSeek R1, a good news for open source LLM. To foster progress in defensive LLM research, we release both our benchmark and the CyberSleuth platform as a foundation for fair, reproducible evaluation of forensic agents.

[Arxiv](https://arxiv.org/abs/2508.20643)