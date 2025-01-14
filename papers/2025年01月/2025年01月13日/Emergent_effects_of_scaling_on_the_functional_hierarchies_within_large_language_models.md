# 扩展对大型语言模型内部功能层次结构的新兴影响

发布时间：2025年01月13日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLM）的内部工作机制，特别是不同层次在处理信息时的表现。研究通过实验分析了模型各层在编码信息时的行为，揭示了模型在处理抽象信息时的复杂性和波动性。这些内容属于对LLM内部结构和理论机制的探讨，因此归类为LLM理论。` `机器学习`

> Emergent effects of scaling on the functional hierarchies within large language models

# 摘要

> # 摘要
大型语言模型（LLM）的架构常被视为功能分层的：早期层处理语法，中间层解析语义，后期层整合信息。本研究重新探讨了这一观点。通过将简单文本（如“教堂和风琴”）输入LLM并提取激活，我们使用支持向量机和岭回归预测文本标签，以检验各层是否编码了特定信息。小型模型（Llama-3.2-3b；28层）的分析部分支持了分层观点：项目级语义在早期层（2-7层）最强，随后是两项关系（8-12层）和四项类比（10-15层）。随着层数加深，项目和简单关系的表示逐渐减少，深层更关注全局信息。然而，一些发现与稳定的层次观点相矛盾：首先，尽管深层能表示文档范围的抽象，但它们也会压缩上下文窗口早期部分的信息，缺乏有意义的抽象。其次，在更大模型（Llama-3.3-70b-Instruct）中，抽象水平出现显著波动：随着层数增加，两项关系和四项类比的表示先增后减，随后再次短暂增加。这一奇特模式在多个实验中一致出现。第三，扩展还带来了相邻层注意力机制之间的协调效应。在较大模型的多个实验中，相邻层在各自表示的信息上波动。总之，抽象层次虽常在层间显现，但大型模型也以奇特方式偏离了这一结构。

> Large language model (LLM) architectures are often described as functionally hierarchical: Early layers process syntax, middle layers begin to parse semantics, and late layers integrate information. The present work revisits these ideas. This research submits simple texts to an LLM (e.g., "A church and organ") and extracts the resulting activations. Then, for each layer, support vector machines and ridge regressions are fit to predict a text's label and thus examine whether a given layer encodes some information. Analyses using a small model (Llama-3.2-3b; 28 layers) partly bolster the common hierarchical perspective: Item-level semantics are most strongly represented early (layers 2-7), then two-item relations (layers 8-12), and then four-item analogies (layers 10-15). Afterward, the representation of items and simple relations gradually decreases in deeper layers that focus on more global information. However, several findings run counter to a steady hierarchy view: First, although deep layers can represent document-wide abstractions, deep layers also compress information from early portions of the context window without meaningful abstraction. Second, when examining a larger model (Llama-3.3-70b-Instruct), stark fluctuations in abstraction level appear: As depth increases, two-item relations and four-item analogies initially increase in their representation, then markedly decrease, and afterward increase again momentarily. This peculiar pattern consistently emerges across several experiments. Third, another emergent effect of scaling is coordination between the attention mechanisms of adjacent layers. Across multiple experiments using the larger model, adjacent layers fluctuate between what information they each specialize in representing. In sum, an abstraction hierarchy often manifests across layers, but large models also deviate from this structure in curious ways.

[Arxiv](https://arxiv.org/abs/2501.07359)