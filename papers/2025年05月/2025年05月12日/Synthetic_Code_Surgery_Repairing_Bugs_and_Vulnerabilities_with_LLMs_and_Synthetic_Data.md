# 合成代码手术：利用大型语言模型和合成数据修复代码中的漏洞和安全漏洞

发布时间：2025年05月12日

`LLM应用` `软件工程` `数据生成`

> Synthetic Code Surgery: Repairing Bugs and Vulnerabilities with LLMs and Synthetic Data

# 摘要

> 本文提出了一种基于大型语言模型（LLMs）生成合成数据来提升自动程序修复（APR）的新方法。当前APR系统受限于高质量训练数据的匮乏，这些数据需要涵盖多种编程语言中的各类错误类型。本文提出的方法通过两阶段流程解决这一限制：首先生成合成样本，随后进行严格的质量评估。研究中采用了多个先进的LLMs，生成了约30,000对包含错误代码和修复后代码的样本，覆盖了12种编程语言和13类错误。随后，这些样本依据五个标准进行了跨模型评估：正确性、代码质量、安全性、性能和完整性。在VulRepair测试集上的实验结果表明，完美预测率有了显著提升，经过质量筛选的合成数据集在某些情况下优于基线和真实世界提交数据配置。该方法通过严格的统计测试（包括ANOVA和事后Tukey的诚实显著差异分析）得到了验证。此外，表现最佳的配置在使用计算开销较小的解码策略下仍超越现有系统。本研究确立了一种自我引导的范式，其中LLMs自动生成并评估自身的训练数据，这可能改变软件工程任务中数据稀缺性的应对方式，并推动自动代码维护工具的稳健性和适应性发展。

> This paper presents a novel methodology for enhancing Automated Program Repair (APR) through synthetic data generation utilizing Large Language Models (LLMs). Current APR systems are constrained by the limited availability of high-quality training data encompassing diverse bug types across multiple programming languages. The proposed approach addresses this limitation through a two-phase process: a synthetic sample generation followed by a rigorous quality assessment. Multiple state-of-the-art LLMs were employed to generate approximately 30,000 paired examples of buggy and fixed code across 12 programming languages and 13 bug categories. Subsequently, these samples underwent cross-model evaluation against five criteria: correctness, code quality, security, performance, and completeness. Experimental evaluation on the VulRepair test set dataset showed statistically significant improvements in Perfect Prediction rates, with the quality-filtered synthetic dataset outperforming both baseline and real-world commit data configurations in certain scenarios. The methodology was validated through rigorous statistical testing, including ANOVA and post-hoc Tukey's Honest Significant Difference analysis. Furthermore, the best-performing configurations surpassed existing systems despite using a less computationally intensive decoding strategy. This research establishes a self-bootstrapping paradigm in which LLMs generate and evaluate their own training data, potentially transforming approaches to data scarcity across software engineering tasks and advancing the development of robust, adaptable tools for automated code maintenance.

[Arxiv](https://arxiv.org/abs/2505.07372)