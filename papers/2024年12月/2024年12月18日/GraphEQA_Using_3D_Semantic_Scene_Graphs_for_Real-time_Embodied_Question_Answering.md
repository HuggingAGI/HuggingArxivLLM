# GraphEQA：借助 3D 语义场景图实现实时具身问答

发布时间：2024年12月18日

`Agent` `机器人` `具身问答`

> GraphEQA: Using 3D Semantic Scene Graphs for Real-time Embodied Question Answering

# 摘要

> 在具身问答（EQA）中，智能体得探索并形成对未知环境的语义理解，从而有把握地回答情境问题。这在机器人领域一直是个难题，难点在于获取有用的语义表征、在线更新这些表征，以及借助先前的世界知识来高效探索和规划。为应对这些局限，我们提出了 GraphEQA 这一创新方法，它利用实时 3D 度量语义场景图（3DSGs）和任务相关图像作为多模态记忆，让视觉语言模型（VLMs）能在未知环境中执行 EQA 任务。我们采用了分层规划的方式，借助 3DSGs 的分层特性来进行结构化规划和语义引导的探索。通过在 HM-EQA 数据集上的模拟实验以及在家庭和办公环境中的真实实验，我们表明，我们的方法在完成 EQA 任务时成功率更高、规划步骤更少，优于关键的基线。

> In Embodied Question Answering (EQA), agents must explore and develop a semantic understanding of an unseen environment in order to answer a situated question with confidence. This remains a challenging problem in robotics, due to the difficulties in obtaining useful semantic representations, updating these representations online, and leveraging prior world knowledge for efficient exploration and planning. Aiming to address these limitations, we propose GraphEQA, a novel approach that utilizes real-time 3D metric-semantic scene graphs (3DSGs) and task relevant images as multi-modal memory for grounding Vision-Language Models (VLMs) to perform EQA tasks in unseen environments. We employ a hierarchical planning approach that exploits the hierarchical nature of 3DSGs for structured planning and semantic-guided exploration. Through experiments in simulation on the HM-EQA dataset and in the real world in home and office environments, we demonstrate that our method outperforms key baselines by completing EQA tasks with higher success rates and fewer planning steps.

[Arxiv](https://arxiv.org/abs/2412.14480)