# FlashRecovery：大型语言模型（LLMs）大规模训练的快速低成本故障恢复

发布时间：2025年09月03日

`其他` `基础理论`

> FlashRecovery: Fast and Low-Cost Recovery from Failures for Large-Scale Training of LLMs

# 摘要

> 大型语言模型（LLMs）凭借卓越性能在各领域产生了深远影响。然而，以前所未有的规模训练这些模型需依赖庞大的AI加速器集群和复杂的并行策略，这给长时间训练中的系统可靠性带来了严峻挑战——硬件与软件故障难以避免，由此造成的训练时间损耗十分严重。为应对这些挑战，我们提出了FlashRecovery——一套快速低成本的故障恢复系统，核心包含三大模块：（1）主动实时故障检测：通过持续监控训练状态，可在数秒内即时识别软硬件故障，确保事件快速响应；（2）规模无关的任务重启：针对正常节点与故障节点采用差异化恢复策略，并结合优化的通信组重建协议，确保恢复时间不受集群规模影响，基本保持恒定；（3）单步无检查点恢复：创新的恢复机制支持一步到位的恢复，彻底摆脱对传统检查点方法的依赖及由此产生的额外开销。这些创新共同助力FlashRecovery实现了最优的恢复时间目标（RTO）和恢复点目标（RPO），大幅提升了长时间LLM训练的可靠性与效率。实验结果显示，FlashRecovery系统可在包含4800个设备的训练集群中150秒内完成训练恢复，且不同规模训练任务的故障恢复时间基本保持一致。

> Large language models (LLMs) have made a profound impact across various fields due to their advanced capabilities. However, training these models at unprecedented scales requires extensive AI accelerator clusters and sophisticated parallelism strategies, which pose significant challenges in maintaining system reliability over prolonged training periods. A major concern is the substantial loss of training time caused by inevitable hardware and software failures. To address these challenges, we present FlashRecovery, a fast and low-cost failure recovery system comprising three core modules: (1) Active and real-time failure detection. This module performs continuous training state monitoring, enabling immediate identification of hardware and software failures within seconds, thus ensuring rapid incident response; (2) Scale-independent task restart. By employing different recovery strategies for normal and faulty nodes, combined with an optimized communication group reconstruction protocol, our approach ensures that the recovery time remains nearly constant, regardless of cluster scale; (3) Checkpoint-free recovery within one step. Our novel recovery mechanism enables single-step restoration, completely eliminating dependence on traditional checkpointing methods and their associated overhead. Collectively, these innovations enable FlashRecovery to achieve optimal Recovery Time Objective (RTO) and Recovery Point Objective (RPO), substantially improving the reliability and efficiency of long-duration LLM training. Experimental results demonstrate that FlashRecovery system can achieve training restoration on training cluster with 4, 800 devices in 150 seconds. We also verify that the time required for failure recovery is nearly consistent for different scales of training tasks.

[Arxiv](https://arxiv.org/abs/2509.03047)