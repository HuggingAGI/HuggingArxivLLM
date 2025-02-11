# AppVLM: 轻量级视觉语言模型，专为在线应用控制设计

发布时间：2025年02月10日

`LLM应用` `移动应用` `人工智能`

> AppVLM: A Lightweight Vision Language Model for Online App Control

# 摘要

> 将基础模型应用于智能手机助手（即应用代理）是一项重要研究课题。这些代理通过解析文本指令并借助设备界面执行操作，来完成智能手机上的用户指令。尽管潜力巨大，现有方法仍存在明显局限：使用大型专有模型（如GPT-4o）的方法计算成本高昂，而使用小型微调模型的方法则常缺乏对分布外任务的适应性。在本研究中，我们提出了轻量级视觉语言模型（VLM）AppVLM。首先，我们基于AndroidControl数据集对其进行离线微调。随后，我们通过从AndroidWorld环境收集数据并进行进一步训练迭代，优化其策略。实验结果显示，AppVLM在AndroidControl数据集上的离线评估中实现了最高的动作预测准确率，超越所有评估的基线模型。在AndroidWorld环境中，其在线任务完成成功率可与GPT-4o相媲美，同时速度提升达十倍。这使得AppVLM成为实际部署中既实用又高效的解决方案。

> The utilisation of foundation models as smartphone assistants, termed app agents, is a critical research challenge. These agents aim to execute human instructions on smartphones by interpreting textual instructions and performing actions via the device's interface. While promising, current approaches face significant limitations. Methods that use large proprietary models, such as GPT-4o, are computationally expensive, while those that use smaller fine-tuned models often lack adaptability to out-of-distribution tasks. In this work, we introduce AppVLM, a lightweight Vision-Language Model (VLM). First, we fine-tune it offline on the AndroidControl dataset. Then, we refine its policy by collecting data from the AndroidWorld environment and performing further training iterations. Our results indicate that AppVLM achieves the highest action prediction accuracy in offline evaluation on the AndroidControl dataset, compared to all evaluated baselines, and matches GPT-4o in online task completion success rate in the AndroidWorld environment, while being up to ten times faster. This makes AppVLM a practical and efficient solution for real-world deployment.

[Arxiv](https://arxiv.org/abs/2502.06395)