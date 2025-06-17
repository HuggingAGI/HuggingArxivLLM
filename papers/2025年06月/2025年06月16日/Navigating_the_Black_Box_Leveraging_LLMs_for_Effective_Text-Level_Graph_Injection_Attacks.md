# # 驾驭黑箱：利用LLMs实现高效文本级图注入攻击

发布时间：2025年06月16日

`LLM应用` `社交网络` `推荐系统`

> Navigating the Black Box: Leveraging LLMs for Effective Text-Level Graph Injection Attacks

# 摘要

> 文本属性图（TAGs）通过结合文本数据与图结构，在社交网络分析和推荐系统等领域提供独特见解。图神经网络（GNNs）擅长捕捉TAGs中的拓扑结构与文本信息，但其安全性面临挑战——容易受到对抗攻击。现有的图注入攻击（GIA）方法存在两大问题：一是假设攻击者可直接操控嵌入层，生成不可解释的节点嵌入；二是依赖高成本训练的替代模型。针对这些问题，我们提出了一种专为TAGs设计的黑盒GIA框架——ATAG-LLM。该方法创新性地利用大型语言模型（LLMs）直接生成可解释的文本级节点属性，确保攻击在现实场景中的可行性。我们设计了平衡探索与可靠性的LLM提示策略，有效指导文本生成。同时，提出了一种相似性评估方法，用于衡量攻击文本在破坏图同质性方面的效果。在严格的黑盒环境下，ATAG-LLM以极低的训练成本实现对目标节点的有效扰动，成功完成文本级图注入攻击。通过在真实TAG数据集上的实验，我们验证了ATAG-LLM相较于现有嵌入级和文本级攻击方法的显著优势。


> Text-attributed graphs (TAGs) integrate textual data with graph structures, providing valuable insights in applications such as social network analysis and recommendation systems. Graph Neural Networks (GNNs) effectively capture both topological structure and textual information in TAGs but are vulnerable to adversarial attacks. Existing graph injection attack (GIA) methods assume that attackers can directly manipulate the embedding layer, producing non-explainable node embeddings. Furthermore, the effectiveness of these attacks often relies on surrogate models with high training costs. Thus, this paper introduces ATAG-LLM, a novel black-box GIA framework tailored for TAGs. Our approach leverages large language models (LLMs) to generate interpretable text-level node attributes directly, ensuring attacks remain feasible in real-world scenarios. We design strategies for LLM prompting that balance exploration and reliability to guide text generation, and propose a similarity assessment method to evaluate attack text effectiveness in disrupting graph homophily. This method efficiently perturbs the target node with minimal training costs in a strict black-box setting, ensuring a text-level graph injection attack for TAGs. Experiments on real-world TAG datasets validate the superior performance of ATAG-LLM compared to state-of-the-art embedding-level and text-level attack methods.

[Arxiv](https://arxiv.org/abs/2506.13276)