# 联邦素描LoRA：设备端协作微调大型语言模型

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要讨论了在设备端微调大型语言模型（LLMs）的挑战，并提出了一种新的方法（联邦草图LoRA，FSLoRA）来解决计算资源异质性的问题。该方法通过调整草图比率来适应设备的通信和计算约束，并在多个数据集和LLM模型上进行了实验验证。这些内容主要涉及如何在实际应用中优化和调整LLMs，因此属于LLM应用的范畴。` `联邦学习`

> Federated Sketching LoRA: On-Device Collaborative Fine-Tuning of Large Language Models

# 摘要

> # 摘要
设备端微调大型语言模型（LLMs）正日益受到关注。近期研究将低秩适应（LoRA）技术与联邦微调结合，以应对设备模型大小和数据稀缺性带来的挑战。然而，计算资源的异质性仍是关键瓶颈：尽管高秩模块通常能提升性能，但设备能力的差异限制了LoRA的可行秩范围。现有解决方案要么缺乏理论依据，要么增加额外计算开销，亟需一种高效且理论扎实的解决方案。为此，我们提出联邦草图LoRA（FSLoRA），利用草图机制使设备能够选择性更新服务器维护的全局LoRA模块子矩阵。通过调整草图比率（决定设备子矩阵的秩），FSLoRA灵活适应设备的通信和计算约束。我们提供了FSLoRA的严格收敛分析，阐明草图比率如何影响收敛速度。在多个数据集和LLM模型上的实验表明，FSLoRA在性能上显著优于多种基线方法。

> Fine-tuning large language models (LLMs) on devices is attracting increasing interest. Recent works have fused low-rank adaptation (LoRA) techniques with federated fine-tuning to mitigate challenges associated with device model sizes and data scarcity. Still, the heterogeneity of computational resources remains a critical bottleneck: while higher-rank modules generally enhance performance, varying device capabilities constrain LoRA's feasible rank range. Existing approaches attempting to resolve this issue either lack analytical justification or impose additional computational overhead, leaving a wide gap for an efficient and theoretically-grounded solution. To address these challenges, we propose federated sketching LoRA (FSLoRA), which leverages a sketching mechanism to enable devices to selectively update submatrices of global LoRA modules maintained by the server. By adjusting the sketching ratios, which determine the ranks of the submatrices on the devices, FSLoRA flexibly adapts to device-specific communication and computational constraints. We provide a rigorous convergence analysis of FSLoRA that characterizes how the sketching ratios affect the convergence rate. Through comprehensive experiments on multiple datasets and LLM models, we demonstrate FSLoRA's superior performance compared to various baselines.

[Arxiv](https://arxiv.org/abs/2501.19389)