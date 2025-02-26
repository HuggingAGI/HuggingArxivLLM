# # 针对大型视觉语言模型的自监督学习视觉编码器中的隐蔽后门攻击研究

发布时间：2025年02月25日

`LLM理论` `视觉语言模型` `视觉编码器`

> Stealthy Backdoor Attack in Self-Supervised Learning Vision Encoders for Large Vision Language Models

# 摘要

> 自监督学习（SSL）视觉编码器通过学习高质量的图像表示，在大型视觉语言模型（LVLMs）视觉模态开发中发挥着核心作用。由于训练这些编码器成本高昂，预训练编码器被广泛共享并集成到众多LVLMs中，这些模型往往涉及重要安全或社会意义。我们发现，仅通过破坏视觉编码器，就可能在这些LVLMs中诱导出显著的视觉幻觉，构成新的后门威胁。由于编码器的共享特性，许多下游LVLMs可能继承这些后门行为，形成广泛传播的后门风险。为应对这一挑战，我们提出了BadVision，这是首个专门针对LVLMs自监督视觉编码器漏洞的方法，采用了创新的触发器优化和后门学习技术。我们对两类自监督编码器和LVLMs进行了全面测试，覆盖了八个基准数据集。实验结果表明，BadVision以超过99%的成功率诱导LVLMs产生攻击者指定的幻觉，同时保持了极高的隐蔽性，导致77.6%的视觉理解误差。值得注意的是，现有的最先进后门检测方法对我们的攻击束手无策。

> Self-supervised learning (SSL) vision encoders learn high-quality image representations and thus have become a vital part of developing vision modality of large vision language models (LVLMs). Due to the high cost of training such encoders, pre-trained encoders are widely shared and deployed into many LVLMs, which are security-critical or bear societal significance. Under this practical scenario, we reveal a new backdoor threat that significant visual hallucinations can be induced into these LVLMs by merely compromising vision encoders. Because of the sharing and reuse of these encoders, many downstream LVLMs may inherit backdoor behaviors from encoders, leading to widespread backdoors. In this work, we propose BadVision, the first method to exploit this vulnerability in SSL vision encoders for LVLMs with novel trigger optimization and backdoor learning techniques. We evaluate BadVision on two types of SSL encoders and LVLMs across eight benchmarks. We show that BadVision effectively drives the LVLMs to attacker-chosen hallucination with over 99% attack success rate, causing a 77.6% relative visual understanding error while maintaining the stealthiness. SoTA backdoor detection methods cannot detect our attack effectively.

[Arxiv](https://arxiv.org/abs/2502.18290)