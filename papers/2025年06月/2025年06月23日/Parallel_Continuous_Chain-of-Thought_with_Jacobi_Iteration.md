# 并行连续思维链与雅可比迭代结合

发布时间：2025年06月23日

`LLM理论` `机器学习`

> Parallel Continuous Chain-of-Thought with Jacobi Iteration

# 摘要

> 连续思维链在为大型语言模型节省推理资源方面表现出色。通过连续潜意识思维令牌的推理方式，连续CoT能够高效地进行隐式推理。然而，潜意识思维令牌间的顺序依赖关系限制了并行训练，导致训练时间较长。为此，我们提出了并行连续思维链（PCCoT），采用雅可比迭代方法对潜意识思维令牌进行并行更新，从而显著提升了训练和推理效率。实验结果显示，通过合理选择迭代次数，PCCoT不仅能够达到与原有方法相当甚至更优的性能，还成功将训练和推理时间减少了近50%。此外，PCCoT在训练过程中展现出更佳的稳定性和鲁棒性。我们的代码已在GitHub上开源，地址为https://github.com/whyNLP/PCCoT。

> Continuous chain-of-thought has been shown to be effective in saving reasoning tokens for large language models. By reasoning with continuous latent thought tokens, continuous CoT is able to perform implicit reasoning in a compact manner. However, the sequential dependencies between latent thought tokens spoil parallel training, leading to long training time. In this paper, we propose Parallel Continuous Chain-of-Thought (PCCoT), which performs Jacobi iteration on the latent thought tokens, updating them iteratively in parallel instead of sequentially and thus improving both training and inference efficiency of continuous CoT. Experiments demonstrate that by choosing the proper number of iterations, we are able to achieve comparable or even better performance while saving nearly 50% of the training and inference time. Moreover, PCCoT shows better stability and robustness in the training process. Our code is available at https://github.com/whyNLP/PCCoT.

[Arxiv](https://arxiv.org/abs/2506.18582)