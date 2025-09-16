# 青少年特发性脊柱侧凸自我管理的多模态大语言模型适配与评估：分而治之框架

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> Adapting and Evaluating Multimodal Large Language Models for Adolescent Idiopathic Scoliosis Self-Management: A Divide and Conquer Framework

# 摘要

> 本研究首次全面评估了多模态大型语言模型（MLLMs）在青少年特发性脊柱侧弯（AIS）自我管理中的应用。我们构建了含约3000张前后位X射线图像及诊断文本的数据库，并借助‘分而治之’框架对五个MLLMs展开评估——该框架涵盖视觉问答、领域知识评估及患者教育咨询评估三项任务。研究发现，MLLMs在解读复杂脊柱X光片及理解AIS护理知识方面能力有限。为应对这些局限，我们首创性地采用脊柱关键点提示来增强MLLMs性能，并编译了AIS知识库以支持检索增强生成（RAG）。结果表明，视觉提示在不同架构中的效果参差不齐，RAG则显著提升了模型在知识评估任务中的表现。研究结果显示，当前MLLMs距离实现AIS护理的个性化助手仍有较大差距，其最大瓶颈在于脊柱畸形位置（最佳准确率：0.55）和方向（最佳准确率：0.13）的准确检测能力。

> This study presents the first comprehensive evaluation of Multimodal Large Language Models (MLLMs) for Adolescent Idiopathic Scoliosis (AIS) self-management. We constructed a database of approximately 3,000 anteroposterior X-rays with diagnostic texts and evaluated five MLLMs through a `Divide and Conquer' framework consisting of a visual question-answering task, a domain knowledge assessment task, and a patient education counseling assessment task. Our investigation revealed limitations of MLLMs' ability in interpreting complex spinal radiographs and comprehending AIS care knowledge. To address these, we pioneered enhancing MLLMs with spinal keypoint prompting and compiled an AIS knowledge base for retrieval augmented generation (RAG), respectively. Results showed varying effectiveness of visual prompting across different architectures, while RAG substantially improved models' performances on the knowledge assessment task. Our findings indicate current MLLMs are far from capable in realizing personalized assistant in AIS care. The greatest challenge lies in their abilities to obtain accurate detections of spinal deformity locations (best accuracy: 0.55) and directions (best accuracy: 0.13).

[Arxiv](https://arxiv.org/abs/2509.11645)