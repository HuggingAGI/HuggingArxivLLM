# 大型语言模型：与生俱来的晶体结构生成器

发布时间：2025年02月28日

`LLM应用` `材料科学` `材料设计`

> Large Language Models Are Innate Crystal Structure Generators

# 摘要

> 晶体结构生成是材料发现的重要基石，它能够帮助我们预测具有理想特性的新型材料。现有方法通常通过在材料数据库上对大型语言模型（LLMs）进行大量微调来实现这一目标。然而，我们发现，即使不进行额外训练，预训练的LLMs本身就具备生成稳定晶体结构的能力。我们的创新框架MatLLMSearch巧妙地将预训练的LLMs与进化搜索算法相结合，取得了令人瞩目的成果：通过机器学习势能验证，我们实现了78.38%的亚稳态率，并通过量子力学计算，达到了31.7%的DFT验证稳定性，这些成绩甚至超越了专门的模型如CrystalTextLLM。除了在晶体结构生成方面的卓越表现，我们的框架还展现出极强的适应性，无需微调即可轻松应对多种材料设计任务，包括晶体结构预测以及变形能和体积模量等多目标优化。这些令人振奋的成果不仅确立了预训练LLMs在材料发现中的 versatile and effective地位，更为晶体结构生成开辟了新的研究方向，同时显著降低了计算开销并提升了研究的可访问性。

> Crystal structure generation is fundamental to materials discovery, enabling the prediction of novel materials with desired properties. While existing approaches leverage Large Language Models (LLMs) through extensive fine-tuning on materials databases, we show that pre-trained LLMs can inherently generate stable crystal structures without additional training. Our novel framework MatLLMSearch integrates pre-trained LLMs with evolutionary search algorithms, achieving a 78.38% metastable rate validated by machine learning interatomic potentials and 31.7% DFT-verified stability via quantum mechanical calculations, outperforming specialized models such as CrystalTextLLM. Beyond crystal structure generation, we further demonstrate that our framework can be readily adapted to diverse materials design tasks, including crystal structure prediction and multi-objective optimization of properties such as deformation energy and bulk modulus, all without fine-tuning. These results establish pre-trained LLMs as versatile and effective tools for materials discovery, opening up new venues for crystal structure generation with reduced computational overhead and broader accessibility.

[Arxiv](https://arxiv.org/abs/2502.20933)