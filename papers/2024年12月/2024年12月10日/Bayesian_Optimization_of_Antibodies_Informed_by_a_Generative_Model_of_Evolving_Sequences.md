# 基于不断进化的序列生成模型为抗体进行贝叶斯优化

发布时间：2024年12月10日

`LLM应用`

> Bayesian Optimization of Antibodies Informed by a Generative Model of Evolving Sequences

# 摘要

> 为了打造有效的治疗手段，生物学家不断地对抗体序列进行变异，以增强结合力和稳定性。所提议的变异可以依据先前的测量结果，或者通过从大型抗体数据库中学习来预测典型抗体。然而，典型抗体的空间广阔，难以搜索，实验往往因预算有限而无法找到合适的抗体。我们推出了克隆信息贝叶斯优化（CloneBO），这是一种贝叶斯优化程序，它通过教导生成模型我们的免疫系统如何优化抗体，从而在实验室中高效地优化抗体。我们的免疫系统通过反复演化抗体序列的特定部分，以实现与目标的强力且稳定的结合，从而形成一组相关且不断演化的序列，即克隆家族。我们在数十万个克隆家族上训练了大型语言模型 CloneLM，并利用它来设计突变序列，这些突变最有可能在人类免疫系统内优化抗体。我们提议使用扭曲的顺序蒙特卡罗程序来引导我们的设计，使其符合先前的测量结果。我们发现，在现实的计算机模拟实验中，CloneBO 比以往方法更能有效地优化抗体，并且在体外湿实验室实验中设计出更强更稳定的结合剂。

> To build effective therapeutics, biologists iteratively mutate antibody sequences to improve binding and stability. Proposed mutations can be informed by previous measurements or by learning from large antibody databases to predict only typical antibodies. Unfortunately, the space of typical antibodies is enormous to search, and experiments often fail to find suitable antibodies on a budget. We introduce Clone-informed Bayesian Optimization (CloneBO), a Bayesian optimization procedure that efficiently optimizes antibodies in the lab by teaching a generative model how our immune system optimizes antibodies. Our immune system makes antibodies by iteratively evolving specific portions of their sequences to bind their target strongly and stably, resulting in a set of related, evolving sequences known as a clonal family. We train a large language model, CloneLM, on hundreds of thousands of clonal families and use it to design sequences with mutations that are most likely to optimize an antibody within the human immune system. We propose to guide our designs to fit previous measurements with a twisted sequential Monte Carlo procedure. We show that CloneBO optimizes antibodies substantially more efficiently than previous methods in realistic in silico experiments and designs stronger and more stable binders in in vitro wet lab experiments.

[Arxiv](https://arxiv.org/abs/2412.07763)