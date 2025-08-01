# # 材料断裂预测的基础模型
大型语言模型（LLMs）在材料断裂预测领域的最新进展为从机器人流程自动化到智能体流程自动化的转变奠定了坚实基础，这一转变通过基于LLMs自动化工作流编排过程实现。

发布时间：2025年07月30日

`LLM应用` `材料科学` `机械工程`

> A Foundation Model for Material Fracture Prediction

# 摘要

> 精准预测材料失效的时间和方式，是设计安全可靠结构、机械系统和工程部件的关键。然而，面对真实应用中材料种类、几何形状和载荷条件的多样性，断裂行为的建模仍具挑战。尽管机器学习方法潜力巨大，但现有模型大多基于狭窄数据集，鲁棒性和泛化能力不足。基于物理的仿真器虽能提供高精度预测，但方法分散且计算资源消耗巨大。

我们提出了一种数据驱动的断裂预测基础模型，基于Transformer架构，支持跨仿真器、多材料（包括塑料粘结炸药、钢、铝、页岩和钨）及多样化载荷条件运行。模型兼容结构化与非结构化网格，并结合大型语言模型对材料属性、边界条件和求解器设置的文本输入进行嵌入处理。这种多模态输入设计使模型能够灵活适应各类仿真场景，无需更改架构。

该模型可微调以适应多种任务，包括失效时间估计、断裂演化建模及组合有限-离散元方法仿真。它还能推广到钛和混凝土等未见材料，仅需少量样本，大幅降低数据需求。我们的研究表明，断裂预测可统一在一个模型架构下，为传统仿真器工作流程提供了一种更高效、更具扩展性的替代方案。

> Accurately predicting when and how materials fail is critical to designing safe, reliable structures, mechanical systems, and engineered components that operate under stress. Yet, fracture behavior remains difficult to model across the diversity of materials, geometries, and loading conditions in real-world applications. While machine learning (ML) methods show promise, most models are trained on narrow datasets, lack robustness, and struggle to generalize. Meanwhile, physics-based simulators offer high-fidelity predictions but are fragmented across specialized methods and require substantial high-performance computing resources to explore the input space. To address these limitations, we present a data-driven foundation model for fracture prediction, a transformer-based architecture that operates across simulators, a wide range of materials (including plastic-bonded explosives, steel, aluminum, shale, and tungsten), and diverse loading conditions. The model supports both structured and unstructured meshes, combining them with large language model embeddings of textual input decks specifying material properties, boundary conditions, and solver settings. This multimodal input design enables flexible adaptation across simulation scenarios without changes to the model architecture. The trained model can be fine-tuned with minimal data on diverse downstream tasks, including time-to-failure estimation, modeling fracture evolution, and adapting to combined finite-discrete element method simulations. It also generalizes to unseen materials such as titanium and concrete, requiring as few as a single sample, dramatically reducing data needs compared to standard ML. Our results show that fracture prediction can be unified under a single model architecture, offering a scalable, extensible alternative to simulator-specific workflows.

[Arxiv](https://arxiv.org/abs/2507.23077)