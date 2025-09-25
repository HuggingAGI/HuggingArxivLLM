# 知识库感知型编排：多智能体系统的动态化隐私保护方法

发布时间：2025年09月23日

`Agent` `基础理论`

> Knowledge Base-Aware Orchestration: A Dynamic, Privacy-Preserving Method for Multi-Agent Systems

# 摘要

> 多智能体系统（MAS）在解决复杂知识密集型问题时，智能体的高效协同变得尤为关键。传统协同方法依赖静态的智能体描述，这类描述常因更新不及时或信息不全而失效，进而导致任务分配效率低下——尤其在智能体能力持续进化的动态环境中问题更为突出。为此，我们提出了知识库感知（KBA）协同框架：一种通过从各智能体内部知识库（KB）提取动态且隐私保护的相关性信号，来增强静态描述的创新方法。在该框架下，当静态描述无法支撑明确的任务分配决策时，协同器会并行向子智能体发出查询。各智能体随即依据自身私有知识库评估任务相关性，并返回轻量级ACK信号，全程不泄露底层数据。收集到的信号会填充至共享语义缓存，为后续任务查询提供智能体适配性的动态参考。通过将这一创新机制与静态描述融合，我们的方法实现了更精准、自适应的任务分配，同时确保智能体的自主性和数据隐私不受影响。实验数据显示，KBA协同框架在任务分配精度和系统整体效率上均显著超越静态描述驱动方法，非常适合对准确性要求高于传统描述驱动分配的大规模系统。

> Multi-agent systems (MAS) are increasingly tasked with solving complex, knowledge-intensive problems where effective agent orchestration is critical. Conventional orchestration methods rely on static agent descriptions, which often become outdated or incomplete. This limitation leads to inefficient task routing, particularly in dynamic environments where agent capabilities continuously evolve. We introduce Knowledge Base-Aware (KBA) Orchestration, a novel approach that augments static descriptions with dynamic, privacy-preserving relevance signals derived from each agent's internal knowledge base (KB). In the proposed framework, when static descriptions are insufficient for a clear routing decision, the orchestrator prompts the subagents in parallel. Each agent then assesses the task's relevance against its private KB, returning a lightweight ACK signal without exposing the underlying data. These collected signals populate a shared semantic cache, providing dynamic indicators of agent suitability for future queries. By combining this novel mechanism with static descriptions, our method achieves more accurate and adaptive task routing preserving agent autonomy and data confidentiality. Benchmarks show that our KBA Orchestration significantly outperforms static description-driven methods in routing precision and overall system efficiency, making it suitable for large-scale systems that require higher accuracy than standard description-driven routing.

[Arxiv](https://arxiv.org/abs/2509.19599)