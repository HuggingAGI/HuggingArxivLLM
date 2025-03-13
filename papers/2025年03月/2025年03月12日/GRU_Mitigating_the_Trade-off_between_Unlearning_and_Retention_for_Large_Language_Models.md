# # GRU：解决大型语言模型中遗忘与保留的权衡

发布时间：2025年03月12日

`LLM理论` `数据隐私保护`

> GRU: Mitigating the Trade-off between Unlearning and Retention for Large Language Models

# 摘要

> 大型语言模型（LLM）的遗忘机制在移除隐私和版权相关内容方面发挥关键作用，对合法安全应用至关重要。然而，完全遗忘通常需要在模型功能上做出妥协，导致遗忘与保留之间的权衡。通过分析遗忘的动态更新过程，我们发现梯度中蕴含了揭示这一权衡的重要信息。特别地，我们研究了在遗忘过程中保留性能与梯度方向差异的关系，这启发我们设计了一种基于两种来源梯度的更新机制——对保留有害但对遗忘有益的梯度。为此，我们提出了梯度修正遗忘（GRU），一个增强的遗忘框架。GRU通过几何聚焦和优化驱动的方式控制更新梯度，最小化其对其他无关响应的副作用。具体而言，GRU推导出一种闭式解，将遗忘梯度投影到对保留有害梯度的正交空间中，在保证整体性能保留的前提下，确保方向偏离最小。通过全面实验，我们证明了GRU作为一种通用框架，易于实现，并通过其灵活和兼容的特性，能够有效提升一系列基线方法。此外，实验结果表明，GRU在LLM遗忘的一系列多样化基准测试中表现出了广泛有效性。

> Large language model (LLM) unlearning has demonstrated its essential role in removing privacy and copyright-related responses, crucial for their legal and safe applications. However, the pursuit of complete unlearning often comes with substantial costs due to its compromises in their general functionality, leading to a notorious trade-off between unlearning and retention. In examining the update process for unlearning dynamically, we find gradients hold essential information for revealing this trade-off. In particular, we look at the varying relationship between retention performance and directional disparities between gradients during unlearning. It motivates the sculpting of an update mechanism derived from gradients from two sources, i.e., harmful for retention and useful for unlearning. Accordingly, we propose Gradient Rectified Unlearning (GRU), an enhanced unlearning framework controlling the updating gradients in a geometry-focused and optimization-driven manner such that their side impacts on other, unrelated responses can be minimized. Specifically, GRU derives a closed-form solution to project the unlearning gradient onto the orthogonal space of that gradient harmful for retention, ensuring minimal deviation from its original direction under the condition that overall performance is retained. Comprehensive experiments are conducted to demonstrate that GRU, as a general framework, is straightforward to implement and efficiently enhances a range of baseline methods through its adaptable and compatible characteristics. Additionally, experimental results show its broad effectiveness across a diverse set of benchmarks for LLM unlearning.

[Arxiv](https://arxiv.org/abs/2503.09117)