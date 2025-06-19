# DisProtEdit：多属性蛋白质编辑中的解纠缠表示探索

发布时间：2025年06月17日

`LLM应用` `生物技术` `蛋白质编辑`

> DisProtEdit: Exploring Disentangled Representations for Multi-Attribute Protein Editing

# 摘要

> 我们推出 DisProtEdit，一个可控的蛋白质编辑框架，它通过双通道自然语言监督学习，实现结构与功能属性的解纠缠表示。与传统方法依赖整体嵌入不同，DisProtEdit 独具匠心地分离语义因素，使编辑过程更加模块化和可解释。为此，我们打造了 SwissProtDis，一个大规模多模态数据集，每个蛋白质序列都配有结构和功能的双文本描述，由大型语言模型自动解析。DisProtEdit 采用对齐与均匀性目标，将蛋白质与文本嵌入精准匹配，同时通过解纠缠损失确保结构与功能语义的独立性。在实际应用中，只需修改文本输入并从更新的潜在表示中解码，即可实现蛋白质编辑。实验结果表明，DisProtEdit 不仅在性能上与现有方法比肩，更在可解释性和可控性上脱颖而出。特别是在我们新构建的多属性编辑基准测试中，该模型实现了高达 61.7% 的双命中成功率，充分展现了其在同步调整结构与功能方面的卓越能力。

> We introduce DisProtEdit, a controllable protein editing framework that leverages dual-channel natural language supervision to learn disentangled representations of structural and functional properties. Unlike prior approaches that rely on joint holistic embeddings, DisProtEdit explicitly separates semantic factors, enabling modular and interpretable control. To support this, we construct SwissProtDis, a large-scale multimodal dataset where each protein sequence is paired with two textual descriptions, one for structure and one for function, automatically decomposed using a large language model. DisProtEdit aligns protein and text embeddings using alignment and uniformity objectives, while a disentanglement loss promotes independence between structural and functional semantics. At inference time, protein editing is performed by modifying one or both text inputs and decoding from the updated latent representation. Experiments on protein editing and representation learning benchmarks demonstrate that DisProtEdit performs competitively with existing methods while providing improved interpretability and controllability. On a newly constructed multi-attribute editing benchmark, the model achieves a both-hit success rate of up to 61.7%, highlighting its effectiveness in coordinating simultaneous structural and functional edits.

[Arxiv](https://arxiv.org/abs/2506.14853)