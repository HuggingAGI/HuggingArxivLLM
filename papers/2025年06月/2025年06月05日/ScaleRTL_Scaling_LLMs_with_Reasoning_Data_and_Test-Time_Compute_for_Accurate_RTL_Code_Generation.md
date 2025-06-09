# # ScaleRTL：利用推理数据与测试时计算扩展LLMs，实现精准RTL代码生成

发布时间：2025年06月05日

`LLM应用` `EDA` `硬件设计`

> ScaleRTL: Scaling LLMs with Reasoning Data and Test-Time Compute for Accurate RTL Code Generation

# 摘要

> 大型语言模型（LLMs）的最新进展使其在软件编码基准测试中达到了接近人类的水平，但在RTL代码生成方面，由于高质量训练数据的匮乏，其效果仍有待提升。尽管先前的研究对LLMs进行了RTL任务的微调，但这些方法未能从根本上突破数据瓶颈，且由于其不具备推理能力，也缺乏对测试时扩展的支持。在本研究中，我们推出了ScaleRTL，这是首个专注于RTL编码的推理型LLM，能够同时扩展高质量推理数据和测试时计算能力。我们整理了一个多样化的长链式推理轨迹集，平均每条轨迹包含56K个token，最终构建了一个包含350亿个token的大型数据集，其中蕴含丰富的RTL知识。通过在该语料库上对通用推理模型进行微调，我们得到了具备深度RTL推理能力的ScaleRTL。随后，我们通过一种创新的测试时扩展策略进一步提升了ScaleRTL的性能，该策略通过迭代地反思和自我修正之前的推理步骤来延长推理过程。实验结果表明，ScaleRTL在VerilogEval和RTLLM基准测试中达到了最先进的性能水平，与18个具有竞争力的基线模型相比，在VerilogEval上提升了18.4%，在RTLLM上提升了12.7%。

> Recent advances in large language models (LLMs) have enabled near-human performance on software coding benchmarks, but their effectiveness in RTL code generation remains limited due to the scarcity of high-quality training data. While prior efforts have fine-tuned LLMs for RTL tasks, they do not fundamentally overcome the data bottleneck and lack support for test-time scaling due to their non-reasoning nature. In this work, we introduce ScaleRTL, the first reasoning LLM for RTL coding that scales up both high-quality reasoning data and test-time compute. Specifically, we curate a diverse set of long chain-of-thought reasoning traces averaging 56K tokens each, resulting in a dataset of 3.5B tokens that captures rich RTL knowledge. Fine-tuning a general-purpose reasoning model on this corpus yields ScaleRTL that is capable of deep RTL reasoning. Subsequently, we further enhance the performance of ScaleRTL through a novel test-time scaling strategy that extends the reasoning process via iteratively reflecting on and self-correcting previous reasoning steps. Experimental results show that ScaleRTL achieves state-of-the-art performance on VerilogEval and RTLLM, outperforming 18 competitive baselines by up to 18.4% on VerilogEval and 12.7% on RTLLM.

[Arxiv](https://arxiv.org/abs/2506.05566)