# 在交互式多模态通信中，通过结构化任务关系提升组合型 LLM 推理能力。

发布时间：2025年07月28日

`LLM应用` `车联网` `无线网络`

> Advancing Compositional LLM Reasoning with Structured Task Relations in Interactive Multimodal Communications

# 摘要

> 交互式多模态应用（IMAs），如车联网中的路线规划，通过无线网络整合多种数据形式，为用户带来个性化的丰富体验。近期，大型语言模型（LLMs）的进步利用了混合专家（MoE）机制来增强多种IMAs的能力，每个LLM针对特定任务进行单独训练，这些任务展示了不同的业务工作流程。与现有依赖多个LLMs实现IMAs的方法不同，本文提出了一种全新范式，通过单一组合型LLM在无线网络中实现多种IMAs。两大主要挑战包括：1）引导单一LLM适应多样化的IMAs目标；2）确保LLM在资源受限的移动环境中的灵活性与效率。

为解决第一个挑战，我们提出了ContextLoRA，这是一种通过构建任务依赖图引导LLM学习IMAs间丰富结构化上下文的新方法。针对每个IMA，我们划分神经层的可学习参数矩阵，以促进LLM的组合。随后，我们开发了一种基于任务关系的分步微调流程，包括训练、冻结和掩蔽阶段。这使LLM能够学习任务间的推理，以实现更好的适应性，捕捉任务间的潜在依赖关系。

针对第二个挑战，我们引入了ContextGear，这是一种优化ContextLoRA训练过程的调度策略，旨在通过战略分组机制最小化计算和通信成本。在三个基准上的实验验证了所提出的ContextLoRA和ContextGear的优越性。此外，我们在实际的无线测试床上实现了我们的范式原型，展示了其在多种IMAs中的实际应用潜力。我们将向社区开源我们的代码。


> Interactive multimodal applications (IMAs), such as route planning in the Internet of Vehicles, enrich users' personalized experiences by integrating various forms of data over wireless networks. Recent advances in large language models (LLMs) utilize mixture-of-experts (MoE) mechanisms to empower multiple IMAs, with each LLM trained individually for a specific task that presents different business workflows. In contrast to existing approaches that rely on multiple LLMs for IMAs, this paper presents a novel paradigm that accomplishes various IMAs using a single compositional LLM over wireless networks. The two primary challenges include 1) guiding a single LLM to adapt to diverse IMA objectives and 2) ensuring the flexibility and efficiency of the LLM in resource-constrained mobile environments. To tackle the first challenge, we propose ContextLoRA, a novel method that guides an LLM to learn the rich structured context among IMAs by constructing a task dependency graph. We partition the learnable parameter matrix of neural layers for each IMA to facilitate LLM composition. Then, we develop a step-by-step fine-tuning procedure guided by task relations, including training, freezing, and masking phases. This allows the LLM to learn to reason among tasks for better adaptation, capturing the latent dependencies between tasks. For the second challenge, we introduce ContextGear, a scheduling strategy to optimize the training procedure of ContextLoRA, aiming to minimize computational and communication costs through a strategic grouping mechanism. Experiments on three benchmarks show the superiority of the proposed ContextLoRA and ContextGear. Furthermore, we prototype our proposed paradigm on a real-world wireless testbed, demonstrating its practical applicability for various IMAs. We will release our code to the community.

[Arxiv](https://arxiv.org/abs/2507.21199)