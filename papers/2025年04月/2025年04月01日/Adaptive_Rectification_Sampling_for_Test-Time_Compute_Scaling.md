# 自适应校正采样实现测试时计算缩放

发布时间：2025年04月01日

`LLM应用

理由：这篇论文探讨了如何在推理时扩展大型语言模型的能力，特别是在复杂任务中通过自适应修正采样方法来提升模型性能。它属于模型的应用层面，旨在优化模型的表现和效率，因此归类为LLM应用。` `人工智能`

> Adaptive Rectification Sampling for Test-Time Compute Scaling

# 摘要

> 新发布的 OpenAI-o1 和 DeepSeek-R1 展示了推理时扩展（test-time scaling）在复杂任务（如逻辑推理）中显著提升模型性能的能力。常见的推理时扩展方法包括生成更多思维链（CoTs）或更长的带有自我修正的思维链。然而，自我修正虽然能提升性能，但如果推理步骤本身正确，可能会导致显著的标记浪费并降低思维链的可读性。为展示大型语言模型（LLMs）可在更精细粒度级别纠正错误，我们提出了自适应修正采样（AR-Sampling），该方法可引导 LLMs 在适当步骤进行自我修正。AR-Sampling 利用过程监督奖励模型（PRM）作为验证器，并构建触发句来指导模型进行自适应的步骤级别重新思考。实验表明，我们的方法使模型以更精细的粒度重新思考，提升解决方案的准确性，同时生成合理数量的额外标记。

> The newly released OpenAI-o1 and DeepSeek-R1 have demonstrated that test-time scaling can significantly improve model performance, especially in complex tasks such as logical reasoning. Common test-time scaling methods involve generating more chain of thoughts (CoTs) or longer CoTs with self-correction. However, while self-correction can improve performance, it may lead to significant token waste and reduce readability of the CoT if the reasoning steps are already correct. To demonstrate that large language models (LLMs) can rectify errors at a more fine-grained level, we propose Adaptive Rectification Sampling (AR-Sampling), which can guide the LLMs to self-correction at the appropriate step. AR-Sampling leverages a process-supervised reward model (PRM) as a verifier and constructed trigger sentences to guide the model in adaptive step-level rethinking. Through the experiments on GSM8K and MATH500, it indicate that our approach enables the models to rethink in more fine-grained level, improving the accuracy of solutions, while generating a reasonable number of additional tokens.

[Arxiv](https://arxiv.org/abs/2504.01317)