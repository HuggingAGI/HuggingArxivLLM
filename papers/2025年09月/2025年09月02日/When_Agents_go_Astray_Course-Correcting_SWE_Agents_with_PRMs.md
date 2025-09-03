# 智能体误入歧途时：基于PRMs的软件工程智能体航向纠偏

发布时间：2025年09月02日

`Agent` `工业与制造`

> When Agents go Astray: Course-Correcting SWE Agents with PRMs

# 摘要

> 大型语言模型（LLM）智能体正越来越多地应用于复杂的多步骤软件工程（SWE）任务。然而，其执行轨迹往往存在代价高昂的低效问题，例如冗余探索、循环往复，以及在找到解决方案后仍无法终止。先前的研究大多采用事后处理方式应对这些错误，仅在执行结束后才诊断失败。本文提出SWE-PRM——一种推理时过程奖励模型（PRM），它能在执行过程中主动干预，检测并纠正轨迹级错误。该PRM设计基于常见低效问题的分类体系，可提供轻量级、可解释的反馈，且无需修改底层策略。在SWE-bench Verified基准测试中，闭源PRM将任务解决率从40.0%提升至50.6%（提高10.6个百分点），其中中高难度任务的性能提升最为显著。在反馈策略方面，分类法引导的PRM表现优于无引导或显式动作指令型变体，在提高成功率的同时缩短了轨迹长度。这些优势的额外推理成本低至0.2美元，性价比可观，使得PRM成为提升SWE智能体可靠性与效率的实用且可扩展的机制。

> Large Language Model (LLM) agents are increasingly deployed for complex, multi-step software engineering (SWE) tasks. However, their trajectories often contain costly inefficiencies, such as redundant exploration, looping, and failure to terminate once a solution is reached. Prior work has largely treated these errors in a post-hoc manner, diagnosing failures only after execution. In this paper, we introduce SWE-PRM, an inference-time Process Reward Model (PRM) that intervenes during execution to detect and course-correct trajectory-level errors. Our PRM design leverages a taxonomy of common inefficiencies and delivers lightweight, interpretable feedback without modifying the underlying policy. On SWE-bench Verified, closed-source PRMs improve resolution from 40.0% to 50.6% (+10.6 p.p.), with the largest gains on medium and hard tasks. Among feedback strategies, taxonomy-guided PRMs outperform unguided or explicit action-prescriptive variants, increasing success rate while reducing trajectory length. These benefits come at an acceptable added inference cost of as low as $0.2, making PRMs a practical and scalable mechanism for improving SWE agents' reliability and efficiency.

[Arxiv](https://arxiv.org/abs/2509.02360)