# 自适应政治调查与GPT-4结合，通过模拟用户互动解决冷启动问题

发布时间：2025年03月12日

`LLM应用` `政治学` `调查方法`

> Adaptive political surveys and GPT-4: Tackling the cold start problem with simulated user interactions

# 摘要

> 自适应问卷能够根据参与者之前的回答，动态选择下一个问题。由于数字化的发展，自适应问卷已成为政治学等领域传统调查的可行替代方案。然而，自适应问卷的一个局限性是其依赖数据来训练问题选择模型。通常，此类训练数据（即用户交互数据）事先不可用。为了解决这个问题，我们测试了大型语言模型（LLM）是否能够准确生成此类交互数据，并探索了这些合成数据是否可用于预训练自适应政治调查的统计模型。

为了评估这种方法，我们以瑞士投票建议应用程序（VAA）Smartvote的现有数据为基础，采用两种方式：首先，我们将LLM生成的合成数据分布与真实分布进行比较，以评估其相似性；其次，我们将随机初始化的自适应问卷与基于合成数据预训练的问卷进行性能比较，以评估其在训练中的适用性。我们将这些结果与一个具有完美先验知识的“ oracle”问卷进行基准测试。

我们发现，现成的LLM（GPT-4）能够从不同瑞士政党的角度准确回答Smartvote问卷。此外，我们证明，使用合成数据初始化统计模型可以显著减少预测用户回答的误差，并提高VAA的候选人推荐准确性。我们的研究强调了LLM在生成训练数据方面的巨大潜力，特别是在政治调查等与LLM契合的应用领域，可以利用这些数据改进自适应问卷的数据收集过程。

> Adaptive questionnaires dynamically select the next question for a survey participant based on their previous answers. Due to digitalisation, they have become a viable alternative to traditional surveys in application areas such as political science. One limitation, however, is their dependency on data to train the model for question selection. Often, such training data (i.e., user interactions) are unavailable a priori. To address this problem, we (i) test whether Large Language Models (LLM) can accurately generate such interaction data and (ii) explore if these synthetic data can be used to pre-train the statistical model of an adaptive political survey. To evaluate this approach, we utilise existing data from the Swiss Voting Advice Application (VAA) Smartvote in two ways: First, we compare the distribution of LLM-generated synthetic data to the real distribution to assess its similarity. Second, we compare the performance of an adaptive questionnaire that is randomly initialised with one pre-trained on synthetic data to assess their suitability for training. We benchmark these results against an "oracle" questionnaire with perfect prior knowledge. We find that an off-the-shelf LLM (GPT-4) accurately generates answers to the Smartvote questionnaire from the perspective of different Swiss parties. Furthermore, we demonstrate that initialising the statistical model with synthetic data can (i) significantly reduce the error in predicting user responses and (ii) increase the candidate recommendation accuracy of the VAA. Our work emphasises the considerable potential of LLMs to create training data to improve the data collection process in adaptive questionnaires in LLM-affine areas such as political surveys.

[Arxiv](https://arxiv.org/abs/2503.09311)