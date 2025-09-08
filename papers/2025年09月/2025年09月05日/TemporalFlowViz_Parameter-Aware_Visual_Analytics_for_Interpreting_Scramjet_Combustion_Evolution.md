# TemporalFlowViz：参数感知可视化分析助力超燃冲压发动机燃烧演化解析

发布时间：2025年09月05日

`其他` `工业与制造`

> TemporalFlowViz: Parameter-Aware Visual Analytics for Interpreting Scramjet Combustion Evolution

# 摘要

> 深入理解超燃冲压发动机内复杂的燃烧动力学机制，对推动高速推进技术发展至关重要。然而，模拟生成的时间流场数据规模庞大、维度高，给视觉解读、特征区分及跨案例对比带来了极大挑战。为此，本文提出TemporalFlowViz——一个参数感知的可视化分析工作流与系统，专门用于支持专家驱动的超燃冲压发动机燃烧模拟时间流场聚类、可视化及解读。该方法利用数百组初始条件各异的模拟燃烧案例，每组案例均生成时间序列的流场图像。通过预训练视觉Transformer提取这些帧的高维嵌入特征，再结合降维和基于密度的聚类方法揭示潜在燃烧模式，同时在嵌入空间中构建时间轨迹，以追踪各模拟案例随时间的演化过程。为衔接潜在特征表示与专家推理，领域专家为代表性聚类中心添加描述性标签进行标注。这些标注作为视觉语言模型的上下文提示，用于为单帧及完整模拟案例生成自然语言摘要。系统还支持基于参数的过滤、相似性案例检索及多视图协同探索，助力深入分析。通过两项专家参与的案例研究及专家反馈验证了TemporalFlowViz的有效性，结果表明该系统能有效促进假设生成、支持可解释的模式发现，并在大规模超燃冲压发动机燃烧分析中提升知识发现能力。

> Understanding the complex combustion dynamics within scramjet engines is critical for advancing high-speed propulsion technologies. However, the large scale and high dimensionality of simulation-generated temporal flow field data present significant challenges for visual interpretation, feature differentiation, and cross-case comparison. In this paper, we present TemporalFlowViz, a parameter-aware visual analytics workflow and system designed to support expert-driven clustering, visualization, and interpretation of temporal flow fields from scramjet combustion simulations. Our approach leverages hundreds of simulated combustion cases with varying initial conditions, each producing time-sequenced flow field images. We use pretrained Vision Transformers to extract high-dimensional embeddings from these frames, apply dimensionality reduction and density-based clustering to uncover latent combustion modes, and construct temporal trajectories in the embedding space to track the evolution of each simulation over time. To bridge the gap between latent representations and expert reasoning, domain specialists annotate representative cluster centroids with descriptive labels. These annotations are used as contextual prompts for a vision-language model, which generates natural-language summaries for individual frames and full simulation cases. The system also supports parameter-based filtering, similarity-based case retrieval, and coordinated multi-view exploration to facilitate in-depth analysis. We demonstrate the effectiveness of TemporalFlowViz through two expert-informed case studies and expert feedback, showing TemporalFlowViz enhances hypothesis generation, supports interpretable pattern discovery, and enhances knowledge discovery in large-scale scramjet combustion analysis.

[Arxiv](https://arxiv.org/abs/2509.04834)