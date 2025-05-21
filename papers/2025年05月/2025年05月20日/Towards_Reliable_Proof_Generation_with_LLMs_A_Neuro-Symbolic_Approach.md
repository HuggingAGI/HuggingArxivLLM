# 迈向可靠证明生成：神经符号方法驱动的LLM探索

发布时间：2025年05月20日

`LLM应用`

> Towards Reliable Proof Generation with LLMs: A Neuro-Symbolic Approach

# 摘要

> 大型语言模型 (LLMs) 在需要严密逻辑推理的正式领域，如数学证明生成中表现欠佳。我们提出了一种结合 LLMs 生成优势与结构化组件的神经符号方法，以解决这一难题。以几何问题为例，我们的方法分为两步：(1) 检索类似问题并利用其证明引导 LLM；(2) 通过形式验证器评估证明并提供反馈，帮助模型修正错误。实验表明，我们的方法使 OpenAI o1 模型的证明准确率提升了 58%-70%。类似问题和验证器反馈均对提升效果起到了关键作用。更广泛地说，通过生成可证明正确结论的 LLM，我们有望显著提升其可靠性、准确性和一致性，解锁更多需要高度可信度的复杂任务与现实应用场景。

> Large language models (LLMs) struggle with formal domains that require rigorous logical deduction and symbolic reasoning, such as mathematical proof generation. We propose a neuro-symbolic approach that combines LLMs' generative strengths with structured components to overcome this challenge. As a proof-of-concept, we focus on geometry problems. Our approach is two-fold: (1) we retrieve analogous problems and use their proofs to guide the LLM, and (2) a formal verifier evaluates the generated proofs and provides feedback, helping the model fix incorrect proofs. We demonstrate that our method significantly improves proof accuracy for OpenAI's o1 model (58%-70% improvement); both analogous problems and the verifier's feedback contribute to these gains. More broadly, shifting to LLMs that generate provably correct conclusions could dramatically improve their reliability, accuracy and consistency, unlocking complex tasks and critical real-world applications that require trustworthiness.

[Arxiv](https://arxiv.org/abs/2505.14479)