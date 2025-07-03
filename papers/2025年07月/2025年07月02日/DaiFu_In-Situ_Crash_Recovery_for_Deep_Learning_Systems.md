# DaiFu: 深度学习系统中的原位故障恢复技术

发布时间：2025年07月02日

`其他` `人工智能` `软件工程`

> DaiFu: In-Situ Crash Recovery for Deep Learning Systems

# 摘要

> 深度学习 (DL) 系统在各领域广泛应用，并因大型语言模型的兴起而愈发流行。然而，由于其复杂的软件架构，崩溃问题难以避免且频繁发生，严重浪费资源并阻碍开发效率。因此，高效的崩溃恢复至关重要。现有解决方案如检查点-重试机制对于小错误或暂时性错误导致的崩溃恢复过于笨重。为此，我们提出 DaiFu，一个针对 DL 系统的轻量级原位恢复框架。通过简单的代码转换，DaiFu 可在崩溃发生时即时拦截并动态更新运行上下文（如代码、配置等），实现快速恢复。实验表明，DaiFu 的恢复速度比现有方案快 1372 倍，且几乎无额外开销（低于 0.40%）。我们还构建了涵盖 7 种典型崩溃场景的基准测试，证实了 DaiFu 在各种情况下的有效性。

> Deep learning (DL) systems have been widely adopted in many areas, and are becoming even more popular with the emergence of large language models. However, due to the complex software stacks involved in their development and execution, crashes are unavoidable and common. Crashes severely waste computing resources and hinder development productivity, so efficient crash recovery is crucial. Existing solutions, such as checkpoint-retry, are too heavyweight for fast recovery from crashes caused by minor programming errors or transient runtime errors. Therefore, we present DaiFu, an in-situ recovery framework for DL systems. Through a lightweight code transformation to a given DL system, DaiFu augments it to intercept crashes in situ and enables dynamic and instant updates to its program running context (e.g., code, configurations, and other data) for agile crash recovery. Our evaluation shows that DaiFu helps reduce the restore time for crash recovery, achieving a 1372x speedup compared with state-of-the-art solutions. Meanwhile, the overhead of DaiFu is negligible (under 0.40%). We also construct a benchmark spanning 7 distinct crash scenarios in DL systems, and show the effectiveness of DaiFu in diverse situations.

[Arxiv](https://arxiv.org/abs/2507.01628)