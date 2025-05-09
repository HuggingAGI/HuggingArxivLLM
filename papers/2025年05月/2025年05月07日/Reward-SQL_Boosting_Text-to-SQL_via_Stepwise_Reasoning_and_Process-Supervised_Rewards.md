# # Reward-SQL：通过逐步推理与过程监督奖励提升文本到SQL的效果

发布时间：2025年05月07日

`LLM应用

摘要讨论了大型语言模型在Text-to-SQL任务中的应用，提出了Reward-SQL框架，通过整合过程奖励模型来提高推理准确性。这属于模型在特定任务中的应用，因此归类为LLM应用。` `数据库管理`

> Reward-SQL: Boosting Text-to-SQL via Stepwise Reasoning and Process-Supervised Rewards

# 摘要

> # 摘要
大型语言模型（LLMs）在Text-to-SQL任务上的表现有了显著提升，这得益于其强大的推理能力。为了在推理过程中提高准确性，可以在训练和推理阶段引入外部的过程奖励模型（PRMs），以提供精细的监督。然而，如果使用不当，PRMs可能会扭曲推理路径，导致生成的SQL不准确或错误。为了解决这一挑战，我们提出了Reward-SQL框架，系统性地探索了如何有效将PRMs整合到Text-to-SQL推理过程中。

我们的方法遵循“冷启动，然后PRM监督”的范式。具体来说，我们首先训练模型将SQL查询分解为结构化的逐步推理链，使用公共表表达式（Chain-of-CTEs），从而建立一个强大且可解释的推理基线。然后，我们研究了四种整合PRMs的策略，并发现将PRM作为在线训练信号（GRPO）与PRM引导的推理（例如最佳N采样）相结合，能够取得最佳效果。

实证研究表明，在BIRD基准测试中，Reward-SQL使受7B PRM监督的模型在各种指导策略下实现了13.1%的性能提升。值得注意的是，我们基于Qwen2.5-Coder-7B-Instruct的GRPO对齐策略模型在BIRD开发集上达到了68.9%的准确率，优于相同模型规模下的所有基线方法。这些结果证明了Reward-SQL在利用基于奖励的监督进行Text-to-SQL推理方面的有效性。我们的代码已公开发布。

> Recent advances in large language models (LLMs) have significantly improved performance on the Text-to-SQL task by leveraging their powerful reasoning capabilities. To enhance accuracy during the reasoning process, external Process Reward Models (PRMs) can be introduced during training and inference to provide fine-grained supervision. However, if misused, PRMs may distort the reasoning trajectory and lead to suboptimal or incorrect SQL generation.To address this challenge, we propose Reward-SQL, a framework that systematically explores how to incorporate PRMs into the Text-to-SQL reasoning process effectively. Our approach follows a "cold start, then PRM supervision" paradigm. Specifically, we first train the model to decompose SQL queries into structured stepwise reasoning chains using common table expressions (Chain-of-CTEs), establishing a strong and interpretable reasoning baseline. Then, we investigate four strategies for integrating PRMs, and find that combining PRM as an online training signal (GRPO) with PRM-guided inference (e.g., best-of-N sampling) yields the best results. Empirically, on the BIRD benchmark, Reward-SQL enables models supervised by a 7B PRM to achieve a 13.1% performance gain across various guidance strategies. Notably, our GRPO-aligned policy model based on Qwen2.5-Coder-7B-Instruct achieves 68.9% accuracy on the BIRD development set, outperforming all baseline methods under the same model size. These results demonstrate the effectiveness of Reward-SQL in leveraging reward-based supervision for Text-to-SQL reasoning. Our code is publicly available.

[Arxiv](https://arxiv.org/abs/2505.04671)