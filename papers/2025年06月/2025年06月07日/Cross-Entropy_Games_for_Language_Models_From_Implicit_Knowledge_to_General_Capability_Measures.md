# 语言模型中的交叉熵博弈：从隐性知识到通用能力评估

发布时间：2025年06月07日

`LLM理论` `人工智能` `游戏理论`

> Cross-Entropy Games for Language Models: From Implicit Knowledge to General Capability Measures

# 摘要

> 大型语言模型（LLMs）在文本上定义了概率测度。通过深入探讨LLM对这种测度的隐性知识及其算法内涵，我们提出了超越传统生成采样的多样化任务，包括摘要、反事实思考、异常检测、原创性搜索、逆向提示、辩论、创造性解决问题等形式。这些任务可以基于LLM测度形式化为游戏，我们将其命名为交叉熵（Xent）游戏。Xent游戏可以是单人或多人参与，涉及交叉熵分数和约束，并可表示为简单的计算图和程序。我们展示了Xent游戏空间广阔且充满趣味实例，同时可以从基本博弈论一致性公理构建。随后，我们探讨了如何利用Xent游戏空间衡量LLMs的能力，这引导我们构建了Xent游戏测度：从给定范围中提取覆盖测度构建的有限Xent游戏族，可用作能力基准。为解决测量通用能力相关的无界范围问题，我们建议采用受演化动力学启发的思路，以连贯方式探索Xent游戏空间。

> Large Language Models (LLMs) define probability measures on text. By considering the implicit knowledge question of what it means for an LLM to know such a measure and what it entails algorithmically, we are naturally led to formulate a series of tasks that go beyond generative sampling, involving forms of summarization, counterfactual thinking, anomaly detection, originality search, reverse prompting, debating, creative solving, etc. These tasks can be formulated as games based on LLM measures, which we call Cross-Entropy (Xent) Games. Xent Games can be single-player or multi-player. They involve cross-entropy scores and cross-entropy constraints, and can be expressed as simple computational graphs and programs. We show the Xent Game space is large enough to contain a wealth of interesting examples, while being constructible from basic game-theoretic consistency axioms. We then discuss how the Xent Game space can be used to measure the abilities of LLMs. This leads to the construction of Xent Game measures: finite families of Xent Games that can be used as capability benchmarks, built from a given scope, by extracting a covering measure. To address the unbounded scope problem associated with the challenge of measuring general abilities, we propose to explore the space of Xent Games in a coherent fashion, using ideas inspired by evolutionary dynamics.

[Arxiv](https://arxiv.org/abs/2506.06832)