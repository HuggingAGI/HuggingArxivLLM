# 常识的试金石：探索之路

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要探讨了如何通过公理化框架和常识测试来评估和构建安全且有益的人工智能系统，特别是针对大型语言模型（LLMs）的潜在问题和挑战。论文的核心内容涉及对LLMs的理论分析和测试方法的开发，旨在解决LLMs在处理新概念和避免欺骗性幻觉方面的局限性。因此，这篇论文更适合归类为LLM理论。` `人工智能`

> Towards A Litmus Test for Common Sense

# 摘要

> 本文是系列文章的第二篇，旨在探索一条通往安全且有益的人工智能之路。基于《常识即所需》的洞见，我们提出了一种更正式的常识测试方法，采用公理化框架，结合最小先验知识（MPK）约束与对角线或哥德尔式论证，设计出超越AI已知概念集的任务。我们探讨了该方法在抽象与推理语料库（ARC）中的应用，并考虑了训练/测试数据的限制、物理或虚拟体现以及大型语言模型（LLMs）的影响。此外，我们还关注了新兴的欺骗性幻觉现象，即更强大的AI系统可能故意生成看似合理但误导性的输出来掩盖知识空白。核心观点是，若在扩展AI时忽视常识，可能会加剧这种欺骗性倾向，从而危及安全与信任。与开发有益AI而不造成伤害的总体目标一致，我们的公理化测试不仅能够评估AI处理全新概念的能力，还为构建未来安全、有益且对齐的人工智能奠定了伦理与可靠的基础。

> This paper is the second in a planned series aimed at envisioning a path to safe and beneficial artificial intelligence. Building on the conceptual insights of "Common Sense Is All You Need," we propose a more formal litmus test for common sense, adopting an axiomatic approach that combines minimal prior knowledge (MPK) constraints with diagonal or Godel-style arguments to create tasks beyond the agent's known concept set. We discuss how this approach applies to the Abstraction and Reasoning Corpus (ARC), acknowledging training/test data constraints, physical or virtual embodiment, and large language models (LLMs). We also integrate observations regarding emergent deceptive hallucinations, in which more capable AI systems may intentionally fabricate plausible yet misleading outputs to disguise knowledge gaps. The overarching theme is that scaling AI without ensuring common sense risks intensifying such deceptive tendencies, thereby undermining safety and trust. Aligning with the broader goal of developing beneficial AI without causing harm, our axiomatic litmus test not only diagnoses whether an AI can handle truly novel concepts but also provides a stepping stone toward an ethical, reliable foundation for future safe, beneficial, and aligned artificial intelligence.

[Arxiv](https://arxiv.org/abs/2501.09913)