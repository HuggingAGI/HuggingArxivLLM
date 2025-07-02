# ChatHLS：系统性设计自动化与优化，面向高层次综合

发布时间：2025年07月01日

`LLM应用` `计算机硬件` `电子设计自动化`

> ChatHLS: Towards Systematic Design Automation and Optimization for High-Level Synthesis

# 摘要

> 面对日益复杂的计算需求，专用领域加速器的采用速度显著加快。然而，传统硬件设计方法仍受制于漫长的开发与验证周期。高阶综合（HLS）通过从高级编程语言实现硬件设计，架起了软件与硬件之间的桥梁。然而，由于严格的编码约束和复杂的硬件特定优化，其广泛应用面临诸多障碍，给开发者带来巨大挑战。大型语言模型（LLMs）的最新进展在硬件设计自动化领域展现了巨大潜力，但受限于高质量数据集的稀缺性，尤其是在HLS领域，其效果大打折扣。为应对这些挑战，我们推出了ChatHLS，一个敏捷的HLS设计自动化与优化工作流。ChatHLS整合了经过微调的LLMs到多智能体框架中，用于错误修正和设计优化。通过广泛的评估，ChatHLS在612个测试案例中实现了82.7%的平均修复通过率，较GPT-4o和Llama3-8B分别提升了19.1%和63.0%。此外，ChatHLS在资源受限的内核上实现了1.9$	imes$至14.8$	imes$的性能提升。通过在实际计算预算内实现复杂的优化推理，ChatHLS较现有基于领域特定语言的方法实现了4.9$	imes$的几何平均加速。这些成果凸显了ChatHLS在大幅缩短硬件开发周期的同时，仍能保持设计可靠性和优化质量的严格标准的潜力。

> The increasing complexity of computational demands has accelerated the adoption of domain-specific accelerators, yet traditional hardware design methodologies remain constrained by prolonged development and verification cycles. High-Level Synthesis (HLS) bridges the gap between software and hardware by enabling hardware design from high-level programming languages. However, its widespread adoption is hindered by strict coding constraints and intricate hardware-specific optimizations, creating significant obstacles for developers. Recent advancements in Large Language Models (LLMs) demonstrate substantial potential in hardware design automation. However, their effectiveness is limited by the scarcity of high-quality datasets, particularly in the context of HLS. To address these challenges, we introduce ChatHLS, an agile HLS design automation and optimization workflow that leverages fine-tuned LLMs integrated within a multi-agent framework for error correction and design optimization. Our extensive evaluations reveal that ChatHLS achieves an average repair pass rate of 82.7% over 612 test cases, outperforming the GPT-4o and Llama3-8B by 19.1% and 63.0%, respectively. Furthermore, ChatHLS delivers performance enhancements ranging from 1.9$\times$ to 14.8$\times$ upon resource-constrained kernels. By enabling sophisticated optimization reasoning within practical computational budgets, ChatHLS attains a 4.9$\times$ geometric mean speedup compared to state-of-the-art DSL-based approaches. These results underscore the potential of ChatHLS in substantially expediting hardware development cycles while maintaining rigorous standards of design reliability and optimization quality.

[Arxiv](https://arxiv.org/abs/2507.00642)