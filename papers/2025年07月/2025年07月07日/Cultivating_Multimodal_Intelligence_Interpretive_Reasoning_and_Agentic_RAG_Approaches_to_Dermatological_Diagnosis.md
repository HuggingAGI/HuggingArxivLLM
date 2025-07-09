# 探索多模态智能：通过解释性推理与自主式RAG方法实现皮肤科诊断

发布时间：2025年07月07日

`RAG` `皮肤病`

> Cultivating Multimodal Intelligence: Interpretive Reasoning and Agentic RAG Approaches to Dermatological Diagnosis

# 摘要

> 由微软、斯坦福大学和巴塞罗那clinic医院联合举办的2025年ImageCLEF MEDIQA-MAGIC挑战赛第二届专注于多模态皮肤科问答和分割任务，采用真实患者的查询和图像。本研究聚焦于封闭式视觉问答（CVQA）任务，目标是基于用户提供的图像和症状描述，从多个选项中准确选出正确答案。研究采用三元核心方法：（1）微调开源多模态模型（Qwen、Gemma和LLaMA系列）于竞赛数据集；（2）引入结构化推理层以协调候选模型输出；（3）结合智能检索增强生成（agentic RAG），从美国皮肤病学会数据库中补充相关资料。团队以第六名的成绩获得亚军，展现了强劲实力和高精度。该研究不仅突破了竞赛基准，还解决了远程医疗中的实际难题：在输入有限的情况下，需异步完成高精度、高可解释性的诊断决策。通过模拟皮肤科医生的系统性推理模式，该架构为构建更可靠的自动化诊断支持系统开辟了新路径。

> The second edition of the 2025 ImageCLEF MEDIQA-MAGIC challenge, co-organized by researchers from Microsoft, Stanford University, and the Hospital Clinic of Barcelona, focuses on multimodal dermatology question answering and segmentation, using real-world patient queries and images. This work addresses the Closed Visual Question Answering (CVQA) task, where the goal is to select the correct answer to multiple-choice clinical questions based on both user-submitted images and accompanying symptom descriptions. The proposed approach combines three core components: (1) fine-tuning open-source multimodal models from the Qwen, Gemma, and LLaMA families on the competition dataset, (2) introducing a structured reasoning layer that reconciles and adjudicates between candidate model outputs, and (3) incorporating agentic retrieval-augmented generation (agentic RAG), which adds relevant information from the American Academy of Dermatology's symptom and condition database to fill in gaps in patient context. The team achieved second place with a submission that scored sixth, demonstrating competitive performance and high accuracy. Beyond competitive benchmarks, this research addresses a practical challenge in telemedicine: diagnostic decisions must often be made asynchronously, with limited input and with high accuracy and interpretability. By emulating the systematic reasoning patterns employed by dermatologists when evaluating skin conditions, this architecture provided a pathway toward more reliable automated diagnostic support systems.

[Arxiv](https://arxiv.org/abs/2507.05520)