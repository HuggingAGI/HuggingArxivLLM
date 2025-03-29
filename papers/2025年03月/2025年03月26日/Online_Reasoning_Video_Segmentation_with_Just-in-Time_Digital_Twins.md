# 在线推理视频分割与实时数字孪生

发布时间：2025年03月26日

`LLM应用

论文摘要讨论了如何利用大型语言模型（LLMs）在推理分割任务中的应用，提出了一种新的框架来优化LLM的使用，解决现有方法的限制。因此，这篇论文属于LLM应用类别。` `视频处理` `计算机视觉`

> Online Reasoning Video Segmentation with Just-in-Time Digital Twins

# 摘要

> 推理分割（RS）的目标是基于隐式文本查询识别并分割感兴趣的对象。它为具身AI代理提供了重要推动力，使其能够理解高层次指令，无需明确的分步指导。然而，当前RS方法严重依赖多模态大型语言模型（LLMs）的视觉感知能力，导致几项重大限制。首先，它们难以处理需要多步推理或涉及复杂空间/时间关系的查询。其次，它们需要对LLM进行微调，这可能需要频繁更新以保持与当代LLMs的兼容性，并可能在微调过程中增加灾难性遗忘的风险。最后，由于主要设计用于静态图像或离线视频处理，它们对在线视频数据的扩展性较差。为了解决这些限制，我们提出了一种代理框架，该框架在不进行LLM微调的情况下，将感知与推理分离，用于在线视频RS。我们的创新在于引入了一种“及时”数字孪生概念：给定一个隐式查询，LLM计划使用专业视觉模型从高层次视频构建低层次场景表示。我们称这种创建数字孪生的方法为“及时”，因为LLM规划器会预见到对特定信息的需求，并仅请求这一有限子集，而不是总是评估每个专业模型。随后，LLM在此数字孪生表示上进行推理以识别目标对象。为了评估我们的方法，我们引入了一个新的综合性视频推理分割基准，包含200个视频和895个隐式文本查询。该基准涵盖三个推理类别（语义、空间和时间），并具有三种不同的推理链复杂度。

> Reasoning segmentation (RS) aims to identify and segment objects of interest based on implicit text queries. As such, RS is a catalyst for embodied AI agents, enabling them to interpret high-level commands without requiring explicit step-by-step guidance. However, current RS approaches rely heavily on the visual perception capabilities of multimodal large language models (LLMs), leading to several major limitations. First, they struggle with queries that require multiple steps of reasoning or those that involve complex spatial/temporal relationships. Second, they necessitate LLM fine-tuning, which may require frequent updates to maintain compatibility with contemporary LLMs and may increase risks of catastrophic forgetting during fine-tuning. Finally, being primarily designed for static images or offline video processing, they scale poorly to online video data. To address these limitations, we propose an agent framework that disentangles perception and reasoning for online video RS without LLM fine-tuning. Our innovation is the introduction of a just-in-time digital twin concept, where -- given an implicit query -- a LLM plans the construction of a low-level scene representation from high-level video using specialist vision models. We refer to this approach to creating a digital twin as "just-in-time" because the LLM planner will anticipate the need for specific information and only request this limited subset instead of always evaluating every specialist model. The LLM then performs reasoning on this digital twin representation to identify target objects. To evaluate our approach, we introduce a new comprehensive video reasoning segmentation benchmark comprising 200 videos with 895 implicit text queries. The benchmark spans three reasoning categories (semantic, spatial, and temporal) with three different reasoning chain complexity.

[Arxiv](https://arxiv.org/abs/2503.21056)