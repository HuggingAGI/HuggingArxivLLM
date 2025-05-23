# 集合的和与差：超越AlphaEvolve的改进

发布时间：2025年05月21日

`其他` `计算机科学`

> Sums and differences of sets (improvement over AlphaEvolve)

# 摘要

> 2025年5月14日，DeepMind宣布，大型语言模型AlphaEvolve在数学问题上取得突破，在多个问题上达到了或超越了已知的最佳界限。特别是在集合和差问题中，AlphaEvolve通过一个包含54265个整数的集合，将下界从$θ=1.14465$提升至$θ=1.1584$。本文中，我们提出了一种更优的下界$θ=1.173050$，通过显式构造一个包含超过$10^{43546}$个元素的U集合实现。为了实现快速的整数和浮点数运算，我们采用了免费的GMP库。

> On May 14, 2025, DeepMind announced that AlphaEvolve, a large language model applied to a set of mathematical problems, had matched or exceeded the best known bounds on several problems. In the case of the sum and difference of sets problem, AlphaEvolve, using a set of $54265$ integers, improved the known lower bound of $θ=1.14465$ to $θ=1.1584$. In this paper, we present an improved bound $θ=1.173050$ using an explicit construction of a U set that contains more than $10^{43546}$ elements. For fast integer and floating-point arithmetic, we used the (free) GMP library.

[Arxiv](https://arxiv.org/abs/2505.16105)