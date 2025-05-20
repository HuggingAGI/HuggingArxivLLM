# # 单次主导：针对检索增强生成系统的知识投毒攻击研究

发布时间：2025年05月15日

`RAG` `大型语言模型`

> One Shot Dominance: Knowledge Poisoning Attack on Retrieval-Augmented Generation Systems

# 摘要

> 大型语言模型（LLMs）结合检索增强生成（RAG）后，生成准确回答的能力得到提升。然而，依赖外部知识库带来了安全风险，尤其是公开可修改的知识库。针对RAG系统知识库的投毒攻击面临两大挑战：恶意内容需与多个真实文档竞争，且LLMs更信任与其内部知识相符的信息。以往方法通过注入多个恶意文档应对，但这种饱和攻击易被检测且不切实际。为此，我们提出AuthChain，一种基于证据链理论和权威效应的新攻击方法，生成更具说服力的中毒文档。AuthChain建立有力证据链并融入权威声明，有效克服真实文档和LLMs内部知识的干扰。实验显示，与现有方法相比，AuthChain不仅攻击成功率显著提升，且在隐蔽性方面表现更优。

> Large Language Models (LLMs) enhanced with Retrieval-Augmented Generation (RAG) have shown improved performance in generating accurate responses. However, the dependence on external knowledge bases introduces potential security vulnerabilities, particularly when these knowledge bases are publicly accessible and modifiable. Poisoning attacks on knowledge bases for RAG systems face two fundamental challenges: the injected malicious content must compete with multiple authentic documents retrieved by the retriever, and LLMs tend to trust retrieved information that aligns with their internal memorized knowledge. Previous works attempt to address these challenges by injecting multiple malicious documents, but such saturation attacks are easily detectable and impractical in real-world scenarios. To enable the effective single document poisoning attack, we propose AuthChain, a novel knowledge poisoning attack method that leverages Chain-of-Evidence theory and authority effect to craft more convincing poisoned documents. AuthChain generates poisoned content that establishes strong evidence chains and incorporates authoritative statements, effectively overcoming the interference from both authentic documents and LLMs' internal knowledge. Extensive experiments across six popular LLMs demonstrate that AuthChain achieves significantly higher attack success rates while maintaining superior stealthiness against RAG defense mechanisms compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2505.11548)