# # 基于大型语言模型的多机器人任务分配与调度自动 MILP 模型构建方法

发布时间：2025年03月17日

`LLM应用` `制造业` `生产调度`

> Automatic MILP Model Construction for Multi-Robot Task Allocation and Scheduling Based on Large Language Models

# 摘要

> 工业4.0的快速发展推动了智能生产系统在多机器人系统中对高效任务分配和调度的需求。然而，现有方法依赖领域专业知识，并在适应动态生产约束方面面临挑战。此外，企业对生产调度数据的高隐私要求限制了基于云的大型语言模型（LLMs）在解决方案开发中的应用。为应对这些挑战，本研究提出了一种知识增强的混合整数线性规划（MILP）自动化建模框架，将本地LLMs与领域知识库结合，从自然语言描述中自动生成可执行代码。该框架采用知识引导的DeepSeek-R1-Distill-Qwen-32B模型提取复杂时空约束（平均准确率82%），并借助监督微调的Qwen2.5-Coder-7B-Instruct模型高效生成MILP代码（平均准确率90%）。实验结果表明，该框架在飞机蒙皮制造案例中成功实现自动建模，同时确保了数据隐私和计算效率。这项研究为复杂工业场景提供了低门槛且高度可靠的建模技术路径。

> With the accelerated development of Industry 4.0, intelligent manufacturing systems increasingly require efficient task allocation and scheduling in multi-robot systems. However, existing methods rely on domain expertise and face challenges in adapting to dynamic production constraints. Additionally, enterprises have high privacy requirements for production scheduling data, which prevents the use of cloud-based large language models (LLMs) for solution development. To address these challenges, there is an urgent need for an automated modeling solution that meets data privacy requirements. This study proposes a knowledge-augmented mixed integer linear programming (MILP) automated formulation framework, integrating local LLMs with domain-specific knowledge bases to generate executable code from natural language descriptions automatically. The framework employs a knowledge-guided DeepSeek-R1-Distill-Qwen-32B model to extract complex spatiotemporal constraints (82% average accuracy) and leverages a supervised fine-tuned Qwen2.5-Coder-7B-Instruct model for efficient MILP code generation (90% average accuracy). Experimental results demonstrate that the framework successfully achieves automatic modeling in the aircraft skin manufacturing case while ensuring data privacy and computational efficiency. This research provides a low-barrier and highly reliable technical path for modeling in complex industrial scenarios.

[Arxiv](https://arxiv.org/abs/2503.13813)