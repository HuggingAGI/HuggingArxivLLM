# ProMQA-Assembly：装配领域的多模态程序性问答数据集

发布时间：2025年09月02日

`LLM应用` `工业与制造`

> ProMQA-Assembly: Multimodal Procedural QA Dataset on Assembly

# 摘要

> 装配任务助手潜力巨大，能在从日常任务到工业场景的各类活动中为人类提供帮助。但目前缺乏能在实际场景中支持面向应用的系统评估的测试平台，装配领域尤其如此。为推动这一领域发展，我们构建了一个全新的装配活动多模态问答数据集。该数据集名为ProMQA-Assembly，包含391个问答对，要求以在线交互的方式对人类活动记录及其说明书进行多模态理解。在数据集构建中，我们采用半自动化问答标注方法：利用大型语言模型生成候选答案，再由人工验证，既经济高效，又通过整合细粒度动作标签来丰富问题类型，进一步优化了标注流程。此外，我们还为玩具车组装这一目标任务构建了指令任务图。这些新构建的任务图不仅用于基准测试实验，还能辅助问答标注中的人工验证环节。基于该数据集，我们对多种模型进行了基准测试，其中包括性能领先的专有多模态模型。结果显示，现有模型仍有较大提升空间。我们相信，这个新评估数据集将为程序活动助手的进一步发展提供有力支持。

> Assistants on assembly tasks have a large potential to benefit humans from everyday tasks to industrial settings. However, no testbeds support application-oriented system evaluation in a practical setting, especially in assembly. To foster the development, we propose a new multimodal QA dataset on assembly activities. Our dataset, ProMQA-Assembly, consists of 391 QA pairs that require the multimodal understanding of human-activity recordings and their instruction manuals in an online-style manner. In the development, we adopt a semi-automated QA annotation approach, where LLMs generate candidates and humans verify them, as a cost-effective method, and further improve it by integrating fine-grained action labels to diversify question types. Furthermore, we create instruction task graphs for the target tasks of assembling toy vehicles. These newly created task graphs are used in our benchmarking experiment, as well as to facilitate the human verification process in the QA annotation. Utilizing our dataset, we benchmark models, including competitive proprietary multimodal models. Our results suggest great room for improvement for the current models. We believe our new evaluation dataset can contribute to the further development of procedural-activity assistants.

[Arxiv](https://arxiv.org/abs/2509.02949)