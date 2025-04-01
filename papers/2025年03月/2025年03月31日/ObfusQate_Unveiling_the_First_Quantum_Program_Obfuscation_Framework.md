# ObfusQate：揭秘首个量子程序混淆框架

发布时间：2025年03月31日

`其他` `量子计算` `安全性`

> ObfusQate: Unveiling the First Quantum Program Obfuscation Framework

# 摘要

> 本文介绍了一款名为ObfusQate的创新工具，它利用量子原语进行混淆，旨在增强经典和量子程序的安全性。我们设计并实现了两大类混淆方法，包括量子电路级混淆和代码级混淆，共计八种独特方法。量子电路级混淆基于量子门和电路，采用量子门隐藏和单位矩阵等策略，构建复杂且难以理解的电路，有效隐藏核心功能，防止逆向工程，使底层代码难以解读。同时，代码级混淆通过量子不透明谓词操作程序操作的逻辑顺序，混淆执行路径，使程序行为更加难以预测和分析。此外，ObfusQate还可用于混淆恶意代码片段，使其更难被检测和分析。这些进展为探索量子混淆技术的潜力和局限性奠定了基础，使ObfusQate成为未来开发者在不断发展的软件开发领域中增强代码安全的宝贵工具。据我们所知，ObfusQate是首个利用量子原语构建自动混淆框架的开创性工作。安全评估表明，ObfusQate的混淆在时间和空间复杂度上具有多项式开销，同时保持代码行为不变。我们还通过将按键记录器嵌入Shor算法并使用ObfusQate进行混淆，展示了其在攻击性场景中的应用。实验结果表明，当前如GPT 4o、GPT o3 mini和Grok 3等大型语言模型在混淆后无法识别恶意按键记录器。

> This paper introduces ObfusQate, a novel tool that conducts obfuscations using quantum primitives to enhance the security of both classical and quantum programs. We have designed and implemented two primary categories of obfuscations: quantum circuit level obfuscation and code level obfuscation, encompassing a total of eight distinct methods. Quantum circuit-level obfuscation leverages on quantum gates and circuits, utilizing strategies such as quantum gate hiding and identity matrices to construct complex, non-intuitive circuits that effectively obscure core functionalities and resist reverse engineering, making the underlying code difficult to interpret. Meanwhile, code-level obfuscation manipulates the logical sequence of program operations through quantum-based opaque predicates, obfuscating execution paths and rendering program behavior more unpredictable and challenging to analyze. Additionally, ObfusQate can be used to obfuscate malicious code segments, making them harder to detect and analyze. These advancements establish a foundational framework for further exploration into the potential and limitations of quantum-based obfuscation techniques, positioning ObfusQate as a valuable tool for future developers to enhance code security in the evolving landscape of software development. To the best of our knowledge, ObfusQate represents the pioneering work in developing an automated framework for implementing obfuscations leveraging quantum primitives. Security evaluations show that obfuscations by ObfusQate maintain code behavior with polynomial overheads in space and time complexities. We have also demonstrated an offensive use case by embedding a keylogger into Shor's algorithm and obfuscating it using ObfusQate. Our results show that current Large language models like GPT 4o, GPT o3 mini and Grok 3 were not able to identify the malicious keylogger after obfuscation.

[Arxiv](https://arxiv.org/abs/2503.23785)