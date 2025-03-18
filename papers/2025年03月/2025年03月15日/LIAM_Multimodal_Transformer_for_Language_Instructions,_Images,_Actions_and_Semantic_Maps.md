# LIAM：语言指令、图像、动作与语义地图的多模态变压器模型

发布时间：2025年03月15日

`LLM应用` `家庭服务机器人` `多模态输入`

> LIAM: Multimodal Transformer for Language Instructions, Images, Actions and Semantic Maps

# 摘要

> 大型语言模型和开放词汇对象感知方法的结合，为家庭服务机器人注入了更多灵活性。通过为机器人配备任务描述和环境信息，无需逐一实现每个任务，即可轻松应对家庭场景的多样性。我们提出了一种名为LIAM的端到端模型，它基于语言、图像、动作和地图输入来预测动作记录。语言和图像输入采用CLIP主干编码，为此我们设计了两个预训练任务，用于微调权重并预对齐潜在空间。我们在ALFRED数据集上进行了实验，这是一个专为家庭任务设计的模拟器生成基准。实验结果表明，预对齐不同模态的嵌入空间至关重要，而语义地图的引入也显著提升了性能。

> The availability of large language models and open-vocabulary object perception methods enables more flexibility for domestic service robots. The large variability of domestic tasks can be addressed without implementing each task individually by providing the robot with a task description along with appropriate environment information. In this work, we propose LIAM - an end-to-end model that predicts action transcripts based on language, image, action, and map inputs. Language and image inputs are encoded with a CLIP backbone, for which we designed two pre-training tasks to fine-tune its weights and pre-align the latent spaces. We evaluate our method on the ALFRED dataset, a simulator-generated benchmark for domestic tasks. Our results demonstrate the importance of pre-aligning embedding spaces from different modalities and the efficacy of incorporating semantic maps.

[Arxiv](https://arxiv.org/abs/2503.12230)