# # 基于物理引擎的软件系统运行时故障排查：我们能探索多远？

发布时间：2025年07月29日

`其他` `物理引擎` `安全关键系统`

> Runtime Failure Hunting for Physics Engine Based Software Systems: How Far Can We Go?

# 摘要

> 物理引擎（PEs）是模拟物理交互的核心软件框架，广泛应用于娱乐到安全关键系统的多个领域。尽管其重要性不言而喻，物理引擎仍面临物理故障问题，这些故障可能导致软件可靠性下降、用户体验受损，甚至在自动驾驶汽车或医疗机器人中引发严重故障。当前针对基于物理引擎软件的测试方法存在局限性，通常需要白盒访问权限，并且主要关注于崩溃检测，而非语义复杂的物理故障。本文首次提出了一项大规模实证研究，旨在表征基于物理引擎软件中的物理故障。我们探讨了三个关键问题：物理故障的表现形式、检测技术的有效性以及开发者对当前检测实践的看法。我们的主要贡献包括：（1）构建了物理故障表现形式的分类体系；（2）对深度学习、基于提示的技术以及大型多模态模型等多种检测方法进行了全面评估；（3）从开发者经验中提炼出实际可行的见解，以改进检测方法。为了支持未来研究，我们公开了PhysiXFails数据集、代码及其他资源，访问地址为https://sites.google.com/view/physics-failure-detection。

> Physics Engines (PEs) are fundamental software frameworks that simulate physical interactions in applications ranging from entertainment to safety-critical systems. Despite their importance, PEs suffer from physics failures, deviations from expected physical behaviors that can compromise software reliability, degrade user experience, and potentially cause critical failures in autonomous vehicles or medical robotics. Current testing approaches for PE-based software are inadequate, typically requiring white-box access and focusing on crash detection rather than semantically complex physics failures. This paper presents the first large-scale empirical study characterizing physics failures in PE-based software. We investigate three research questions addressing the manifestations of physics failures, the effectiveness of detection techniques, and developer perceptions of current detection practices. Our contributions include: (1) a taxonomy of physics failure manifestations; (2) a comprehensive evaluation of detection methods including deep learning, prompt-based techniques, and large multimodal models; and (3) actionable insights from developer experiences for improving detection approaches. To support future research, we release PhysiXFails, code, and other materials at https://sites.google.com/view/physics-failure-detection.

[Arxiv](https://arxiv.org/abs/2507.22099)