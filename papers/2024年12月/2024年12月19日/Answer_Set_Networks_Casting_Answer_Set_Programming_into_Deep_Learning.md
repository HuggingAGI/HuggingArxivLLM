# Answer Set Networks：把 Answer Set Programming 引入深度学习

发布时间：2024年12月19日

`LLM应用` `人工智能`

> Answer Set Networks: Casting Answer Set Programming into Deep Learning

# 摘要

> 尽管答案集编程（ASP）能够对神经符号（NeSy）系统加以约束，但其应用却因计算稳定模型的高昂成本以及最先进求解器的 CPU 受限特性而受阻。为此，我们提出了答案集网络（ASN）这一 NeSy 求解器。基于图神经网络（GNN），ASN 是一种针对基于 ASP 的深度概率逻辑编程（DPPL）的可扩展方法。具体而言，我们展示了如何将 ASP 转化为 ASN，并说明了 ASN 如何借助 GPU 的批处理和并行化能力有效解决编码问题。我们的实验评估显示，ASN 在多项任务上的表现优于最先进的受 CPU 限制的 NeSy 系统。同时，基于 ASN 的优势，我们做出了以下两项贡献。其一，我们率先展示了利用 DPPL 对大型语言模型（LLM）进行微调，运用 ASN 以逻辑指导训练。其二，我们展示了无人机的“宪法导航”，即在 ASN 中对公共航空法进行编码，以用于在不确定环境中为无人驾驶飞行器规划路线。

> Although Answer Set Programming (ASP) allows constraining neural-symbolic (NeSy) systems, its employment is hindered by the prohibitive costs of computing stable models and the CPU-bound nature of state-of-the-art solvers. To this end, we propose Answer Set Networks (ASN), a NeSy solver. Based on Graph Neural Networks (GNN), ASNs are a scalable approach to ASP-based Deep Probabilistic Logic Programming (DPPL). Specifically, we show how to translate ASPs into ASNs and demonstrate how ASNs can efficiently solve the encoded problem by leveraging GPU's batching and parallelization capabilities. Our experimental evaluations demonstrate that ASNs outperform state-of-the-art CPU-bound NeSy systems on multiple tasks. Simultaneously, we make the following two contributions based on the strengths of ASNs. Namely, we are the first to show the finetuning of Large Language Models (LLM) with DPPLs, employing ASNs to guide the training with logic. Further, we show the "constitutional navigation" of drones, i.e., encoding public aviation laws in an ASN for routing Unmanned Aerial Vehicles in uncertain environments.

[Arxiv](https://arxiv.org/abs/2412.14814)