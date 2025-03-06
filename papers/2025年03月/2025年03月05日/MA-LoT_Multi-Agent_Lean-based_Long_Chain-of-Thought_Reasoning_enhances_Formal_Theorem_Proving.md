# MA-LoT：多智能体 Lean 驱动的长链式推理助力形式定理证明的提升

发布时间：2025年03月05日

`LLM应用` `定理证明`

> MA-LoT: Multi-Agent Lean-based Long Chain-of-Thought Reasoning enhances Formal Theorem Proving

# 摘要

> 利用 Lean 等计算机可验证语言解决数学问题，已在数学与计算机科学领域掀起波澜。当前最先进的方法主要依赖单一大型语言模型（LLMs）作为代理或证明器，用于生成完整证明或执行树搜索。然而，单智能体方法在将自然语言（NL）的高层推理与形式语言（FL）验证反馈相结合方面存在天然缺陷。为突破这一限制，我们提出 MA-LoT：一种基于 Lean 的多智能体长链式思维框架（据我们所知），这是首个专为 Lean4 定理证明设计的多智能体框架，在长链式思维中实现了自然语言推理与形式语言验证的完美平衡。通过这种创新的交互方式，我们的方法在证明生成过程中实现了更深层次的洞察力和长期连贯性，而这正是传统方法难以企及的。我们借助新兴的长链式思维中形式推理能力，结合我们的创新 LoT-Transfer Learning 训练推理流水线来实现这一目标。实验结果表明，我们的框架在 Lean4 版本的 MiniF2F-Test 数据集上达到了 54.51% 的准确率，远超 GPT-4（22.95%）、单智能体树搜索（InternLM-Step-Prover，50.70%）和完整证明生成（DeepSeek-Prover-v1.5，48.36%）的基线表现。这一成果不仅展示了多智能体协作的强大能力，更揭示了将长链式思维与形式验证相结合在更广泛视角下生成更深入见解的巨大潜力。

> Solving mathematical problems using computer-verifiable languages like Lean has significantly impacted mathematical and computer science communities. State-of-the-art methods utilize single Large Language Models (LLMs) as agents or provers to either generate complete proof or perform tree searches. However, single-agent methods inherently lack a structured way to combine high-level reasoning in Natural Language (NL) with Formal Language (FL) verification feedback. To solve these issues, we propose MA-LoT: Multi-Agent Lean-based Long Chain-of-Thought framework, (to the best of our knowledge), the first multi-agent framework for Lean4 theorem proving that balance high-level NL reasoning and FL verification in Long CoT. Using this structured interaction, our approach enables deeper insights and long-term coherence in proof generation, with which past methods struggle. We do this by leveraging emergent formal reasoning ability in Long CoT using our novel LoT-Transfer Learning training-inference pipeline. Extensive experiments show that our framework achieves 54.51% accuracy rate on the Lean4 version of MiniF2F-Test dataset, largely outperforming GPT-4 (22.95%), single-agent tree search (InternLM-Step-Prover, 50.70%), and whole-proof generation (DeepSeek-Prover-v1.5, 48.36%) baselines. Furthermore, our findings highlight the potential of combining Long CoT with formal verification for a more insightful generation in a broader perspective.

[Arxiv](https://arxiv.org/abs/2503.03205)