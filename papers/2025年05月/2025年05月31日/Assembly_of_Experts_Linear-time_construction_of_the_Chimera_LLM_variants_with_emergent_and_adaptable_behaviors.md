# 专家集合：组装具有涌现且可适应行为的混血大型语言模型变体，实现线性时间构建

发布时间：2025年05月31日

`LLM应用` `AI研究` `模型优化`

> Assembly of Experts: Linear-time construction of the Chimera LLM variants with emergent and adaptable behaviors

# 摘要

> 在 LLM 的预训练过程中，计算一个8位权重需要 $10^{13}$ 到 $10^{15}$ 次浮点运算，成本极高且效率低下。为了充分利用预训练模型的投入，我们提出了“专家组件”（Assembly-of-Experts, AoE）方法，能够在线性时间内从专家混合模型（Mixture-of-Experts）中生成功能强大的子模型。通过单独插值模型权重张量，可以增强或抑制父模型的语义特征。

调整从父模型中提取的权重比例时，我们发现 AoE 子模型的一些特性会逐渐变化，而其他行为特征则会突然显现。令人惊喜的是，几乎所有生成的模型都功能强大且有效，这使得模型搜索变得异常简单。

我们构建了 DeepSeek R1T“Chimera”，这是一个结合了 DeepSeek V3-0324 和 R1 模型的 671B 开源混合模型。尽管 Chimera 仅继承了 R1 的路由专家张量，但其智能水平接近 R1，同时输出令牌减少了约 40%，推理速度接近 V3。无需微调或蒸馏，Chimera 的推理过程相较于父模型更加紧凑有序。


> Requiring $10^{13}$-$10^{15}$ FLOPs to calculate one 8 bit weight in an LLM during pretraining is extremely expensive and seems inefficient. To better leverage the huge investments made into pretrained models, we develop the new "Assembly-of-Experts" (AoE) construction method to create capable child variants of existing Mixture-of-Experts parent models in linear time. Model weight tensors get interpolated individually, allowing to enhance or suppress semantic features of the parents.
  Varying the proportion of weights taken from the parent models, we observe some properties of the AoE child model changing gradually, while other behavioral traits emerge with a sharp transition. Surprisingly, nearly every generated model is functional and capable, which makes searching the model space straightforward.
  We construct the DeepSeek R1T "Chimera", a 671B open-weights hybrid model combining DeepSeek's V3-0324 and R1 model variants. The child inherits only the routed expert tensors of R1, but still achieves about R1-level intelligence. At the same time, it uses about 40\% fewer output tokens, close to V3 speed. Constructed without any fine-tuning or distillation, the Chimera exhibits surprisingly compact, orderly reasoning compared to its parent models.

[Arxiv](https://arxiv.org/abs/2506.14794)