# # Maya：通过模拟虚拟加速器优化深度学习训练任务

发布时间：2025年03月25日

`LLM应用` `人工智能` `性能建模`

> Maya: Optimizing Deep Learning Training Workloads using Emulated Virtual Accelerators

# 摘要

> 训练大型基础模型需要数亿美元的成本，因此优化部署变得至关重要。目前的方法要求机器学习工程师在昂贵的计算集群上通过容易出错的试错法手动设计训练配方。为了高效探索训练配置，研究人员开发了性能建模系统。然而，这些系统迫使用户将工作负载转换为自定义规格语言，导致实际工作负载与其表示之间存在语义差距。这种差距带来了权衡：系统要么仅支持有限的工作负载以保持易用性，要么需要复杂的规格限制实际采用，要么通过简化模型妥协预测准确性。

我们介绍了Maya，一个通过透明设备仿真消除这些权衡的性能建模系统。Maya在训练框架和加速器设备之间的狭窄接口运行，无需代码修改或翻译即可捕获完整的工作负载行为。通过拦截未经修改的训练代码中的设备API调用，Maya直接观察低级操作，从而在保持易用性和通用性的同时实现准确的性能预测。我们的评估显示，Maya在各种模型和优化策略下实现了小于5%的预测误差，并识别出可将训练成本降低高达56%的配置，优于现有方法。


> Training large foundation models costs hundreds of millions of dollars, making deployment optimization critical. Current approaches require machine learning engineers to manually craft training recipes through error-prone trial-and-error on expensive compute clusters. To enable efficient exploration of training configurations, researchers have developed performance modeling systems. However, these systems force users to translate their workloads into custom specification languages, introducing a fundamental semantic gap between the actual workload and its representation. This gap creates an inherent tradeoff: systems must either support a narrow set of workloads to maintain usability, require complex specifications that limit practical adoption, or compromise prediction accuracy with simplified models.
  We present Maya, a performance modeling system that eliminates these tradeoffs through transparent device emulation. By operating at the narrow interface between training frameworks and accelerator devices, Maya can capture complete workload behavior without requiring code modifications or translations. Maya intercepts device API calls from unmodified training code to directly observe low-level operations, enabling accurate performance prediction while maintaining both ease of use and generality. Our evaluation shows Maya achieves less than 5% prediction error across diverse models and optimization strategies, identifying configurations that reduce training costs by up to 56% compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2503.20191)