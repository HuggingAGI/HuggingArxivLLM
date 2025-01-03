# 基于正则化松弛的大型语言模型对抗攻击

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要讨论的是大型语言模型（LLMs）的安全性，特别是对抗性攻击方法的改进。论文提出了一种新的对抗性攻击技术，通过结合正则化梯度和连续优化方法来提升攻击效率。这些内容属于对LLMs的理论研究和改进，因此归类为“LLM理论”。` `人工智能` `网络安全`

> Adversarial Attacks on Large Language Models Using Regularized Relaxation

# 摘要

> 随着大型语言模型（LLMs）在实际应用中的广泛使用，其安全性变得至关重要。尽管对齐技术显著提升了整体安全性，但LLMs仍易受精心设计的对抗性输入攻击。因此，对抗性攻击方法被广泛用于研究和理解这些漏洞。然而，现有攻击方法存在显著局限：基于离散标记优化的方法效率低下，而连续优化技术无法生成有效标记，难以应用于实际场景。本文提出了一种新的对抗性攻击技术，通过结合正则化梯度和连续优化方法，克服了这些限制。我们的方法比当前最先进的贪婪坐标梯度法快两个数量级，显著提升了对齐语言模型的攻击成功率，并生成了有效标记，解决了连续优化方法的关键缺陷。我们在四个数据集上对五个最先进的LLMs进行了实验，验证了该方法的有效性。

> As powerful Large Language Models (LLMs) are now widely used for numerous practical applications, their safety is of critical importance. While alignment techniques have significantly improved overall safety, LLMs remain vulnerable to carefully crafted adversarial inputs. Consequently, adversarial attack methods are extensively used to study and understand these vulnerabilities. However, current attack methods face significant limitations. Those relying on optimizing discrete tokens suffer from limited efficiency, while continuous optimization techniques fail to generate valid tokens from the model's vocabulary, rendering them impractical for real-world applications. In this paper, we propose a novel technique for adversarial attacks that overcomes these limitations by leveraging regularized gradients with continuous optimization methods. Our approach is two orders of magnitude faster than the state-of-the-art greedy coordinate gradient-based method, significantly improving the attack success rate on aligned language models. Moreover, it generates valid tokens, addressing a fundamental limitation of existing continuous optimization methods. We demonstrate the effectiveness of our attack on five state-of-the-art LLMs using four datasets.

[Arxiv](https://arxiv.org/abs/2410.19160)