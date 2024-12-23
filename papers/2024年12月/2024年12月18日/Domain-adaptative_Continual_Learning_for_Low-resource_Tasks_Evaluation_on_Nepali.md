# 针对低资源任务的领域自适应持续学习：尼泊尔语评估

发布时间：2024年12月18日

`LLM应用` `持续学习`

> Domain-adaptative Continual Learning for Low-resource Tasks: Evaluation on Nepali

# 摘要

> 持续学习已成为重要研究方向，原因是新数据出现时，从头重训大型语言模型（LLMs）不可行。领域自适应预训练（DAPT）范式颇受关注，它专注于持续训练预训练语言模型，使其适应原本未受训的领域。在本研究中，我们评估了低资源环境（比如尼泊尔语环境）下 DAPT 的可行性。我们用合成数据继续训练 Llama 3 8B，使其在 4 位 QLoRA 设定下适应尼泊尔语。我们从性能、遗忘和知识获取等方面评估了适配后的模型。我们对比了基础模型和最终模型在尼泊尔语生成能力、流行基准测试中的表现，并开展案例研究来探究它们在尼泊尔语中的语言知识。我们在最终模型中看到了一些意料之中的遗忘，但也惊喜地发现，评估时增加样本数量，最终模型的百分比提升（高达 19.29%）比基础模型（4.98%）更好，这表明存在潜在的留存。我们还探索了层头自注意力热图，以确定最终模型在尼泊尔语中的依赖解析能力。

> Continual learning has emerged as an important research direction due to the infeasibility of retraining large language models (LLMs) from scratch in the event of new data availability. Of great interest is the domain-adaptive pre-training (DAPT) paradigm, which focuses on continually training a pre-trained language model to adapt it to a domain it was not originally trained on. In this work, we evaluate the feasibility of DAPT in a low-resource setting, namely the Nepali language. We use synthetic data to continue training Llama 3 8B to adapt it to the Nepali language in a 4-bit QLoRA setting. We evaluate the adapted model on its performance, forgetting, and knowledge acquisition. We compare the base model and the final model on their Nepali generation abilities, their performance on popular benchmarks, and run case-studies to probe their linguistic knowledge in Nepali. We see some unsurprising forgetting in the final model, but also surprisingly find that increasing the number of shots during evaluation yields better percent increases in the final model (as high as 19.29% increase) compared to the base model (4.98%), suggesting latent retention. We also explore layer-head self-attention heatmaps to establish dependency resolution abilities of the final model in Nepali.

[Arxiv](https://arxiv.org/abs/2412.13860)