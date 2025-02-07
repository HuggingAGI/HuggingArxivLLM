# 掌握 RoPEs：通过 STRING 优化 2D 和 3D 位置编码

发布时间：2025年02月04日

`LLM理论

理由：该论文主要介绍了一种新的位置编码方法STRING，并讨论了其在大型语言模型中的应用。虽然论文提到了在机器人技术中的应用，但其核心贡献是对位置编码方法的理论扩展和验证，这属于对大型语言模型的理论改进。因此，将其分类为LLM理论更为合适。` `机器人技术` `计算机视觉`

> Learning the RoPEs: Better 2D and 3D Position Encodings with STRING

# 摘要

> 我们推出了STRING：一种可分离的平移不变位置编码方法。STRING通过统一的理论框架扩展了旋转位置编码，后者是近期在大型语言模型中广泛应用的算法。STRING不仅保持了精确的平移不变性，支持任意维度的标记坐标，还确保了低计算成本。这些特性在机器人技术中尤为关键，因为高效的3D标记表示至关重要。我们将STRING应用于支持RGB(-D)输入（颜色加可选深度）的视觉Transformer中，显著提升了开放词汇对象检测和机器人控制器的性能。此外，我们通过严谨的数学分析验证了方法的普适性。

> We introduce STRING: Separable Translationally Invariant Position Encodings. STRING extends Rotary Position Encodings, a recently proposed and widely used algorithm in large language models, via a unifying theoretical framework. Importantly, STRING still provides exact translation invariance, including token coordinates of arbitrary dimensionality, whilst maintaining a low computational footprint. These properties are especially important in robotics, where efficient 3D token representation is key. We integrate STRING into Vision Transformers with RGB(-D) inputs (color plus optional depth), showing substantial gains, e.g. in open-vocabulary object detection and for robotics controllers. We complement our experiments with a rigorous mathematical analysis, proving the universality of our methods.

[Arxiv](https://arxiv.org/abs/2502.02562)