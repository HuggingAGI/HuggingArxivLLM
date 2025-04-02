# # 情境化自主无人机导航，通过边缘云计算部署的大型语言模型实现

发布时间：2025年04月01日

`LLM应用` `自动驾驶`

> Contextualized Autonomous Drone Navigation using LLMs Deployed in Edge-Cloud Computing

# 摘要

> 自动驾驶导航通常在多种场景下进行离线训练，并根据实际经验进行在线微调。然而，现实世界充满动态变化，许多环境变化/影响由于难以在离线训练数据中描述，甚至在在线场景中也难以描述，因此无法实时考虑。然而，我们知道人类操作员可以通过自然语言描述这些动态环境变化，添加语义背景。这项研究旨在部署大语言模型（LLMs）来实时调整自动驾驶导航的上下文代码。文献中未评估的挑战在于哪些LLMs是合适的，以及这些计算密集型算法应在计算-通信边缘-云计算架构中放置在哪里。本文评估了不同LLMs如何动态调整导航地图参数（例如，轮廓图形状）并推导出导航任务指令集。然后，我们评估哪种LLMs最适合，并应在未来的6G通信边缘-云计算架构中放置在哪里。

> Autonomous navigation is usually trained offline in diverse scenarios and fine-tuned online subject to real-world experiences. However, the real world is dynamic and changeable, and many environmental encounters/effects are not accounted for in real-time due to difficulties in describing them within offline training data or hard to describe even in online scenarios. However, we know that the human operator can describe these dynamic environmental encounters through natural language, adding semantic context. The research is to deploy Large Language Models (LLMs) to perform real-time contextual code adjustment to autonomous navigation. The challenge not evaluated in literature is what LLMs are appropriate and where should these computationally heavy algorithms sit in the computation-communication edge-cloud computing architectures. In this paper, we evaluate how different LLMs can adjust both the navigation map parameters dynamically (e.g., contour map shaping) and also derive navigation task instruction sets. We then evaluate which LLMs are most suitable and where they should sit in future edge-cloud of 6G telecommunication architectures.

[Arxiv](https://arxiv.org/abs/2504.00607)