# # 基于排序投票的大型语言模型自我一致性

发布时间：2025年05月15日

`LLM应用` `问答系统`

> Ranked Voting based Self-Consistency of Large Language Models

# 摘要

> 多数投票法被认为是提升链式推理能力的有效方法，因为它能在不同推理路径中选出"自我一致性"最高的答案（Wang et al., 2023）。但传统链式推理方法通常每次只能生成一个答案，忽视了其他潜在答案的可能性。这些替代答案往往在后续投票中被忽略。本研究提出在每次推理中生成排序答案，并对多个响应中的排序答案进行排序投票，从而让整体自我一致性更可靠。具体来说，我们采用了三种排序投票方法：单票制、博达计数和平均倒数排名投票。我们在六个数据集上验证了方法，包括三个选择题和三个开放性问答任务，使用了先进的开源和闭源大型语言模型。实验结果表明，我们的方法优于基线方法，展示了利用排序答案信息并通过排序投票提升推理性能的潜力。代码可在https://github.com/szu-tera/RankedVotingSC获取。

> Majority voting is considered an effective method to enhance chain-of-thought reasoning, as it selects the answer with the highest "self-consistency" among different reasoning paths (Wang et al., 2023). However, previous chain-of-thought reasoning methods typically generate only a single answer in each trial, thereby ignoring the possibility of other potential answers. As a result, these alternative answers are often overlooked in subsequent voting processes. In this work, we propose to generate ranked answers in each reasoning process and conduct ranked voting among multiple ranked answers from different responses, thereby making the overall self-consistency more reliable. Specifically, we use three ranked voting methods: Instant-runoff voting, Borda count voting, and mean reciprocal rank voting. We validate our methods on six datasets, including three multiple-choice and three open-ended question-answering tasks, using both advanced open-source and closed-source large language models. Extensive experimental results indicate that our proposed method outperforms the baselines, showcasing the potential of leveraging the information of ranked answers and using ranked voting to improve reasoning performance. The code is available at https://github.com/szu-tera/RankedVotingSC.

[Arxiv](https://arxiv.org/abs/2505.10772)