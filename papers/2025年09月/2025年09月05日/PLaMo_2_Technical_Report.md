# PLaMo 2 技术报告

发布时间：2025年09月05日

`LLM应用` `基础理论`

> PLaMo 2 Technical Report

# 摘要

> 本报告介绍了PLaMo 2——一系列专注于日语的大型语言模型，其核心是基于Samba的混合架构，通过持续预训练过渡到全注意力机制，从而支持32K token的上下文。为解决数据稀缺问题，训练过程采用了海量合成语料库；同时通过权重复用与结构化剪枝提升计算效率，这种高效剪枝方法使8B模型性能媲美我们之前的100B模型。后训练阶段通过监督微调（SFT）与直接偏好优化（DPO）流程对模型进行精调，并结合合成日语指令数据与模型合并技术进一步提升性能。PLaMo 2模型通过vLLM和量化技术优化推理过程，精度损失极小，最终在日语基准测试中创下最佳性能，在指令遵循、语言流畅度和日语特定知识方面超越同等规模的开源模型。

> In this report, we introduce PLaMo 2, a series of Japanese-focused large language models featuring a hybrid Samba-based architecture that transitions to full attention via continual pre-training to support 32K token contexts. Training leverages extensive synthetic corpora to overcome data scarcity, while computational efficiency is achieved through weight reuse and structured pruning. This efficient pruning methodology produces an 8B model that achieves performance comparable to our previous 100B model. Post-training further refines the models using a pipeline of supervised fine-tuning (SFT) and direct preference optimization (DPO), enhanced by synthetic Japanese instruction data and model merging techniques. Optimized for inference using vLLM and quantization with minimal accuracy loss, the PLaMo 2 models achieve state-of-the-art results on Japanese benchmarks, outperforming similarly-sized open models in instruction-following, language fluency, and Japanese-specific knowledge.

[Arxiv](https://arxiv.org/abs/2509.04897)