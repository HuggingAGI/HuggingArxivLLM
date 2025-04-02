# 数字世界里的大型语言模型：一场快速的数值推理能力测试

发布时间：2025年03月31日

`LLM应用` `数学推理` `数值推理`

> Large Language Models in Numberland: A Quick Test of Their Numerical Reasoning Abilities

# 摘要

> 人类数学推理的核心是“数字感”——一种对数字及其关系的抽象理解，使我们能够利用有限资源解决涉及庞大数字空间的问题。大型语言模型（LLMs）的数学推理能力通常通过高水平问题（如数学竞赛题、几何题、文字题和谜题）来测试，但其低级数字感仍待进一步探索。我们推出“Numberland”，一个包含100个问题的测试集，旨在评估基于LLM的代理的数值推理能力。这些任务涵盖了基本运算、高级计算（例如指数运算、复数运算）、质数检测和24点游戏，旨在测试基础技能及其在解决复杂和不确定问题中的整合能力。我们评估了五款基于LLM的代理：OpenAI的o1和o1-mini、Google Gemini、Microsoft Copilot以及Anthropic Claude。它们在前三个允许确定性解题步骤的任务中得分74-95%。但在需要试错搜索的24点游戏中，表现下降至10-73%。我们进一步测试了24点游戏中的顶级解题者（o1，准确率为73%），在25个更难题目上，其得分降至27%，证实了搜索能力是主要瓶颈。这些结果，结合错误类型，揭示了LLMs数字推理能力的脆弱性，这在它们在高难度基准测试中的卓越表现下显得有些意外。LLMs数值推理的局限性凸显了简单、针对性测试的重要性，这些测试可用于评估和解释LLMs的数学技能，确保其安全使用。

> An essential element of human mathematical reasoning is our number sense -- an abstract understanding of numbers and their relationships -- which allows us to solve problems involving vast number spaces using limited computational resources. Mathematical reasoning of Large Language Models (LLMs) is often tested on high-level problems (such as Olympiad challenges, geometry, word problems, and puzzles), but their low-level number sense remains less explored. We introduce "Numberland," a 100-problem test to evaluate the numerical reasoning abilities of LLM-based agents. The tasks -- basic operations, advanced calculations (e.g., exponentiation, complex numbers), prime number checks, and the 24 game -- aim to test elementary skills and their integration in solving complex and uncertain problems. We evaluated five LLM-based agents: OpenAI's o1 and o1-mini, Google Gemini, Microsoft Copilot, and Anthropic Claude. They scored 74-95% on the first three tasks that allow deterministic steps to solutions. In the 24 game, which needs trial-and-error search, performance dropped to 10-73%. We tested the top 24 solver (o1 with 73% accuracy) on 25 harder problems, and its score fell to 27%, confirming search as a bottleneck. These results, along with the types of mistakes, suggest a fragile number of LLMs, which is a bit surprising given their prowess in challenging benchmarks. The limits of LLM numerical reasoning highlight the scope of simple, targeted tests to evaluate and explain LLM math skills to ensure safe use.

[Arxiv](https://arxiv.org/abs/2504.00226)