# 在更安全的治疗方案推荐中，评估基于LLM的多智能体系统所获得的经验与启示

发布时间：2025年07月14日

`Agent` `决策支持系统`

> Lessons Learned from Evaluation of LLM based Multi-agents in Safer Therapy Recommendation

# 摘要

> 多病共存慢性患者的治疗推荐面临治疗冲突的挑战，现有的决策支持系统在扩展性上也存在限制。受全科医生（GP）通过多学科团队（MDT）协作管理多病共存患者方式的启发，本研究探讨了基于大型语言模型（LLM）的多智能体系统（MAS）在提供更安全治疗推荐方面的潜力。我们设计了一个单智能体和MAS框架，通过模拟MDT决策过程，使LLM智能体之间能够讨论解决医疗冲突。我们使用基准案例对多病共存患者的治疗规划任务进行了评估，并将MAS的表现与单智能体方法及真实世界基准进行了对比。研究的重要贡献在于定义了超越技术精确度和召回率的评估指标，能够检查建议的临床目标达成情况及其相对于黄金标准基准的用药负担。结果显示，使用当前LLMs，单智能体GP的表现可与MDT媲美。得分最高的模型提供了满足所有临床目标的正确建议，但建议内容尚不完整。一些模型还提出了不必要的药物，导致药物与病情或药物间不必要的相互作用。

> Therapy recommendation for chronic patients with multimorbidity is challenging due to risks of treatment conflicts. Existing decision support systems face scalability limitations. Inspired by the way in which general practitioners (GP) manage multimorbidity patients, occasionally convening multidisciplinary team (MDT) collaboration, this study investigated the feasibility and value of using a Large Language Model (LLM)-based multi-agent system (MAS) for safer therapy recommendations. We designed a single agent and a MAS framework simulating MDT decision-making by enabling discussion among LLM agents to resolve medical conflicts. The systems were evaluated on therapy planning tasks for multimorbidity patients using benchmark cases. We compared MAS performance with single-agent approaches and real-world benchmarks. An important contribution of our study is the definition of evaluation metrics that go beyond the technical precision and recall and allow the inspection of clinical goals met and medication burden of the proposed advices to a gold standard benchmark. Our results show that with current LLMs, a single agent GP performs as well as MDTs. The best-scoring models provide correct recommendations that address all clinical goals, yet the advices are incomplete. Some models also present unnecessary medications, resulting in unnecessary conflicts between medication and conditions or drug-drug interactions.

[Arxiv](https://arxiv.org/abs/2507.10911)