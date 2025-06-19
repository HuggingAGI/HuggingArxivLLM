# # SwarmAgentic: 基于群体智能实现完全自动化的智能体系统生成

发布时间：2025年06月18日

`Agent` `智能体系统` `自动化`

> SwarmAgentic: Towards Fully Automated Agentic System Generation via Swarm Intelligence

# 摘要

> 大型语言模型的快速发展显著推动了智能体系统在决策、协调和任务执行能力上的进步。然而，现有的智能体系统生成框架在完全自主性方面仍显不足，缺乏从零开始生成智能体、自我优化的智能体功能以及协作能力，这严重限制了其适应性和扩展性。我们提出了SwarmAgentic，一个完全自动化的智能体系统生成框架。该框架从零开始构建智能体系统，并通过语言驱动的探索，将智能体功能和协作能力作为相互依赖的组件进行联合优化。为了实现对系统级结构的高效搜索，SwarmAgentic维护一组候选系统，并通过反馈引导的更新进行演化，这一方法灵感来源于粒子群优化（PSO）。我们在六个涉及高层规划、系统级协调和创造性推理的真实、开放性和探索性任务中评估了SwarmAgentic。仅凭任务描述和目标函数，SwarmAgentic在TravelPlanner基准上比ADAS高出261.8%的相对改进，优于所有基线，凸显了完全自动化在结构无约束任务中的有效性。这一框架标志着向可扩展和自主的智能体系统设计迈出的重要一步，成功将群智能与完全自动化的多智能体系统生成相结合。我们的代码已公开发布于https://yaoz720.github.io/SwarmAgentic/。

> The rapid progress of Large Language Models has advanced agentic systems in decision-making, coordination, and task execution. Yet, existing agentic system generation frameworks lack full autonomy, missing from-scratch agent generation, self-optimizing agent functionality, and collaboration, limiting adaptability and scalability. We propose SwarmAgentic, a framework for fully automated agentic system generation that constructs agentic systems from scratch and jointly optimizes agent functionality and collaboration as interdependent components through language-driven exploration. To enable efficient search over system-level structures, SwarmAgentic maintains a population of candidate systems and evolves them via feedback-guided updates, drawing inspiration from Particle Swarm Optimization (PSO). We evaluate our method on six real-world, open-ended, and exploratory tasks involving high-level planning, system-level coordination, and creative reasoning. Given only a task description and an objective function, SwarmAgentic outperforms all baselines, achieving a +261.8% relative improvement over ADAS on the TravelPlanner benchmark, highlighting the effectiveness of full automation in structurally unconstrained tasks. This framework marks a significant step toward scalable and autonomous agentic system design, bridging swarm intelligence with fully automated system multi-agent generation. Our code is publicly released at https://yaoz720.github.io/SwarmAgentic/.

[Arxiv](https://arxiv.org/abs/2506.15672)