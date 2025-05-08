# # 设备端大型语言模型实现智能Wi-Fi漫游

发布时间：2025年05月07日

`LLM应用` `无线通信` `边缘计算`

> On-Device LLM for Context-Aware Wi-Fi Roaming

# 摘要

> 无线漫游是动态移动环境中实现无缝连接的关键任务，但传统方法常常难以应对。我们首次提出跨层应用设备端大型语言模型（LLM），在应用层进行高层次推理并实时指导物理层/介质访问控制层（PHY/MAC）操作。LLM主要负责两项创新任务：基于环境线索（如位置、时间）的智能AP选择，以及自适应的漫游时机决策。为适应边缘硬件的严格要求，我们采用链式推理提示、参数高效微调和量化等优化技术。实验结果表明，与传统方法和深度强化学习方案相比，我们的方法在漫游稳定性和信号质量之间实现了更优平衡。这些成果彰显了应用层LLM推理在未来的边缘无线控制系统中的巨大潜力。

> Wireless roaming is a critical yet challenging task for maintaining seamless connectivity in dynamic mobile environments. Conventional threshold-based or heuristic schemes often fail, leading to either sticky or excessive handovers. We introduce the first cross-layer use of an on-device large language model (LLM): high-level reasoning in the application layer that issues real-time actions executed in the PHY/MAC stack. The LLM addresses two tasks: (i) context-aware AP selection, where structured prompts fuse environmental cues (e.g., location, time) to choose the best BSSID; and (ii) dynamic threshold adjustment, where the model adaptively decides when to roam. To satisfy the tight latency and resource budgets of edge hardware, we apply a suite of optimizations-chain-of-thought prompting, parameter-efficient fine-tuning, and quantization. Experiments on indoor and outdoor datasets show that our approach surpasses legacy heuristics and DRL baselines, achieving a strong balance between roaming stability and signal quality. These findings underscore the promise of application-layer LLM reasoning for lower-layer wireless control in future edge systems.

[Arxiv](https://arxiv.org/abs/2505.04174)