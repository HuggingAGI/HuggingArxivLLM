# 朝着更稳健的检索增强生成迈进：在对抗性中毒攻击的情况下评估 RAG

发布时间：2024年12月21日

`RAG` `信息检索` `语言模型`

> Towards More Robust Retrieval-Augmented Generation: Evaluating RAG Under Adversarial Poisoning Attacks

# 摘要

> 检索增强生成（RAG）系统已成为缓解大型语言模型（LLM）幻觉、提升其在知识密集领域表现的颇具前景的解决方案。然而，这类系统易受对抗性中毒攻击，恶意段落被注入检索数据库，可能误导模型生成错误的输出。在本文中，我们对 RAG 系统的检索和生成部分展开研究，以探究如何增强其抵御此类攻击的能力。从检索角度，我们剖析对抗性上下文被检索的缘由和方式，并评估所检索段落的质量对下游生成的影响。从生成角度，我们评估能否借助 LLM 的高级批判性思维和内部知识能力来减轻对抗性上下文的影响，比如将怀疑提示用作自卫机制。我们的实验和发现为设计更安全、更具韧性的检索增强框架提供了切实可行的见解，为其在现实应用中的可靠部署铺平了道路。

> Retrieval-Augmented Generation (RAG) systems have emerged as a promising solution to mitigate LLM hallucinations and enhance their performance in knowledge-intensive domains. However, these systems are vulnerable to adversarial poisoning attacks, where malicious passages injected into retrieval databases can mislead the model into generating factually incorrect outputs. In this paper, we investigate both the retrieval and the generation components of RAG systems to understand how to enhance their robustness against such attacks. From the retrieval perspective, we analyze why and how the adversarial contexts are retrieved and assess how the quality of the retrieved passages impacts downstream generation. From a generation perspective, we evaluate whether LLMs' advanced critical thinking and internal knowledge capabilities can be leveraged to mitigate the impact of adversarial contexts, i.e., using skeptical prompting as a self-defense mechanism. Our experiments and findings provide actionable insights into designing safer and more resilient retrieval-augmented frameworks, paving the way for their reliable deployment in real-world applications.

[Arxiv](https://arxiv.org/abs/2412.16708)