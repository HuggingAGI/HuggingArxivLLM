# 利用 LLM 增强的代理对博弈论场景进行自动形式化与模拟

发布时间：2024年12月11日

`Agent` `博弈论`

> Autoformalizing and Simulating Game-Theoretic Scenarios using LLM-augmented Agents

# 摘要

> 博弈论模拟是探索自然与人工代理相互作用的多用途工具。然而，为现实世界场景建模并开发模拟往往需要大量的人类专业知识和精力。为了简化这一流程，我们推出了一个框架，能借助由大型语言模型（LLMs）增强的代理来实现博弈论场景的自动形式化。在此方法中，LLM 增强的代理会把自然语言场景描述转化为可执行的逻辑程序，这些程序定义了每个游戏的规则，并对其语法准确性进行验证。接着开展锦标赛模拟，期间代理通过玩生成的游戏来测试其功能。若有真实的收益矩阵可用，还能进行精准的语义验证。经过验证的游戏可用于后续模拟，以评估不同策略的成效。我们在五个知名的 2x2 同步移动游戏的 55 种不同自然语言描述集合上对我们的方法进行了评估，生成的游戏规则中语法正确度达 96%，语义正确度达 87%。此外，我们还评估了 LLM 增强的代理自动形式化游戏策略的能力。

> Game-theoretic simulations are a versatile tool for exploring interactions of both natural and artificial agents. However, modelling real-world scenarios and developing simulations often require substantial human expertise and effort. To streamline this process, we present a framework that enables the autoformalization of game-theoretic scenarios using agents augmented by large language models (LLMs). In this approach, LLM-augmented agents translate natural language scenario descriptions into executable logic programs that define the rules of each game, validating these programs for syntactic accuracy. A tournament simulation is then conducted, during which the agents test the functionality of the generated games by playing them. When a ground truth payoff matrix is available, an exact semantic validation can also be performed. The validated games can then be used in further simulations to assess the effectiveness of different strategies. We evaluate our approach on a diverse set of 55 natural language descriptions across five well-known 2x2 simultaneous-move games, demonstrating 96% syntactic and 87% semantic correctness in the generated game rules. Additionally, we assess the LLM-augmented agents' capability to autoformalize strategies for gameplay.

[Arxiv](https://arxiv.org/abs/2412.08805)