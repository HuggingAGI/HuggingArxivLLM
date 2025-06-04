# 评估基于大语言模型的推理在多目标高性能计算作业调度中的有效性

发布时间：2025年05月29日

`LLM应用` `高性能计算` `调度优化`

> Evaluating the Efficacy of LLM-Based Reasoning for Multiobjective HPC Job Scheduling

# 摘要

> 高性能计算（HPC）作业调度需要在多个相互冲突的目标之间实现高效平衡，包括缩短总完成时间、减少等待时间、优化资源利用率和确保公平性。传统调度方法，如基于启发式的“先到先得”或复杂的优化技术，往往难以应对动态负载和异构HPC系统的挑战。为了解决这一难题，我们提出了一种基于大型语言模型（LLM）的新型调度框架，采用“推理 + 行动”的ReAct式架构，实现迭代优化和可解释决策。该系统通过Scratchpad内存记录调度历史，并通过自然语言反馈不断优化决策，同时配备约束执行模块以确保调度的可行性和安全性。我们基于OpenAI的O4-Mini和Anthropic的Claude 3.7，在包含异构混合负载、突发性模式和对抗性场景的七种真实HPC工作负载下对本方法进行了全面评估。与“先到先得”、最短作业优先和Google OR-Tools（10至100个作业规模）的对比实验表明，基于LLM的调度方法在多目标优化方面表现出色，不仅能够平衡各项性能指标，还能通过自然语言推理轨迹提供透明的决策过程。该方法在约束满足方面具有显著优势，并且无需特定领域训练即可适应多样化负载需求。然而，推理质量与计算开销之间的权衡限制了其在实时调度中的应用。这项研究首次系统性地探索了具有推理能力的LLM在HPC调度领域的潜力，验证了其在多目标优化中的有效性，同时也揭示了计算效率方面的局限性。研究结果为在动态HPC环境中利用先进语言模型解决复杂调度问题提供了重要的理论支持和实践参考。


> High-Performance Computing (HPC) job scheduling involves balancing conflicting objectives such as minimizing makespan, reducing wait times, optimizing resource use, and ensuring fairness. Traditional methods, including heuristic-based (e.g., First-Come-First-Served) or intensive optimization techniques, often lack adaptability to dynamic workloads and heterogeneous HPC systems. To address this, we propose a novel Large Language Model (LLM)-based scheduler using a ReAct-style framework (Reason + Act), enabling iterative, interpretable decision-making. The system incorporates a scratchpad memory to track scheduling history and refine decisions via natural language feedback, while a constraint enforcement module ensures feasibility and safety. We evaluate our approach using OpenAI's O4-Mini and Anthropic's Claude 3.7 across seven real-world HPC workload scenarios, including heterogeneous mixes, bursty patterns, and adversarial cases. Comparisons against FCFS, Shortest Job First, and Google OR-Tools (on 10 to 100 jobs) reveal that LLM-based scheduling effectively balances multiple objectives while offering transparent reasoning through natural language traces. The method excels in constraint satisfaction and adapts to diverse workloads without domain-specific training. However, a trade-off between reasoning quality and computational overhead challenges real-time deployment. This work presents the first comprehensive study of reasoning-capable LLMs for HPC scheduling, demonstrating their potential to handle multiobjective optimization while highlighting limitations in computational efficiency. The findings provide insights into leveraging advanced language models for complex scheduling problems in dynamic HPC environments.

[Arxiv](https://arxiv.org/abs/2506.02025)