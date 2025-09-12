# Compass-v3：为东南亚多语言电商扩展特定领域大型语言模型

发布时间：2025年09月10日

`LLM应用` `零售与电商`

> Compass-v3: Scaling Domain-Specific LLMs for Multilingual E-Commerce in Southeast Asia

# 摘要

> 大型语言模型（LLMs）在通用领域表现卓越，但在需要特定领域知识的专业任务中性能常显不足。电子商务领域尤为棘手，因其数据存在噪声多、异构性强、多语言混杂及高度动态的特点。为此，我们推出Compass-v3——一款面向东南亚电商的垂直领域混合专家（MoE）模型，总参数达2450亿，单token激活参数710亿。该模型采用"少而精"的专家设计，结合节点内专家并行、定制内存复制运算符等硬件高效优化策略，实现GPU利用率最大化。模型训练基于12万亿精心筛选的多语言语料与大规模合成电商指令，采用混合训练策略完成。为提升对齐效果，我们提出最优传输直接偏好优化（OTPO）技术，通过捕捉token级差异增强电商场景指令遵循度。广泛评估显示，Compass-v3电商性能刷新当前最佳水平，超越DeepSeek-V3.1、GPT-4系列及Qwen3-235B。此外，模型在低资源东南亚语种（印尼语、泰语、菲律宾语、越南语、马来语、他加禄语）及葡萄牙语上展现卓越多语能力，通用基准测试中仍保持竞争力。目前，该模型已大规模应用于Shopee工业级电商平台，逐步替代OpenAI服务流量，占平台LLM总用量超70%，充分彰显其专业电商领域专长与广泛语言学能力的双重优势。

> Large language models (LLMs) excel in general-domain applications, yet their performance often degrades in specialized tasks requiring domain-specific knowledge. E-commerce is particularly challenging, as its data are noisy, heterogeneous, multilingual, and highly dynamic. We present Compass-v3, a vertical-domain Mixture-of-Experts (MoE) model with 245B total parameters and 71B active per token, designed for Southeast Asian e-commerce. Compass-v3 adopts fewer but larger experts, combined with hardware-efficient optimizations-such as intra-node expert parallelism and a customized memcpy operator-to maximize GPU utilization. The model is trained on 12T tokens of curated multilingual corpora and large-scale synthetic e-commerce instructions using a mixed-training strategy. To enhance alignment, we propose Optimal-Transport Direct Preference Optimization (OTPO), which captures token-level distinctions and improves instruction adherence in commerce-specific scenarios. Extensive evaluations demonstrate that Compass-v3 delivers state-of-the-art e-commerce performance, surpassing DeepSeek-V3.1, GPT-4 series, and Qwen3-235B. Moreover, Compass-v3 demonstrates strong multilingual capability across low-resource Southeast Asian languages (Indonesian, Thai, Filipino, Vietnamese, Malay, Taglog) and Portuguese while sustaining competitive performance on general benchmarks. It has already been widely applied in Shopee's industrial-scale e-commerce platform and is gradually replacing OpenAI's traffic, now accounting for over 70\% of total LLM usage, highlighting its dual strengths in specialized commerce expertise and broad linguistic competence.

[Arxiv](https://arxiv.org/abs/2509.09121)