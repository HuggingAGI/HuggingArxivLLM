# # 标题
复杂任务的分层规划：结合知识图谱增强检索增强生成（RAG）与符号验证

发布时间：2025年04月06日

`LLM应用` `机器人` `任务规划`

> Hierarchical Planning for Complex Tasks with Knowledge Graph-RAG and Symbolic Verification

# 摘要

> 大型语言模型（LLMs）在机器人规划领域展现出潜力，但面对长期复杂任务，尤其在需要外部知识的专门环境中，仍面临挑战。现有的分层规划和检索增强生成（RAG）方法虽能部分解决问题，但需更深层次的结合才能构建更可靠的系统。为此，我们提出一种神经符号方法，通过基于知识图谱的RAG增强LLM规划器，实现分层计划生成。该方法将复杂任务分解为可管理的子任务，并进一步转化为可执行的原子动作序列。为确保分解的正确性，我们引入符号验证器，该组件不仅验证形式上的正确性，还能通过匹配预期与观察到的世界状态检测故障。实验结果表明，将分层规划、符号验证与RAG相结合的方法在不同复杂度和不同LLMs的任务中均表现出显著优势。此外，我们的实验设计和新提出的评估指标不仅验证了该方法在复杂规划中的有效性，还为评估LLMs的推理与组合能力提供了工具。


> Large Language Models (LLMs) have shown promise as robotic planners but often struggle with long-horizon and complex tasks, especially in specialized environments requiring external knowledge. While hierarchical planning and Retrieval-Augmented Generation (RAG) address some of these challenges, they remain insufficient on their own and a deeper integration is required for achieving more reliable systems. To this end, we propose a neuro-symbolic approach that enhances LLMs-based planners with Knowledge Graph-based RAG for hierarchical plan generation. This method decomposes complex tasks into manageable subtasks, further expanded into executable atomic action sequences. To ensure formal correctness and proper decomposition, we integrate a Symbolic Validator, which also functions as a failure detector by aligning expected and observed world states. Our evaluation against baseline methods demonstrates the consistent significant advantages of integrating hierarchical planning, symbolic verification, and RAG across tasks of varying complexity and different LLMs. Additionally, our experimental setup and novel metrics not only validate our approach for complex planning but also serve as a tool for assessing LLMs' reasoning and compositional capabilities.

[Arxiv](https://arxiv.org/abs/2504.04578)