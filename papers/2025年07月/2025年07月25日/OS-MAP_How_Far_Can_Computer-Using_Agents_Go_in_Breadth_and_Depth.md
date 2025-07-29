# OS-MAP: 使用计算机的智能体在广度和深度上究竟能走多远？

发布时间：2025年07月25日

`Agent` `人工智能` `自动化`

> OS-MAP: How Far Can Computer-Using Agents Go in Breadth and Depth?

# 摘要

> 计算机使用智能体在提升人类生产力和跨平台实现新应用形式方面展现出巨大潜力。尽管 recent advances 已经带来了可用的应用，现有的基准测试未能考虑到内部任务异质性以及相应的智能体能力，同时这些基准也未能与实际用户需求对齐——这阻碍了有针对性的能力开发以及研究进展向实际部署的可靠过渡。为了弥补这一差距，我们提出了 OS-MAP，这是一个日常计算机使用自动化的基准测试。它将 416 个现实任务分布在 15 个应用程序中，依据两个关键维度进行组织：一个五级自动化的分类法，以及从真实世界用户需求层次结构中衍生出的泛化范围。为了实现对所需能力的细粒度分析以及与现实场景的对齐，OS-MAP 从两个维度对智能体进行评估：五级分类法中的自动化水平，以及需求层次结构中的泛化范围。这种设计捕捉了智能体所需自主性和泛化能力的不同层次，形成了一个性能-泛化评估矩阵，用于结构化和全面的评估。实验表明，即使是具有 VLM 后端的 State-of-the-Art 智能体，在涉及感知、推理和协调的更高级任务上也显得力不从心——这凸显了对当前优势和局限性进行更深入理解的必要性，以推动计算机使用智能体研究和部署的未来进展。所有代码、环境、基线和数据均可在 https://github.com/OS-Copilot/OS-Map 公开获取。

> Computer-using agents have shown strong potential to boost human productivity and enable new application forms across platforms. While recent advances have led to usable applications, existing benchmarks fail to account for the internal task heterogeneity and the corresponding agent capabilities, as well as their alignment with actual user demands-hindering both targeted capability development and the reliable transition of research progress into practical deployment. To bridge the gap, we present OS-MAP, a benchmark for daily computer-using automation that organizes its 416 realistic tasks across 15 applications along two key dimensions: a five-level taxonomy of automation and a generalization scope derived from a real-world user demand hierarchy. To enable fine-grained analysis of required capabilities and alignment with real-world scenarios, OS-MAP evaluates agents along two dimensions: automation level across a five-level taxonomy, and generalization scope across a demand hierarchy. This design captures varying levels of required agent autonomy and generalization, forming a performance-generalization evaluation matrix for structured and comprehensive assessment. Experiments show that even State-of-the-Art agents with VLM backbones struggle with higher-level tasks involving perception, reasoning, and coordination-highlighting the need for a deeper understanding of current strengths and limitations to drive the future progress in computer-using agents research and deployment. All code, environments, baselines, and data are publicly available at https://github.com/OS-Copilot/OS-Map.

[Arxiv](https://arxiv.org/abs/2507.19132)