# LeAD：基于LLM的增强规划系统与端到端自动驾驶的融合

发布时间：2025年07月08日

`LLM应用` `自动驾驶` `自动驾驶系统`

> LeAD: The LLM Enhanced Planning System Converged with End-to-end Autonomous Driving

# 摘要

> 城市自动驾驶系统的大规模部署面临一个主要障碍，即复杂场景和边缘案例的普遍存在。现有系统在解析交通环境中的语义信息以及识别其他交通参与者意图方面表现不足，导致生成的决策难以与经验丰富的驾驶员推理模式保持一致。我们提出了LeAD，一种创新的双速率自动驾驶架构，将基于模仿学习的端到端（E2E）框架与大型语言模型（LLM）增强相结合。高频的E2E子系统负责维持实时的感知-规划-控制循环，而低频的LLM模块则通过多模态感知融合与高精地图提升场景理解能力。当基线规划器遇到能力限制时，该模块能够通过链式推理（CoT）推导出最优决策。我们在CARLA仿真器上的实验评估表明，LeAD在处理非常规场景方面表现出色， Leaderboard V1基准测试中获得71分，路线完成率达93%。

> A principal barrier to large-scale deployment of urban autonomous driving systems lies in the prevalence of complex scenarios and edge cases. Existing systems fail to effectively interpret semantic information within traffic contexts and discern intentions of other participants, consequently generating decisions misaligned with skilled drivers' reasoning patterns. We present LeAD, a dual-rate autonomous driving architecture integrating imitation learning-based end-to-end (E2E) frameworks with large language model (LLM) augmentation. The high-frequency E2E subsystem maintains real-time perception-planning-control cycles, while the low-frequency LLM module enhances scenario comprehension through multi-modal perception fusion with HD maps and derives optimal decisions via chain-of-thought (CoT) reasoning when baseline planners encounter capability limitations. Our experimental evaluation in the CARLA Simulator demonstrates LeAD's superior handling of unconventional scenarios, achieving 71 points on Leaderboard V1 benchmark, with a route completion of 93%.

[Arxiv](https://arxiv.org/abs/2507.05754)