# # REAL：通过真实网站的确定性模拟评估自主代理性能

发布时间：2025年04月15日

`Agent` `人工智能` `电子商务`

> REAL: Benchmarking Autonomous Agents on Deterministic Simulations of Real Websites

# 摘要

> 我们推出 REAL，一个用于在真实世界网站的可预测模拟中进行多轮次智能体评估的基准和框架。REAL 包含 11 个跨领域广泛使用的高保真度网站副本，涵盖电子商务、旅游、通信和职业社交等领域。我们还发布了一个包含 112 个实际任务的基准，这些任务模拟了日常复杂的用户交互，需要准确的信息检索和状态改变操作。所有交互均在完全受控的环境中进行，消除了安全风险，并能够对智能体的能力和可靠性进行强大、可重复的评估。我们的创新评估框架结合了基于网站状态的程序化检查和基于评分标准的 LLM 判断，支持信息检索任务。该框架支持开源和专有智能体系统，通过一个灵活的评估工具，可以在浏览器环境中容纳黑盒命令，使研究实验室无需修改即可测试智能系统。我们的实证结果显示，前沿语言模型在 REAL 上的最高成功率为 41%，凸显了在自主网页导航和任务完成能力方面的关键差距。我们的框架支持新任务的轻松集成、可重复评估以及用于训练网页智能体的可扩展数据生成。网站、框架和排行榜可在 https://realevals.xyz 和 https://github.com/agi-inc/REAL 获取。

> We introduce REAL, a benchmark and framework for multi-turn agent evaluations on deterministic simulations of real-world websites. REAL comprises high-fidelity, deterministic replicas of 11 widely-used websites across domains such as e-commerce, travel, communication, and professional networking. We also release a benchmark consisting of 112 practical tasks that mirror everyday complex user interactions requiring both accurate information retrieval and state-changing actions. All interactions occur within this fully controlled setting, eliminating safety risks and enabling robust, reproducible evaluation of agent capability and reliability. Our novel evaluation framework combines programmatic checks of website state for action-based tasks with rubric-guided LLM-based judgments for information retrieval. The framework supports both open-source and proprietary agent systems through a flexible evaluation harness that accommodates black-box commands within browser environments, allowing research labs to test agentic systems without modification. Our empirical results show that frontier language models achieve at most a 41% success rate on REAL, highlighting critical gaps in autonomous web navigation and task completion capabilities. Our framework supports easy integration of new tasks, reproducible evaluation, and scalable data generation for training web agents. The websites, framework, and leaderboard are available at https://realevals.xyz and https://github.com/agi-inc/REAL.

[Arxiv](https://arxiv.org/abs/2504.11543)