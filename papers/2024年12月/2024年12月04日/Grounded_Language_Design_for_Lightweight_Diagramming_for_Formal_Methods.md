# 针对形式方法的轻量级图表绘制的基础语言设计

发布时间：2024年12月04日

`其他` `软件开发` `模型查找`

> Grounded Language Design for Lightweight Diagramming for Formal Methods

# 摘要

> 模型查找，就像 SAT 求解器及类似工具所展现的那样，应用广泛，不管是在嵌入场景中，还是作为独立工具。比如，像 Alloy 这类工具以 SAT 为目标，使用户能够逐步定义、探索、验证和诊断大量复杂系统的复杂规范。
  这些工具的关键在于包含一个可视化器，能让用户以图形方式探索生成的模型。然而，正如我们所表明的，对领域一无所知的默认可视化器毫无用处，甚至严重违背了展示和认知原则。在另一个极端，全面的可视化需要大量的精力以及指定者可能不具备的知识；它们还可能出现不良的故障模式（包括无声故障）。相反，我们需要一种语言来获取轻量级图表的关键领域信息。我们基于有关图表的认知科学文献和大量自定义可视化示例来设计语言。这确定了轻量级图表的关键要素。我们将其提炼为一小组正交的基本元素。我们扩展了一个类似 Alloy 的工具来支持这些基本元素。我们评估了生成图表的有效性，发现它们有助于推理。然后，我们将其与许多其他绘图语言和工具进行比较，表明这项工作定义了一个新的细分领域，它轻量、有效，并且遵循合理的原则。

> Model finding, as embodied by SAT solvers and similar tools, is used widely, both in embedding settings and as a tool in its own right. For instance, tools like Alloy target SAT to enable users to incrementally define, explore, verify, and diagnose sophisticated specifications for a large number of complex systems.
  These tools critically include a visualizer that lets users graphically explore these generated models. As we show, however, default visualizers, which know nothing about the domain, are unhelpful and even actively violate presentational and cognitive principles. At the other extreme, full-blown visualizations require significant effort as well as knowledge a specifier might not possess; they can also exhibit bad failure modes (including silent failure). Instead, we need a language to capture essential domain information for lightweight diagramming. We ground our language design in both the cognitive science literature on diagrams and on a large number of example custom visualizations. This identifies the key elements of lightweight diagrams. We distill these into a small set of orthogonal primitives. We extend an Alloy-like tool to support these primitives. We evaluate the effectiveness of the produced diagrams, finding them good for reasoning. We then compare this against many other drawing languages and tools to show that this work defines a new niche that is lightweight, effective, and driven by sound principles.

[Arxiv](https://arxiv.org/abs/2412.03310)