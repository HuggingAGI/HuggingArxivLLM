# 凸优化问题中 Clipped-SGD 在 $(L_0,L_1)$-光滑条件和重尾噪声下的收敛性研究

发布时间：2025年05月27日

`LLM理论` `机器学习`

> Convergence of Clipped-SGD for Convex $(L_0,L_1)$-Smooth Optimization with Heavy-Tailed Noise

# 摘要

> 梯度裁剪是机器学习和深度学习中广泛应用的技术，尤其在缓解大型语言模型训练中的重尾噪声方面效果显著。此外，在$(L_0,L_1)$-光滑性假设下，带裁剪的一阶方法（如Clip-SGD）相较于传统SGD展现出更强的收敛性保证，这一特性在众多深度学习任务中普遍存在。然而，Clip-SGD在重尾噪声与$(L_0,L_1)$-光滑性双重条件下的高概率收敛性尚未得到充分研究。本文首次针对凸$(L_0,L_1)$-光滑优化问题且存在重尾噪声的场景，为Clip-SGD建立了高概率收敛界限，填补了这一研究空白。我们的分析不仅涵盖了确定性情形和$L_1=0$的随机情形作为特例，从而复现了已知界限，还显著拓展了先前的研究成果。特别值得注意的是，我们的收敛速率避免了指数级增长因子，且不依赖于严格的次高斯噪声假设，这大大扩展了梯度裁剪技术的应用范围。

> Gradient clipping is a widely used technique in Machine Learning and Deep Learning (DL), known for its effectiveness in mitigating the impact of heavy-tailed noise, which frequently arises in the training of large language models. Additionally, first-order methods with clipping, such as Clip-SGD, exhibit stronger convergence guarantees than SGD under the $(L_0,L_1)$-smoothness assumption, a property observed in many DL tasks. However, the high-probability convergence of Clip-SGD under both assumptions -- heavy-tailed noise and $(L_0,L_1)$-smoothness -- has not been fully addressed in the literature. In this paper, we bridge this critical gap by establishing the first high-probability convergence bounds for Clip-SGD applied to convex $(L_0,L_1)$-smooth optimization with heavy-tailed noise. Our analysis extends prior results by recovering known bounds for the deterministic case and the stochastic setting with $L_1 = 0$ as special cases. Notably, our rates avoid exponentially large factors and do not rely on restrictive sub-Gaussian noise assumptions, significantly broadening the applicability of gradient clipping.

[Arxiv](https://arxiv.org/abs/2505.20817)