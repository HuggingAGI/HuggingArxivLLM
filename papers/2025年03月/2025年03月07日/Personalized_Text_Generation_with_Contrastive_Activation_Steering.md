# 个性化文本生成：基于对比激活引导

发布时间：2025年03月07日

`LLM应用` `内容创作`

> Personalized Text Generation with Contrastive Activation Steering

# 摘要

> 个性化文本生成的目标是从用户的过往文本中捕捉其独特的写作风格，并生成忠实反映这些风格特征的文本。目前，主要采用检索增强生成（RAG）和参数高效微调（PEFT）两大技术路线。尽管这些方法推动了领域的发展，但仍面临两大挑战：(1) 过往文本中内容语义与风格特征的混杂使得准确建模用户写作风格变得困难；(2) RAG的检索操作导致推理延迟，PEFT则需要为每个用户存储大量参数，限制了其扩展性。为解决这些问题，我们提出了StyleVector框架。该框架无需额外训练，通过在LLM的激活空间中将个性化写作风格解耦并表示为一个向量，实现了无需检索或存储参数的风格引导生成。实验结果表明，与PEFT方法相比，StyleVector在个性化生成质量上提升了8%，同时将存储需求降低了1700倍。

> Personalized text generation aims to infer users' writing style preferences from their historical texts and generate outputs that faithfully reflect these stylistic characteristics. Existing solutions primarily adopt two paradigms: retrieval-augmented generation (RAG) and parameter-efficient fine-tuning (PEFT). While these approaches have advanced the field, they suffer from two critical limitations: (1) the entanglement of content semantics and stylistic patterns in historical texts impedes accurate modeling of user-specific writing preferences; and (2) scalability challenges arising from both RAG's inference latency by retrieval operations and PEFT's parameter storage requirements for per user model. To overcome these limitations, we propose StyleVector, a training-free framework that disentangles and represents personalized writing style as a vector in LLM's activation space, enabling style-steered generation during inference without requiring costly retrieval or parameter storage. Comprehensive experiments demonstrate that our framework achieves a significant 8% relative improvement in personalized generation while reducing storage requirements by 1700 times over PEFT method.

[Arxiv](https://arxiv.org/abs/2503.05213)