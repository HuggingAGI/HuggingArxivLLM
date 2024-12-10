# 在自动驾驶中利用指令引导的交互器进行世界知识增强型推理

发布时间：2024年12月09日

`LLM应用` `自动驾驶` `多模态数据集`

> World knowledge-enhanced Reasoning Using Instruction-guided Interactor in Autonomous Driving

# 摘要

> 多模态大型语言模型（MLLMs）因具备丰富的世界知识，让自动驾驶重焕生机，尤其在可感知区域内的推理任务方面表现出色。然而，在面对感知受限区域（动态或静态遮挡区域）时，MLLMs 难以有效融合感知能力与世界知识来进行推理。这些区域可能隐藏关键的安全信息，对脆弱道路使用者而言更是如此。本文中，我们提出一个框架，旨在强化感知能力与世界知识的整合，以提升感知受限条件下的自动驾驶性能。具体来说，我们提出了一个即插即用的指令引导交互模块，它能弥合模态差异，大幅缩短输入序列长度，从而有效适配多视图视频输入。另外，为将世界知识与驾驶相关任务更好地结合，我们收集并优化了一个大规模多模态数据集，包含 200 万个自然语言问答对、170 万个基础任务数据。为评估模型对世界知识的运用情况，我们引入了一个包含 20 万个问答对的对象级风险评估数据集，其中的问题需要借助世界知识进行多步推理才能解决。大量实验证明了我们所提方法的有效性。

> The Multi-modal Large Language Models (MLLMs) with extensive world knowledge have revitalized autonomous driving, particularly in reasoning tasks within perceivable regions. However, when faced with perception-limited areas (dynamic or static occlusion regions), MLLMs struggle to effectively integrate perception ability with world knowledge for reasoning. These perception-limited regions can conceal crucial safety information, especially for vulnerable road users. In this paper, we propose a framework, which aims to improve autonomous driving performance under perceptionlimited conditions by enhancing the integration of perception capabilities and world knowledge. Specifically, we propose a plug-and-play instruction-guided interaction module that bridges modality gaps and significantly reduces the input sequence length, allowing it to adapt effectively to multi-view video inputs. Furthermore, to better integrate world knowledge with driving-related tasks, we have collected and refined a large-scale multi-modal dataset that includes 2 million natural language QA pairs, 1.7 million grounding task data. To evaluate the model's utilization of world knowledge, we introduce an object-level risk assessment dataset comprising 200K QA pairs, where the questions necessitate multi-step reasoning leveraging world knowledge for resolution. Extensive experiments validate the effectiveness of our proposed method.

[Arxiv](https://arxiv.org/abs/2412.06324)