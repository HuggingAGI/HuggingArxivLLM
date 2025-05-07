# RESAnything：助力任意引用分割的属性提示

发布时间：2025年05月03日

`LLM应用` `计算机视觉` `图像处理`

> RESAnything: Attribute Prompting for Arbitrary Referring Segmentation

# 摘要

> 我们提出了一种开放词汇、零样本的任意引用表达式分割（RES）方法，专注于处理比现有研究更为广泛的输入表达。具体而言，我们的输入不仅包括对象和部件级别的标签，还涵盖了指向对象/部件功能、设计、风格、材质等属性或特性的隐式引用。我们的模型RESAnything采用链式思考（CoT）推理，其核心思想是属性提示。通过系统性地提示大型语言模型（LLM），我们生成对象/部件属性的详细描述，包括形状、颜色和位置，从而为分割建议提供依据，而这些建议由基础图像分割模型生成。我们的方法鼓励对与功能、风格、设计等相关的对象或部件属性进行深入推理，使系统无需任何部件标注即可处理隐式查询。作为首个基于零样本和LLM的RES方法，RESAnything在传统RES基准上的零样本方法中表现显著优于其他方法，并在涉及隐式查询和复杂部件级别关系的具有挑战性的场景中大幅超越现有方法。最后，我们贡献了一个新的基准数据集，提供了约3000个精心策划的RES实例，以评估部件级别和任意RES解决方案。

> We present an open-vocabulary and zero-shot method for arbitrary referring expression segmentation (RES), targeting input expressions that are more general than what prior works were designed to handle. Specifically, our inputs encompass both object- and part-level labels as well as implicit references pointing to properties or qualities of object/part function, design, style, material, etc. Our model, coined RESAnything, leverages Chain-of-Thoughts (CoT) reasoning, where the key idea is attribute prompting. We generate detailed descriptions of object/part attributes including shape, color, and location for potential segment proposals through systematic prompting of a large language model (LLM), where the proposals are produced by a foundational image segmentation model. Our approach encourages deep reasoning about object or part attributes related to function, style, design, etc., enabling the system to handle implicit queries without any part annotations for training or fine-tuning. As the first zero-shot and LLM-based RES method, RESAnything achieves clearly superior performance among zero-shot methods on traditional RES benchmarks and significantly outperforms existing methods on challenging scenarios involving implicit queries and complex part-level relations. Finally, we contribute a new benchmark dataset to offer ~3K carefully curated RES instances to assess part-level, arbitrary RES solutions.

[Arxiv](https://arxiv.org/abs/2505.02867)