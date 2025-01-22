# EndoChat: 多模态大语言模型在内窥镜手术中的落地应用

发布时间：2025年01月20日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在机器人辅助手术中的应用，特别是EndoChat模型的开发及其在手术场景理解中的表现。论文的重点在于如何利用MLLMs来解决实际应用中的问题，因此属于LLM应用类别。` `机器人辅助手术`

> EndoChat: Grounded Multimodal Large Language Model for Endoscopic Surgery

# 摘要

> # 摘要
最近，多模态大型语言模型（MLLMs）在计算机辅助诊断和决策中展现了巨大潜力。在机器人辅助手术领域，MLLMs可作为手术训练和指导的有效工具。然而，临床应用中仍缺乏专门用于手术场景理解的MLLMs。为此，我们推出了EndoChat，旨在解决外科医生在手术场景理解中遇到的各种对话范式和子任务。为训练EndoChat，我们通过创新管道构建了Surg-396K数据集，系统提取手术信息并基于大规模内窥镜手术数据生成结构化注释。此外，我们引入了多尺度视觉标记交互机制和视觉对比推理机制，以增强模型的表示学习和推理能力。EndoChat在五种对话范式和八种手术场景理解任务中表现卓越。专业外科医生的评估反馈也大多积极。总体而言，EndoChat在推动机器人辅助手术训练和自动化方面展现出巨大潜力。

> Recently, Multimodal Large Language Models (MLLMs) have demonstrated their immense potential in computer-aided diagnosis and decision-making. In the context of robotic-assisted surgery, MLLMs can serve as effective tools for surgical training and guidance. However, there is still a lack of MLLMs specialized for surgical scene understanding in clinical applications. In this work, we introduce EndoChat to address various dialogue paradigms and subtasks in surgical scene understanding that surgeons encounter. To train our EndoChat, we construct the Surg-396K dataset through a novel pipeline that systematically extracts surgical information and generates structured annotations based on collected large-scale endoscopic surgery datasets. Furthermore, we introduce a multi-scale visual token interaction mechanism and a visual contrast-based reasoning mechanism to enhance the model's representation learning and reasoning capabilities. Our model achieves state-of-the-art performance across five dialogue paradigms and eight surgical scene understanding tasks. Additionally, we conduct evaluations with professional surgeons, most of whom provide positive feedback on collaborating with EndoChat. Overall, these results demonstrate that our EndoChat has great potential to significantly advance training and automation in robotic-assisted surgery.

[Arxiv](https://arxiv.org/abs/2501.11347)