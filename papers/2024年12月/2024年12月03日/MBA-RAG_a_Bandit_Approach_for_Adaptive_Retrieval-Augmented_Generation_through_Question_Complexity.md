# MBA-RAG：一种基于问题复杂程度实现自适应检索增强生成的Bandit方法

发布时间：2024年12月03日

`RAG`

> MBA-RAG: a Bandit Approach for Adaptive Retrieval-Augmented Generation through Question Complexity

# 摘要

> 检索增强生成（RAG）在提升语言模型于知识密集型任务中的生成性能方面成效显著。然而，现有的 RAG 框架要么盲目检索，要么依赖僵化的单类分类器选取检索方法，致使在不同复杂程度的查询中效率低下、表现欠佳。为应对这些挑战，我们提出了基于强化学习的框架，能依据查询的复杂程度动态挑选最适宜的检索策略。% 我们的解决方案 我们的方法借助多臂老虎机算法，将每种检索方法视作独特的“臂”，通过平衡探索与利用来调整选择过程。另外，我们引入了动态奖励函数，在准确性和效率之间取得平衡，对需要更多检索步骤的方法予以惩罚，即便它们能得出正确结果。我们的方法在多个单跳和多跳数据集上取得了新的领先成果，同时降低了检索成本。我们的代码可在 https://github.com/FUTUREEEEEE/MBA 获取。

> Retrieval Augmented Generation (RAG) has proven to be highly effective in boosting the generative performance of language model in knowledge-intensive tasks. However, existing RAG framework either indiscriminately perform retrieval or rely on rigid single-class classifiers to select retrieval methods, leading to inefficiencies and suboptimal performance across queries of varying complexity. To address these challenges, we propose a reinforcement learning-based framework that dynamically selects the most suitable retrieval strategy based on query complexity. % our solution Our approach leverages a multi-armed bandit algorithm, which treats each retrieval method as a distinct ``arm'' and adapts the selection process by balancing exploration and exploitation. Additionally, we introduce a dynamic reward function that balances accuracy and efficiency, penalizing methods that require more retrieval steps, even if they lead to a correct result. Our method achieves new state of the art results on multiple single-hop and multi-hop datasets while reducing retrieval costs. Our code are available at https://github.com/FUTUREEEEEE/MBA .

[Arxiv](https://arxiv.org/abs/2412.01572)