# OpenUnlearning: 通过统一的方法与指标基准测试加速 LLM 的遗忘机制

发布时间：2025年06月14日

`LLM理论` `数据隐私` `模型安全`

> OpenUnlearning: Accelerating LLM Unlearning via Unified Benchmarking of Methods and Metrics

# 摘要

> 在需要保障数据隐私、模型安全性和合规性的环境中，实现大型语言模型（LLMs）的安全部署，健壮的遗忘机制至关重要。然而，这一任务充满挑战，部分原因在于难以可靠地衡量遗忘是否真正发生。此外，当前方法的碎片化和评估指标的不一致性阻碍了比较分析和可重复性。为统一和加速研究进展，我们推出了OpenUnlearning——一个专为基准测试LLM遗忘方法和指标而设计的标准且可扩展框架。OpenUnlearning整合了9种遗忘算法和16种多样化评估方式，覆盖TOFU、MUSE和WMDP三大领先基准测试，并支持对我们在公开发布的450多个检查点上的遗忘行为进行分析。借助OpenUnlearning，我们提出了一种专注于评估评估指标自身忠实性和鲁棒性的元评估基准。我们还对多种遗忘方法进行了基准测试，并提供了一套全面评估工具的比较分析。总体而言，我们为LLM遗忘研究的严谨发展建立了一条清晰的、由社区驱动的研究路径。

> Robust unlearning is crucial for safely deploying large language models (LLMs) in environments where data privacy, model safety, and regulatory compliance must be ensured. Yet the task is inherently challenging, partly due to difficulties in reliably measuring whether unlearning has truly occurred. Moreover, fragmentation in current methodologies and inconsistent evaluation metrics hinder comparative analysis and reproducibility. To unify and accelerate research efforts, we introduce OpenUnlearning, a standardized and extensible framework designed explicitly for benchmarking both LLM unlearning methods and metrics. OpenUnlearning integrates 9 unlearning algorithms and 16 diverse evaluations across 3 leading benchmarks (TOFU, MUSE, and WMDP) and also enables analyses of forgetting behaviors across 450+ checkpoints we publicly release. Leveraging OpenUnlearning, we propose a novel meta-evaluation benchmark focused specifically on assessing the faithfulness and robustness of evaluation metrics themselves. We also benchmark diverse unlearning methods and provide a comparative analysis against an extensive evaluation suite. Overall, we establish a clear, community-driven pathway toward rigorous development in LLM unlearning research.

[Arxiv](https://arxiv.org/abs/2506.12618)