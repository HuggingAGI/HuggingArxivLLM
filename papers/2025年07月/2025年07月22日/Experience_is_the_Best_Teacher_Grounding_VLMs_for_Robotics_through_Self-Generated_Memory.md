# 经验是最好的老师：通过自动生成的记忆，让VLMs在机器人领域中扎根

发布时间：2025年07月22日

`Agent

摘要中提到的ExpTeach框架结合了视觉语言模型（VLMs）与物理机器人，强调自主规划、动作验证、反思和调整行为，这些都是智能体的关键特征。虽然提到了RAG方法，但其主要目的是为了增强智能体的自主性和学习能力，因此归类为Agent类别。` `机器人技术` `人工智能`

> Experience is the Best Teacher: Grounding VLMs for Robotics through Self-Generated Memory

# 摘要

> 视觉语言模型（VLMs）在机器人自主规划中得到广泛应用。然而，将最初基于网络数据训练的VLMs应用于多种真实机器人仍具挑战性。本文提出了一种名为ExpTeach的框架，通过构建基于真实经验的自主生成记忆库，将VLMs与物理机器人相结合。在ExpTeach框架中，VLM能够自主规划动作、验证结果、反思失败并以闭环形式调整机器人行为。在此过程中生成的经验随后被总结为长期记忆，通过检索增强生成（RAG）方法检索学习到的知识以指导未来任务。此外，ExpTeach还配备了一个按需图像标注模块，以提升VLM的空间理解能力。实验结果表明，通过反思机制，ExpTeach在四个具有挑战性的机器人任务中将成功率从36%提升至84%，并观察到了智能物体交互的出现，包括创造性工具使用。在12个真实场景（包括8个未见过的场景）的广泛测试中，我们发现结合长期记忆的框架使单次成功率从22%提升至80%，充分证明了ExpTeach的有效性和泛化能力。

> Vision-language models (VLMs) have been widely adopted in robotics to enable autonomous planning. However, grounding VLMs, originally trained on internet data, to diverse real-world robots remains a challenge. This paper presents ExpTeach, a framework that grounds VLMs to physical robots by building a self-generated memory of real-world experiences. In ExpTeach, the VLM autonomously plans actions, verifies outcomes, reflects on failures, and adapts robot behaviors in a closed loop. The self-generated experiences during this process are then summarized into a long-term memory, enabling retrieval of learned knowledge to guide future tasks via retrieval-augmented generation (RAG). Additionally, ExpTeach enhances the spatial understanding of VLMs with an on-demand image annotation module. In experiments, we show that reflection improves success rates from 36% to 84% on four challenging robotic tasks and observe the emergence of intelligent object interactions, including creative tool use. Across extensive tests on 12 real-world scenarios (including eight unseen ones), we find that grounding with long-term memory boosts single-trial success rates from 22% to 80%, demonstrating the effectiveness and generalizability of ExpTeach.

[Arxiv](https://arxiv.org/abs/2507.16713)