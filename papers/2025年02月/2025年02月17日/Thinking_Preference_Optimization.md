# 思考偏好优化

发布时间：2025年02月17日

`LLM理论

摘要主要讨论了监督微调（SFT）方法在提升大型语言模型（LLMs）推理能力方面的应用，并提出了一种新的优化方法ThinkPO。该方法通过偏好优化来提升模型的推理性能，属于对模型训练和优化方法的理论研究，因此归类于LLM理论。` `人工智能` `机器学习`

> Thinking Preference Optimization

# 摘要

> 监督微调（SFT）一直是提升相对较小的大型语言模型（LLMs）长链推理能力的有效方法，通过使用更大模型生成的长链推理响应进行微调。为了持续提升推理能力，我们可以通过收集新的高质量长链推理SFT数据，或者对现有SFT数据集进行重复训练。然而，获取新的长链推理SFT数据成本高昂且有限，而重复训练往往会导致性能 plateau 或下降。为了进一步提升SFT数据的性能，我们提出了思考偏好优化（ThinkPO），这是一种简单有效的后SFT方法，无需新的长链推理响应即可增强长链推理能力。相反，ThinkPO利用现成的或易于获取的短链推理响应作为被拒绝的答案，长链响应作为被选择的答案，针对同一问题。然后通过直接偏好优化，鼓励模型更倾向于生成较长的推理输出。实验表明，ThinkPO进一步提升了SFT模型的推理性能，例如将SFT模型的数学推理准确率提高了8.6%，输出长度增加了25.9%。值得注意的是，ThinkPO能够持续提升公开蒸馏SFT模型的性能，例如将官方DeepSeek-R1-Distill-Qwen-7B在MATH500上的性能从87.4%提升至91.2%。

> Supervised Fine-Tuning (SFT) has been a go-to and effective method for enhancing long chain-of-thought (CoT) reasoning in relatively small LLMs by fine-tuning them with long CoT responses from larger LLMs. To continually improve reasoning abilities, we can either collect new high-quality long CoT reasoning SFT data or repeatedly train on existing SFT datasets. However, acquiring new long CoT SFT data is costly and limited, while repeated training often results in a performance plateau or decline. To further boost the performance with the SFT data, we propose Thinking Preference Optimization (ThinkPO), a simple yet effective post-SFT method that enhances long CoT reasoning without requiring new long CoT responses. Instead, ThinkPO utilizes readily available or easily obtainable short CoT reasoning responses as rejected answers and long CoT responses as chosen answers for the same question. It then applies direct preference optimization to encourage the model to favor longer reasoning outputs. Experiments show that ThinkPO further improves the reasoning performance of SFT-ed models, e.g. it increases math reasoning accuracy of SFT-ed models by 8.6% and output length by 25.9%. Notably, ThinkPO is capable of continually boosting the performance of the publicly distilled SFT model, e.g., increasing the official DeepSeek-R1-Distill-Qwen-7B's performance on MATH500 from 87.4% to 91.2%.

[Arxiv](https://arxiv.org/abs/2502.13173)