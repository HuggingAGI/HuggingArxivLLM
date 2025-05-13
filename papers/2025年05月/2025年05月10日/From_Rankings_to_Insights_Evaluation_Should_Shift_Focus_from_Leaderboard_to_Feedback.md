# 从排名到洞察：评估应从排行榜转向反馈

发布时间：2025年05月10日

`LLM应用

摘要讨论了评估大型语言模型的方法和工具，属于应用层面的探讨，因此归类为LLM应用。` `模型评估`

> From Rankings to Insights: Evaluation Should Shift Focus from Leaderboard to Feedback

# 摘要

> 自动评估基准（如MT-Bench、Arena-Hard和Auto-Arena）正逐渐成为评估大型语言模型（LLMs）的重要工具。然而，现有研究主要依赖有限数据和LLM作为评估者来近似人类对模型的排名，这一方法存在根本性问题。这些基准通常仅提供总体评分，局限于排行榜排名，无法为模型优化和分析提供有效反馈。因此，我们提倡将评估范式从近似人类排名转向提供具有分析价值的反馈。为此，我们推出了Feedbacker——一个提供全面细致评估结果的框架，帮助深入识别模型的优势与不足。Feedbacker由三部分组成：可扩展的树状查询分类构建器、自动化的查询生成方案，以及强大的可视化和分析工具。此外，我们提出了一种创新的评估方法：基于预比较的点式评估（PC2）。该方法通过预先比较辅助响应的差异，实现了配对评估的准确性，同时保持了点式评估的效率。最后，我们借助对17种主流LLMs的评估结果，展示了Feedbacker的实际应用，证明了其有效性和潜力。欢迎访问我们的项目主页https://liudan193.github.io/Feedbacker了解更多。

> Automatic evaluation benchmarks such as MT-Bench, Arena-Hard, and Auto-Arena are seeing growing adoption for the evaluation of Large Language Models (LLMs). Existing research has primarily focused on approximating human-based model rankings using limited data and LLM-as-a-Judge. However, the fundamental premise of these studies, which attempts to replicate human rankings, is flawed. Specifically, these benchmarks typically offer only overall scores, limiting their utility to leaderboard rankings, rather than providing feedback that can guide model optimization and support model profiling. Therefore, we advocate for an evaluation paradigm shift from approximating human-based model rankings to providing feedback with analytical value. To this end, we introduce Feedbacker, an evaluation framework that provides comprehensive and fine-grained results, thereby enabling thorough identification of a model's specific strengths and weaknesses. Such feedback not only supports the targeted optimization of the model but also enhances the understanding of its behavior. Feedbacker comprises three key components: an extensible tree-based query taxonomy builder, an automated query synthesis scheme, and a suite of visualization and analysis tools. Furthermore, we propose a novel LLM-as-a-Judge method: PC2 (Pre-Comparison-derived Criteria) pointwise evaluation. This method derives evaluation criteria by pre-comparing the differences between several auxiliary responses, achieving the accuracy of pairwise evaluation while maintaining the time complexity of pointwise evaluation. Finally, leveraging the evaluation results of 17 mainstream LLMs, we demonstrate the usage of Feedbacker and highlight its effectiveness and potential. Our homepage project is available at https://liudan193.github.io/Feedbacker.

[Arxiv](https://arxiv.org/abs/2505.06698)