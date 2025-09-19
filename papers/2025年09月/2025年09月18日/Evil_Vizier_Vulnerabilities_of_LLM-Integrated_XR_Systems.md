# # 邪恶维齐尔：LLM集成XR系统的漏洞

发布时间：2025年09月18日

`LLM应用` `媒体与娱乐`

> Evil Vizier: Vulnerabilities of LLM-Integrated XR Systems

# 摘要

> 扩展现实（XR）应用正越来越多地集成大型语言模型（LLMs），以提升用户体验、增强场景理解，甚至生成可执行的XR内容，这类应用常被称为“AI眼镜”。尽管潜在优势显著，但XR-LLM集成管道却使XR应用面临新型攻击风险。本文从系统角度分析了文献与实践中的LLM集成XR系统，并沿不同维度对其进行分类。基于此分类，我们识别出通用威胁模型，并在多个采用不同LLM模型的XR平台（Meta Quest 3、Meta Ray-Ban、Android以及运行Llama和GPT模型的Microsoft HoloLens 2）上演示了一系列概念验证攻击。尽管这些平台的LLM集成方式各异，但均存在共同漏洞：攻击者可篡改合法LLM查询的公共上下文，导致用户收到错误的视觉或听觉反馈，进而危害其安全隐私、制造混乱或引发其他不良后果。为应对这些威胁，我们探讨了面向开发人员的缓解策略与最佳实践（包括初步防御原型），并呼吁社区研发新的保护机制以降低此类风险。

> Extended reality (XR) applications increasingly integrate Large Language Models (LLMs) to enhance user experience, scene understanding, and even generate executable XR content, and are often called "AI glasses". Despite these potential benefits, the integrated XR-LLM pipeline makes XR applications vulnerable to new forms of attacks. In this paper, we analyze LLM-Integated XR systems in the literature and in practice and categorize them along different dimensions from a systems perspective. Building on this categorization, we identify a common threat model and demonstrate a series of proof-of-concept attacks on multiple XR platforms that employ various LLM models (Meta Quest 3, Meta Ray-Ban, Android, and Microsoft HoloLens 2 running Llama and GPT models). Although these platforms each implement LLM integration differently, they share vulnerabilities where an attacker can modify the public context surrounding a legitimate LLM query, resulting in erroneous visual or auditory feedback to users, thus compromising their safety or privacy, sowing confusion, or other harmful effects. To defend against these threats, we discuss mitigation strategies and best practices for developers, including an initial defense prototype, and call on the community to develop new protection mechanisms to mitigate these risks.

[Arxiv](https://arxiv.org/abs/2509.15213)