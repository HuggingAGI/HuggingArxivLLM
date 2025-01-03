# TraceVLA: 视觉追踪提示提升通用机器人策略的时空感知

发布时间：2024年12月13日

`Agent

理由：这篇论文主要讨论了如何通过视觉轨迹提示来提升视觉-语言-动作（VLA）模型的时空感知能力，并开发了TraceVLA模型。该模型在机器人操作任务中表现出色，并且展示了强大的泛化能力。这些内容涉及到智能体（Agent）在复杂环境中的感知和决策能力，因此将其分类为Agent。` `机器人` `人工智能`

> TraceVLA: Visual Trace Prompting Enhances Spatial-Temporal Awareness for Generalist Robotic Policies

# 摘要

> 尽管预训练于大量机器人数据集的大型视觉-语言-动作（VLA）模型为机器人学习提供了通用策略，但在处理交互式机器人中的时空动态时仍显不足，尤其是在复杂操作任务中表现欠佳。为此，我们提出了视觉轨迹提示，通过视觉编码状态-动作轨迹，有效提升VLA模型的时空感知能力。我们基于15万条机器人操作轨迹数据集，使用视觉轨迹提示对OpenVLA进行微调，开发了TraceVLA模型。在SimplerEnv的137种配置和物理WidowX机器人上的4个任务中，TraceVLA表现出色，性能超越OpenVLA 10%，在真实机器人任务中更是高出3.5倍，且在不同实体和场景中展现出强大的泛化能力。为进一步验证方法的有效性和通用性，我们基于4B Phi-3-Vision构建了一个紧凑型VLA模型，该模型在Open-X-Embodiment上预训练并在我们的数据集上微调，性能与7B OpenVLA基线相当，同时显著提升了推理效率。

> Although large vision-language-action (VLA) models pretrained on extensive robot datasets offer promising generalist policies for robotic learning, they still struggle with spatial-temporal dynamics in interactive robotics, making them less effective in handling complex tasks, such as manipulation. In this work, we introduce visual trace prompting, a simple yet effective approach to facilitate VLA models' spatial-temporal awareness for action prediction by encoding state-action trajectories visually. We develop a new TraceVLA model by finetuning OpenVLA on our own collected dataset of 150K robot manipulation trajectories using visual trace prompting. Evaluations of TraceVLA across 137 configurations in SimplerEnv and 4 tasks on a physical WidowX robot demonstrate state-of-the-art performance, outperforming OpenVLA by 10% on SimplerEnv and 3.5x on real-robot tasks and exhibiting robust generalization across diverse embodiments and scenarios. To further validate the effectiveness and generality of our method, we present a compact VLA model based on 4B Phi-3-Vision, pretrained on the Open-X-Embodiment and finetuned on our dataset, rivals the 7B OpenVLA baseline while significantly improving inference efficiency.

[Arxiv](https://arxiv.org/abs/2412.10345)