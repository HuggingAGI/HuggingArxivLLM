# # 利用注意力机制研究参数化量子电路中的量子相变

发布时间：2025年06月07日

`LLM应用` `量子物理` `量子计算`

> Learning quantum phase transition in parametrized quantum circuits with an attention mechanism

# 摘要

> 多体量子态和量子相变的学习仍是量子多体物理中的重要挑战。经典机器学习方法在解决这些问题时展现出独特优势。我们提出了一种创新框架，绕过了传统方法中测量物理可观测量的步骤，而是直接学习参数化量子电路的参数。通过将大型语言模型（LLMs）中的注意力机制与变分自编码器（VAE）相结合，我们能够高效捕捉电路参数中的隐藏关联。这些关联使我们能够无监督地提取量子相变信息。此外，我们的VAE不仅充当参数化量子电路的经典表示，还能高效生成对应多体量子态，从而实现特定相位的量子态生成。我们成功将该框架应用于多种量子系统，展示了其广泛的适用性，尤其在识别拓扑量子相变方面表现卓越。

> Learning many-body quantum states and quantum phase transitions remains a major challenge in quantum many-body physics. Classical machine learning methods offer certain advantages in addressing these difficulties. In this work, we propose a novel framework that bypasses the need to measure physical observables by directly learning the parameters of parameterized quantum circuits. By integrating the attention mechanism from large language models (LLMs) with a variational autoencoder (VAE), we efficiently capture hidden correlations within the circuit parameters. These correlations allow us to extract information about quantum phase transitions in an unsupervised manner. Moreover, our VAE acts as a classical representation of parameterized quantum circuits and the corresponding many-body quantum states, enabling the efficient generation of quantum states associated with specific phases. We apply our framework to a variety of quantum systems and demonstrate its broad applicability, with particularly strong performance in identifying topological quantum phase transitions.

[Arxiv](https://arxiv.org/abs/2506.06678)