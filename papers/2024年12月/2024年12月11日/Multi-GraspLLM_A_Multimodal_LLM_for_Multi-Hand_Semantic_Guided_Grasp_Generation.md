# Multi-GraspLLM：一种用于多手语义引导抓取生成的多模态大语言模型。

发布时间：2024年12月11日

`LLM应用` `机器人` `抓取技术`

> Multi-GraspLLM: A Multimodal LLM for Multi-Hand Semantic Guided Grasp Generation

# 摘要

> 多手语义抓取生成的目标是依据自然语言指令，为不同的机械手生成可行且语义恰当的抓取姿态。尽管此任务意义重大，但因缺少具有机械手和物体间细粒度接触描述的多手抓取数据集，所以它一直是个难题。在本文中，我们推出了 Multi-GraspSet，这是首个带有自动接触标注的大规模多手抓取数据集。基于 Multi-GraspSet，我们提出了 Multi-GraspLLM，一个统一的语言引导抓取生成框架。它借助大型语言模型（LLM）处理可变长度序列，在单一的统一架构中为各类机械手生成抓取姿态。Multi-GraspLLM 先是将编码的点云特征与文本特征对齐到统一的语义空间，然后生成抓取箱标记，接着通过手感知线性映射为每个机械手转化为抓取姿态。实验结果显示，我们的方法在 Multi-GraspSet 上显著优于现有方法。更多信息可在我们的项目页面 https://multi-graspllm.github.io 查阅。

> Multi-hand semantic grasp generation aims to generate feasible and semantically appropriate grasp poses for different robotic hands based on natural language instructions. Although the task is highly valuable, due to the lack of multi-hand grasp datasets with fine-grained contact description between robotic hands and objects, it is still a long-standing difficult task. In this paper, we present Multi-GraspSet, the first large-scale multi-hand grasp dataset with automatically contact annotations. Based on Multi-GraspSet, we propose Multi-GraspLLM, a unified language-guided grasp generation framework. It leverages large language models (LLM) to handle variable-length sequences, generating grasp poses for diverse robotic hands in a single unified architecture. Multi-GraspLLM first aligns the encoded point cloud features and text features into a unified semantic space. It then generates grasp bin tokens which are subsequently converted into grasp pose for each robotic hand via hand-aware linear mapping. The experimental results demonstrate that our approach significantly outperforms existing methods on Multi-GraspSet. More information can be found on our project page https://multi-graspllm.github.io.

[Arxiv](https://arxiv.org/abs/2412.08468)