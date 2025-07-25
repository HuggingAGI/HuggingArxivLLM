# 可解释映射器：通过扰动式解释与验证代理探索LLM嵌入空间

发布时间：2025年07月24日

`LLM理论` `拓扑学`

> Explainable Mapper: Charting LLM Embedding Spaces Using Perturbation-Based Explanation and Verification Agents

# 摘要

> 大型语言模型（LLMs）生成的高维嵌入能够捕捉词汇、句子和概念间的丰富语义与句法关系。通过mapper图研究LLM嵌入空间的拓扑结构，我们得以洞察其潜在的组织形式。具体而言，mapper图以图形形式呈现嵌入空间的拓扑结构，每个节点代表一个拓扑邻域（包含一组嵌入），若两个邻域存在重叠，则节点间以边相连。然而，手动探索这些嵌入空间以揭示其中的语言特性仍需大量的人力投入。为解决这一问题，我们提出了一套半自动标注框架，用于系统性地分析嵌入属性。首先，我们定义了mapper图中可探索的元素分类，包括节点、边、路径、组件和轨迹。标注过程借助两类可定制的基于LLM的代理完成，这些代理运用扰动技术实现高效自动化分析。这些代理不仅帮助我们探索和解释mapper元素的特征，还能验证生成解释的可靠性。我们在一个视觉分析工作区中实现了这一框架，并通过案例研究验证其有效性。特别地，我们复现了关于BERT嵌入属性在不同架构层的研究成果，并进一步揭示了拓扑邻域的语言特性。

> Large language models (LLMs) produce high-dimensional embeddings that capture rich semantic and syntactic relationships between words, sentences, and concepts. Investigating the topological structures of LLM embedding spaces via mapper graphs enables us to understand their underlying structures. Specifically, a mapper graph summarizes the topological structure of the embedding space, where each node represents a topological neighborhood (containing a cluster of embeddings), and an edge connects two nodes if their corresponding neighborhoods overlap. However, manually exploring these embedding spaces to uncover encoded linguistic properties requires considerable human effort. To address this challenge, we introduce a framework for semi-automatic annotation of these embedding properties. To organize the exploration process, we first define a taxonomy of explorable elements within a mapper graph such as nodes, edges, paths, components, and trajectories. The annotation of these elements is executed through two types of customizable LLM-based agents that employ perturbation techniques for scalable and automated analysis. These agents help to explore and explain the characteristics of mapper elements and verify the robustness of the generated explanations. We instantiate the framework within a visual analytics workspace and demonstrate its effectiveness through case studies. In particular, we replicate findings from prior research on BERT's embedding properties across various layers of its architecture and provide further observations into the linguistic properties of topological neighborhoods.

[Arxiv](https://arxiv.org/abs/2507.18607)