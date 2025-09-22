# # LoCaL：对抗代码评估指标的表面偏差

发布时间：2025年09月18日

`LLM应用` `基础理论`

> LoCaL: Countering Surface Bias in Code Evaluation Metrics

# 摘要

> 随着大型语言模型（LLMs）及基于LLM的智能体日益普及，可靠高效的代码评估指标（CEMs）已成为推动多项软件工程任务发展的关键。尽管主流基准测试常通过测试用例评估生成代码的正确性，但设计与执行测试用例的成本不菲。基于参考的CEMs则通过衡量候选程序与参考程序的功能相似性进行评分，成为一种更经济的替代方案。尽管已有研究指出这些CEMs与功能正确性的相关性较弱，但相关成因尚停留在假设阶段，可行的解决方案也未得到深入探索。本研究中，我们对四种最先进的基于参考的CEMs展开批判性评估，发现它们存在明显的“重表面特征、轻代码功能”倾向。然而，尽管存在这种表面偏差，现有CEMs评估数据集却鲜少纳入“表面相似但功能相异”或“功能相似但表面相异”的代码对。为填补这一空白，我们提出了CEM评估基准LoCaL（Looks Can Lie），涵盖方法级与程序级的3117个代码对。每个代码对均标注功能相似性分数，专门针对CEMs易出错的场景进行设计。功能相似性分数通过差异模糊测试得出，无需预定义测试用例，同时通过执行比以往研究多一个数量级的测试，提升了分数的可靠性。结果显示，与基准测试相比，这四种CEMs在LoCaL上的性能均显著下降。最后，基于研究结果，我们认为：让CEMs接触类似LoCaL的数据，或能推动抗表面偏差指标的研发。

> With the increasing popularity of large language models (LLMs) and LLM-based agents, reliable and effective code evaluation metrics (CEMs) have become crucial for progress across several software engineering tasks. While popular benchmarks often provide test cases to assess the correctness of generated code, crafting and executing test cases is expensive. Reference-based CEMs provide a cheaper alternative by scoring a candidate program based on its functional similarity to a reference. Although prior research has focused on reporting the weak correlation between these CEMs and functional correctness, the causes are only assumed, and plausible solutions remain unexplored. In this work, we critically evaluate four state-of-the-art reference-based CEMs, revealing their strong bias towards surface-level features rather than code functionality. Despite this surface bias, current evaluation datasets for these CEMs rarely include code pairs that are surface-similar yet functionally dissimilar, or functionally similar yet surface-dissimilar. To mitigate this gap, we propose LoCaL (Looks Can Lie), a CEM evaluation benchmark, with 3117 code pairs at both the method and program levels. Each pair is labeled with a functional similarity score and aims to target regions where CEMs are likely to perform poorly. The functional similarity scores are calculated through differential fuzzing, which eliminates the need for predefined test cases and, at the same time, improves the reliability of the scores by executing an order of magnitude more tests than prior work. We find that all four CEMs show significant performance degradation on LoCaL, compared to the baselines. Finally, based on our findings, we draw the implication that exposing CEMs to LoCaL-like data might facilitate the development of metrics that are robust to surface bias.

[Arxiv](https://arxiv.org/abs/2509.15397)