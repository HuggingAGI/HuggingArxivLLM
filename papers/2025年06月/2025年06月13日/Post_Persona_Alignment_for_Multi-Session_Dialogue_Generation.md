# 多轮对话生成中的角色动态调整方法

发布时间：2025年06月13日

`LLM应用` `对话生成` `人机交互`

> Post Persona Alignment for Multi-Session Dialogue Generation

# 摘要

> 多话轮人设对话生成在保持长期一致性和生成多样化、个性化的回复方面面临挑战。虽然大型语言模型（LLMs）在单话轮对话中表现出色，但难以在长期交互中保持人设真实性和对话连贯性。现有方法通常在生成回复前检索人设信息，这可能限制多样性并导致通用输出。我们提出Post Persona Alignment（PPA），一个创新的两阶段框架，逆转了这一过程。PPA首先仅基于对话上下文生成通用回复，然后用回复作为查询检索相关人设记忆，最后根据发言者人设调整回复。这种事后对齐策略在保持一致性和个性化的同时，促进了自然性和多样性。在多话轮LLM生成对话数据上的实验表明，PPA在一致性、多样性和人设相关性方面显著优于先前方法，为长期个性化对话生成提供了一个更灵活有效的范式。

> Multi-session persona-based dialogue generation presents challenges in maintaining long-term consistency and generating diverse, personalized responses. While large language models (LLMs) excel in single-session dialogues, they struggle to preserve persona fidelity and conversational coherence across extended interactions. Existing methods typically retrieve persona information before response generation, which can constrain diversity and result in generic outputs. We propose Post Persona Alignment (PPA), a novel two-stage framework that reverses this process. PPA first generates a general response based solely on dialogue context, then retrieves relevant persona memories using the response as a query, and finally refines the response to align with the speaker's persona. This post-hoc alignment strategy promotes naturalness and diversity while preserving consistency and personalization. Experiments on multi-session LLM-generated dialogue data demonstrate that PPA significantly outperforms prior approaches in consistency, diversity, and persona relevance, offering a more flexible and effective paradigm for long-term personalized dialogue generation.

[Arxiv](https://arxiv.org/abs/2506.11857)