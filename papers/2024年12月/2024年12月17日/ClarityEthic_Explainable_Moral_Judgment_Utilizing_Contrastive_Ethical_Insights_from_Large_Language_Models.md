# ClarityEthic：借助大型语言模型中的对比性伦理见解进行可解释的道德判断

发布时间：2024年12月17日

`LLM应用` `人工智能` `道德伦理`

> ClarityEthic: Explainable Moral Judgment Utilizing Contrastive Ethical Insights from Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的兴起与广泛应用，保障其安全性对于避免对人类造成危害以及推动道德行为至关重要。然而，借助大规模数据训练直接评估价值倾向（比如支持或反对）并不可信，也难以解释。我们认为，模仿人类依靠社会规范来做道德决策，能够助力 LLMs 理解和预测道德判断。但捕捉人类价值观仍是难题，因为在特定情境中，多个相关规范可能相互冲突。像大多数人所拥护且能促进社会福祉的规范（比如“不要作弊”），就更有可能被接受和广泛采用。所以，LLM 在做出道德决策前，确定特定场景下的恰当规范极为关键。为此，我们引入了一种新颖的道德判断方法，名为	extit{ClarityEthic}，它借助 LLMs 的推理能力和对比学习，从不同视角揭示人类行为的相关社会规范，并选出最可靠的规范以提升判断的准确性。大量实验表明，我们的方法在道德判断任务中优于前沿方法。此外，人类评估证实，生成的社会规范提供了合理的解释，支撑了判断。这表明，采用模仿人类道德策略来对人类道德判断进行建模，有望改善 LLMs 的道德行为。

> With the rise and widespread use of Large Language Models (LLMs), ensuring their safety is crucial to prevent harm to humans and promote ethical behaviors. However, directly assessing value valence (i.e., support or oppose) by leveraging large-scale data training is untrustworthy and inexplainable. We assume that emulating humans to rely on social norms to make moral decisions can help LLMs understand and predict moral judgment. However, capturing human values remains a challenge, as multiple related norms might conflict in specific contexts. Consider norms that are upheld by the majority and promote the well-being of society are more likely to be accepted and widely adopted (e.g., "don't cheat,"). Therefore, it is essential for LLM to identify the appropriate norms for a given scenario before making moral decisions. To this end, we introduce a novel moral judgment approach called \textit{ClarityEthic} that leverages LLMs' reasoning ability and contrastive learning to uncover relevant social norms for human actions from different perspectives and select the most reliable one to enhance judgment accuracy. Extensive experiments demonstrate that our method outperforms state-of-the-art approaches in moral judgment tasks. Moreover, human evaluations confirm that the generated social norms provide plausible explanations that support the judgments. This suggests that modeling human moral judgment with the emulating humans moral strategy is promising for improving the ethical behaviors of LLMs.

[Arxiv](https://arxiv.org/abs/2412.12848)