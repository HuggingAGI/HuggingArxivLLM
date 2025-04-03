# 制定全局策略，灵活适应本地：一个多轮红队代理，结合双层学习机制

发布时间：2025年04月01日

`LLM应用` `模型安全`

> Strategize Globally, Adapt Locally: A Multi-Turn Red Teaming Agent with Dual-Level Learning

# 摘要

> 大型语言模型（LLMs）的恶意利用正带来日益严重的安全威胁，随着其能力的提升和普及，这一问题尤为突出。现有红队测试框架多聚焦于单轮攻击，但现实中，攻击者往往在多轮场景中逐步探测系统漏洞并调整攻击策略。针对这一挑战，我们提出了\AlgName，一种创新的多轮红队测试代理，通过全局战术式学习与局部提示式学习的结合，模拟复杂的攻击者行为。与传统依赖固定策略的多轮方法不同，\AlgName能够动态识别新战术、构建基于目标的战术选择框架，并持续优化提示公式。实验结果表明，在JailbreakBench测试中，\AlgName在5轮对话内对GPT-3.5-Turbo和Llama-3.1-70B实现了超过90%的攻击成功率，显著超越现有最优基线。这一成果充分证明了动态学习方法在多轮真实场景中识别和利用模型漏洞的显著优势。

> The exploitation of large language models (LLMs) for malicious purposes poses significant security risks as these models become more powerful and widespread. While most existing red-teaming frameworks focus on single-turn attacks, real-world adversaries typically operate in multi-turn scenarios, iteratively probing for vulnerabilities and adapting their prompts based on threat model responses. In this paper, we propose \AlgName, a novel multi-turn red-teaming agent that emulates sophisticated human attackers through complementary learning dimensions: global tactic-wise learning that accumulates knowledge over time and generalizes to new attack goals, and local prompt-wise learning that refines implementations for specific goals when initial attempts fail. Unlike previous multi-turn approaches that rely on fixed strategy sets, \AlgName enables the agent to identify new jailbreak tactics, develop a goal-based tactic selection framework, and refine prompt formulations for selected tactics. Empirical evaluations on JailbreakBench demonstrate our framework's superior performance, achieving over 90\% attack success rates against GPT-3.5-Turbo and Llama-3.1-70B within 5 conversation turns, outperforming state-of-the-art baselines. These results highlight the effectiveness of dynamic learning in identifying and exploiting model vulnerabilities in realistic multi-turn scenarios.

[Arxiv](https://arxiv.org/abs/2504.01278)