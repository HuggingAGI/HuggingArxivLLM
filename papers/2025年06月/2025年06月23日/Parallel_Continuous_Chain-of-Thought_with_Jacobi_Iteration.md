# # 并行连续思维链与雅可比迭代

发布时间：2025年06月23日

`LLM理论` `人工智能`

> Parallel Continuous Chain-of-Thought with Jacobi Iteration

# 摘要

> 连续链式思考（Continuous CoT）在节省大型语言模型推理代币方面表现出色。通过利用连续潜在思考代币进行推理，Continuous CoT 能够以紧凑的方式实现隐式推理。然而，潜在思考代币之间的顺序依赖性阻碍了并行训练，导致训练时间过长。为了解决这一问题，我们提出了并行连续链式思考（PCCoT），它通过对潜在思考代币进行雅可比迭代，实现了并行更新，从而显著提升了连续 CoT 的训练和推理效率。实验结果表明，通过选择合适的迭代次数，PCCoT 不仅能够达到与原有方法相当甚至更优的性能，还成功将训练和推理时间减少了近 50%。此外，PCCoT 在训练过程中展现出更强的稳定性和鲁棒性。我们的代码已开源，地址为 https://github.com/whyNLP/PCCoT。

> Continuous chain-of-thought has been shown to be effective in saving reasoning tokens for large language models. By reasoning with continuous latent thought tokens, continuous CoT is able to perform implicit reasoning in a compact manner. However, the sequential dependencies between latent thought tokens spoil parallel training, leading to long training time. In this paper, we propose Parallel Continuous Chain-of-Thought (PCCoT), which performs Jacobi iteration on the latent thought tokens, updating them iteratively in parallel instead of sequentially and thus improving both training and inference efficiency of continuous CoT. Experiments demonstrate that by choosing the proper number of iterations, we are able to achieve comparable or even better performance while saving nearly 50% of the training and inference time. Moreover, PCCoT shows better stability and robustness in the training process. Our code is available at https://github.com/whyNLP/PCCoT.

[Arxiv](https://arxiv.org/abs/2506.18582)