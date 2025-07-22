# LLM世界模型是心理层面的：输出层证据显示LLM机械推理中脆弱世界模型的使用

发布时间：2025年07月21日

`LLM理论` `认知科学`

> LLM world models are mental: Output layer evidence of brittle world model use in LLM mechanical reasoning

# 摘要

> 大型语言模型（LLMs）是通过构建和操作内部世界模型，还是仅仅依赖统计关联（以输出层标记概率表示）来完成任务？我们借鉴认知科学中关于人类心理模型的研究方法，使用TikZ渲染的刺激物对LLMs进行滑轮系统问题的测试。研究1探讨了LLMs是否能够估计机械优势（MA）。结果显示，最先进的模型表现略高于随机水平，且其估计值与真实MA显著相关。滑轮数量与模型估计值之间的显著相关性表明，模型采用了滑轮计数的启发式方法，而无需模拟滑轮系统以获得精确值。研究2通过测试LLMs是否表示对MA估计至关重要的全局特征来进一步检验这一假设。模型评估了一个功能连接的滑轮系统与一个随机放置组件的假系统。在没有明确提示的情况下，模型以F1=0.8的准确率将功能系统识别为具有更大的MA，这表明LLMs能够很好地表示系统，从而区分杂乱无章与功能系统。研究3在此基础上，要求LLMs比较功能系统与匹配系统（后者连接但不将力传递到重量上）；然而，LLMs以F1=0.46的准确率识别功能系统，这表明其表现接近随机猜测。从某种意义上说，这些发现与LLMs操纵内部世界模型的观点相一致，这些模型足以利用滑轮数量与MA之间的统计关联（研究1），并近似表示系统组件的空间关系（研究2）。然而，它们可能缺乏推理复杂结构连接的能力（研究3）。我们最后强调认知科学方法在评估人工智能系统世界建模能力方面的实用性。

> Do large language models (LLMs) construct and manipulate internal world models, or do they rely solely on statistical associations represented as output layer token probabilities? We adapt cognitive science methodologies from human mental models research to test LLMs on pulley system problems using TikZ-rendered stimuli. Study 1 examines whether LLMs can estimate mechanical advantage (MA). State-of-the-art models performed marginally but significantly above chance, and their estimates correlated significantly with ground-truth MA. Significant correlations between number of pulleys and model estimates suggest that models employed a pulley counting heuristic, without necessarily simulating pulley systems to derive precise values. Study 2 tested this by probing whether LLMs represent global features crucial to MA estimation. Models evaluated a functionally connected pulley system against a fake system with randomly placed components. Without explicit cues, models identified the functional system as having greater MA with F1=0.8, suggesting LLMs could represent systems well enough to differentiate jumbled from functional systems. Study 3 built on this by asking LLMs to compare functional systems with matched systems which were connected up but which transferred no force to the weight; LLMs identified the functional system with F1=0.46, suggesting random guessing. Insofar as they may generalize, these findings are compatible with the notion that LLMs manipulate internal world models, sufficient to exploit statistical associations between pulley count and MA (Study 1), and to approximately represent system components' spatial relations (Study 2). However, they may lack the facility to reason over nuanced structural connectivity (Study 3). We conclude by advocating the utility of cognitive scientific methods to evaluate the world-modeling capacities of artificial intelligence systems.

[Arxiv](https://arxiv.org/abs/2507.15521)