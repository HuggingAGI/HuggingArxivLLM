# 贝叶斯教学赋能大型语言模型实现概率推理

发布时间：2025年03月21日

`LLM理论

摘要讨论了大型语言模型（LLMs）在贝叶斯推理框架中的表现及其改进方法，属于对LLM内在机制和推理能力的理论探讨。` `推荐系统` `人工智能`

> Bayesian Teaching Enables Probabilistic Reasoning in Large Language Models

# 摘要

> 基于大型语言模型（LLMs）的人工智能系统正越来越多地被用作与用户和世界互动的代理。为了成功做到这一点，LLMs需要构建对世界的内部表示，并对这些表示形成概率信念。例如，为了向用户提供个性化推荐，LLMs需要在多次交互过程中逐步推断出用户的偏好。为了评估当代LLMs是否能够做到这一点，我们采用了概率论中的贝叶斯推理框架，该框架规定了代理在接收新信息时更新信念的最佳方式。

我们首先展示了LLMs并没有像贝叶斯框架所预期的那样更新其信念，因此，当更多信息变得可用时，它们的预测并没有像预期那样得到改善，甚至比我们发现的人类情况还要差。为了解决这个问题，我们通过训练LLMs模仿最优贝叶斯模型的预测，教会它们以贝叶斯方式进行推理。我们发现，这种方法不仅显著提升了LLMs在其接受训练的特定推荐任务上的表现，还使其能够推广到其他任务。这表明，这种方法赋予了LLMs更广泛的贝叶斯推理能力。

更一般地说，我们的研究结果表明，LLMs能够有效地学习推理策略，并将这些技能推广到新的领域，这在一定程度上解释了LLMs在实际应用中的成功。

> Artificial intelligence systems based on large language models (LLMs) are increasingly used as agents that interact with users and with the world. To do so successfully, LLMs need to construct internal representations of the world and form probabilistic beliefs about those representations. To provide a user with personalized recommendations, for example, the LLM needs to gradually infer the user's preferences, over the course of multiple interactions. To evaluate whether contemporary LLMs are able to do so, we use the Bayesian inference framework from probability theory, which lays out the optimal way to update an agent's beliefs as it receives new information. We first show that the LLMs do not update their beliefs as expected from the Bayesian framework, and that consequently their predictions do not improve as expected as more information becomes available, even less so than we find is the case for humans. To address this issue, we teach the LLMs to reason in a Bayesian manner by training them to mimic the predictions of an optimal Bayesian model. We find that this approach not only significantly improves the LLM's performance on the particular recommendation task it is trained on, but also enables generalization to other tasks. This suggests that this method endows the LLM with broader Bayesian reasoning skills. More generally, our results indicate that LLMs can learn about reasoning strategies effectively and generalize those skills to new domains, which in part explains LLMs' empirical success.

[Arxiv](https://arxiv.org/abs/2503.17523)