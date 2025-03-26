# SCI-IDEA: 基于Token和句子嵌入的上下文感知科学创意方法

发布时间：2025年03月24日

`LLM应用` `科学发现` `创意生成`

> SCI-IDEA: Context-Aware Scientific Ideation Using Token and Sentence Embeddings

# 摘要

> 科学发现的灵感往往源于先前的研究、跨学科融合与新兴挑战。近年来，基于科学文献训练的大型语言模型（LLMs）取得了显著进展，这激发了人们对AI辅助创意生成的兴趣。然而，如何生成具备上下文感知能力、高质量且富有创新性的想法仍然是一个难题。为此，我们提出了一种名为SCI-IDEA的框架，该框架通过迭代式想法精炼，结合了LLM提示策略和顿悟时刻检测技术。SCI-IDEA能够从研究文献中提取关键要素，并从新颖性、兴奋性、可行性和有效性四个方面评估生成的想法。通过全面的实验验证，SCI-IDEA展现出显著的有效性，在新颖性、兴奋性、可行性和有效性方面的平均得分分别为6.84、6.86、6.89和6.84（评分范围为1-10）。评估过程中采用了GPT-4o、GPT-4.5、DeepSeek-32B（均在2-shot提示下）和DeepSeek-70B（3-shot提示下），并使用了基于token的嵌入方法进行顿悟时刻检测。同时，在5-shot提示下使用GPT-4o，3-shot提示下使用GPT-4.5，零-shot链式思考提示下使用DeepSeek-32B，以及5-shot提示下使用DeepSeek-70B（基于句子嵌入），SCI-IDEA分别获得了6.87、6.86、6.83和6.87的得分。此外，我们还探讨了与SCI-IDEA相关的伦理问题，包括知识产权归属、潜在滥用以及人类创造力与AI驱动创意之间的平衡。我们的研究结果凸显了SCI-IDEA在支持结构化与灵活的上下文感知科学想法探索方面的潜力，同时在保持伦理标准的前提下推动创新。

> Every scientific discovery starts with an idea inspired by prior work, interdisciplinary concepts, and emerging challenges. Recent advancements in large language models (LLMs) trained on scientific corpora have driven interest in AI-supported idea generation. However, generating context-aware, high-quality, and innovative ideas remains challenging. We introduce SCI-IDEA, a framework that uses LLM prompting strategies and Aha Moment detection for iterative idea refinement. SCI-IDEA extracts essential facets from research publications, assessing generated ideas on novelty, excitement, feasibility, and effectiveness. Comprehensive experiments validate SCI-IDEA's effectiveness, achieving average scores of 6.84, 6.86, 6.89, and 6.84 (on a 1-10 scale) across novelty, excitement, feasibility, and effectiveness, respectively. Evaluations employed GPT-4o, GPT-4.5, DeepSeek-32B (each under 2-shot prompting), and DeepSeek-70B (3-shot prompting), with token-level embeddings used for Aha Moment detection. Similarly, it achieves scores of 6.87, 6.86, 6.83, and 6.87 using GPT-4o under 5-shot prompting, GPT-4.5 under 3-shot prompting, DeepSeek-32B under zero-shot chain-of-thought prompting, and DeepSeek-70B under 5-shot prompting with sentence-level embeddings. We also address ethical considerations such as intellectual credit, potential misuse, and balancing human creativity with AI-driven ideation. Our results highlight SCI-IDEA's potential to facilitate the structured and flexible exploration of context-aware scientific ideas, supporting innovation while maintaining ethical standards.

[Arxiv](https://arxiv.org/abs/2503.19257)