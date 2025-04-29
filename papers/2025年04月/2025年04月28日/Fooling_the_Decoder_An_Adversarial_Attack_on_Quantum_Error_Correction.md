# 欺骗解码器：对量子纠错的对抗攻击

发布时间：2025年04月28日

`其他` `量子计算` `量子信息处理`

> Fooling the Decoder: An Adversarial Attack on Quantum Error Correction

# 摘要

> 神经网络解码器在容错量子计算中日益重要，但对其工作原理的理解仍然不足，这限制了我们确保其可靠性和安全性。目前，机器学习解码器主要采用循环神经网络和变换模型（如AlphaQubit），强化学习（RL）在训练先进模型（如DeepSeek R1）中发挥关键作用。本研究聚焦于一种基础的RL表面代码解码器（DeepQ），首次实施针对量子错误校正的对抗攻击。通过应用前沿白盒攻击方法，我们发现了该解码器的漏洞，并成功实施了一种攻击，使内存实验中逻辑量子比特的寿命减少达五个数量级。我们的实验验证表明，此次攻击确实利用了真实存在的弱点：该解码器在噪声波动下表现出强健性，将负责终止回合的裁判解码器替换为MWPM解码器对其影响甚微，并在可检测码距下表现出容错特性。此次攻击不仅揭示了基于机器学习的QEC的脆弱性，也凸显了开发更健壮QEC方法的迫切需求。

> Neural network decoders are becoming essential for achieving fault-tolerant quantum computations. However, their internal mechanisms are poorly understood, hindering our ability to ensure their reliability and security against adversarial attacks. Leading machine learning decoders utilize recurrent and transformer models (e.g., AlphaQubit), with reinforcement learning (RL) playing a key role in training advanced transformer models (e.g., DeepSeek R1). In this work, we target a basic RL surface code decoder (DeepQ) to create the first adversarial attack on quantum error correction. By applying state-of-the-art white-box methods, we uncover vulnerabilities in this decoder, demonstrating an attack that reduces the logical qubit lifetime in memory experiments by up to five orders of magnitude. We validate that this attack exploits a genuine weakness, as the decoder exhibits robustness against noise fluctuations, is largely unaffected by substituting the referee decoder, responsible for episode termination, with an MWPM decoder, and demonstrates fault tolerance at checkable code distances. This attack highlights the susceptibility of machine learning-based QEC and underscores the importance of further research into robust QEC methods.

[Arxiv](https://arxiv.org/abs/2504.19651)