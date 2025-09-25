# EchoBench：医疗大型视觉-语言模型谄媚行为评估基准

发布时间：2025年09月24日

`LLM应用` `医疗健康`

> EchoBench: Benchmarking Sycophancy in Medical Large Vision-Language Models

# 摘要

> 当前医疗大型视觉语言模型（LVLMs）的基准测试多聚焦于榜单准确率，却忽略了可靠性与安全性。我们针对高风险临床场景，研究了模型的"谄媚行为"——即不加批判地附和用户提供信息的倾向。为此，我们提出EchoBench基准测试，用于系统评估医疗LVLMs的谄媚行为。该基准包含18个科室、20种模态的2122张图像，以及90个模拟患者、医学生和医生有偏见输入的提示。我们对医疗专用、开源及专有LVLMs展开评估，发现所有模型均存在显著谄媚行为：表现最佳的专有模型（Claude 3.7 Sonnet）谄媚率仍达45.98%，GPT-4.1则高达59.15%。许多医疗专用模型的谄媚率甚至超过95%，尽管它们的准确率仅处于中等水平。通过按偏见类型、科室、感知粒度和模态进行的细粒度分析，我们确定了加剧模型易受影响性的关键因素。进一步研究发现，更高的数据质量/多样性和更强的领域知识能有效降低谄媚行为，同时不影响无偏准确率。EchoBench还可作为缓解谄媚行为的测试平台：简单的提示级干预（如消极提示、单样本、少样本）能持续减少谄媚行为，并为训练和解码阶段的策略设计提供了启发。我们的研究结果强调，有必要进行超越准确率的稳健评估，并为开发更安全、更可信的医疗LVLMs提供了切实可行的指导。

> Recent benchmarks for medical Large Vision-Language Models (LVLMs) emphasize leaderboard accuracy, overlooking reliability and safety. We study sycophancy -- models' tendency to uncritically echo user-provided information -- in high-stakes clinical settings. We introduce EchoBench, a benchmark to systematically evaluate sycophancy in medical LVLMs. It contains 2,122 images across 18 departments and 20 modalities with 90 prompts that simulate biased inputs from patients, medical students, and physicians. We evaluate medical-specific, open-source, and proprietary LVLMs. All exhibit substantial sycophancy; the best proprietary model (Claude 3.7 Sonnet) still shows 45.98% sycophancy, and GPT-4.1 reaches 59.15%. Many medical-specific models exceed 95% sycophancy despite only moderate accuracy. Fine-grained analyses by bias type, department, perceptual granularity, and modality identify factors that increase susceptibility. We further show that higher data quality/diversity and stronger domain knowledge reduce sycophancy without harming unbiased accuracy. EchoBench also serves as a testbed for mitigation: simple prompt-level interventions (negative prompting, one-shot, few-shot) produce consistent reductions and motivate training- and decoding-time strategies. Our findings highlight the need for robust evaluation beyond accuracy and provide actionable guidance toward safer, more trustworthy medical LVLMs.

[Arxiv](https://arxiv.org/abs/2509.20146)