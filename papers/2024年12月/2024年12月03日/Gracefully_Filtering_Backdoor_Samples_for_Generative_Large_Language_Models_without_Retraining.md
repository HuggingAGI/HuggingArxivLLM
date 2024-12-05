# 无需重新训练，优雅地为生成式大型语言模型过滤后门样本

发布时间：2024年12月03日

`LLM应用` `语言模型` `安全防御`

> Gracefully Filtering Backdoor Samples for Generative Large Language Models without Retraining

# 摘要

> 后门攻击对生成式大型语言模型（LLMs）来说，依旧是重大的安全威胁。因为生成式LLMs输出的是高维令牌对数，而非低维分类对数，所以大多数为像BERT这类判别模型设计的现有后门防御方法，对生成式LLMs并不奏效。受到频率空间中后门与干净映射学习行为差异的启发，我们把每个训练样本的梯度（直接影响参数更新）转换至频率空间。我们的发现表明，在频率空间中，后门样本和干净样本的梯度存在明显的区分。基于此现象，我们提出了用于后门样本过滤的频率空间梯度聚类（GraCeFul），它借助频率空间中的样本梯度，能够有效识别后门样本，无需重新训练LLMs。实验结果显示，GraCeFul显著优于基线。特别要指出的是，GraCeFul展现出了出色的计算效率，在识别后门样本时实现了近乎100％的召回率和F1分数，将各种后门攻击的平均成功率降至0％，在多个自由式问答数据集中，干净准确率的下降微乎其微。此外，GraCeFul还适用于Llama-2和Vicuna。代码在https://github.com/ZrW00/GraceFul公开可获取。

> Backdoor attacks remain significant security threats to generative large language models (LLMs). Since generative LLMs output sequences of high-dimensional token logits instead of low-dimensional classification logits, most existing backdoor defense methods designed for discriminative models like BERT are ineffective for generative LLMs. Inspired by the observed differences in learning behavior between backdoor and clean mapping in the frequency space, we transform gradients of each training sample, directly influencing parameter updates, into the frequency space. Our findings reveal a distinct separation between the gradients of backdoor and clean samples in the frequency space. Based on this phenomenon, we propose Gradient Clustering in the Frequency Space for Backdoor Sample Filtering (GraCeFul), which leverages sample-wise gradients in the frequency space to effectively identify backdoor samples without requiring retraining LLMs. Experimental results show that GraCeFul outperforms baselines significantly. Notably, GraCeFul exhibits remarkable computational efficiency, achieving nearly 100% recall and F1 scores in identifying backdoor samples, reducing the average success rate of various backdoor attacks to 0% with negligible drops in clean accuracy across multiple free-style question answering datasets. Additionally, GraCeFul generalizes to Llama-2 and Vicuna. The codes are publicly available at https://github.com/ZrW00/GraceFul.

[Arxiv](https://arxiv.org/abs/2412.02454)