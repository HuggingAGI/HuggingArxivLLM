# 深度研究：新一代分析系统——旨在构建AI驱动分析的运行时

发布时间：2025年09月02日

`Agent` `基础理论`

> Deep Research is the New Analytics System: Towards Building the Runtime for AI-Driven Analytics

# 摘要

> 随着大型语言模型（LLMs）的不断进步，研究人员正打造能对海量非结构化数据进行AI驱动分析的新型系统。近期研究尝试通过语义算子来执行这类分析查询——这种算子是一套声明式的AI数据转换工具，可通过自然语言进行定义。但即便经过优化，这些算子在处理数百万条记录时仍成本高昂，其迭代式执行机制也难以满足交互式数据分析的需求。而在另一研究方向上，深度研究系统已能针对大型数据集回答自然语言问题。这类系统借助一个或多个LLM智能体规划执行流程、处理数据集，并不断迭代优化答案。但这类系统并未对查询计划进行显式优化，因此可能出现执行效率低下的问题。要让AI驱动的分析真正发挥作用，我们需要一种运行时环境，既能实现语义算子的高效执行，又能兼具深度研究系统的灵活性与动态性。为此，我们首先构建了一个原型系统，让深度研究智能体能够编写并执行经过优化的语义算子程序。通过评估，我们发现该原型在两个基础查询任务上的表现，优于手工编写的语义算子程序和开源深度研究系统。与标准开源深度研究智能体相比，原型的F1分数提升了1.95倍。此外，即便让智能体将语义算子当作工具使用，凭借优化的执行机制，原型仍能节省高达76.8%的成本和72.7%的运行时间。

> With advances in large language models (LLMs), researchers are creating new systems that can perform AI-driven analytics over large unstructured datasets. Recent work has explored executing such analytics queries using semantic operators -- a declarative set of AI-powered data transformations with natural language specifications. However, even when optimized, these operators can be expensive to execute on millions of records and their iterator execution semantics make them ill-suited for interactive data analytics tasks. In another line of work, Deep Research systems have demonstrated an ability to answer natural language question(s) over large datasets. These systems use one or more LLM agent(s) to plan their execution, process the dataset(s), and iteratively refine their answer. However, these systems do not explicitly optimize their query plans which can lead to poor plan execution. In order for AI-driven analytics to excel, we need a runtime which combines the optimized execution of semantic operators with the flexibility and more dynamic execution of Deep Research systems. As a first step towards this vision, we build a prototype which enables Deep Research agents to write and execute optimized semantic operator programs. We evaluate our prototype and demonstrate that it can outperform a handcrafted semantic operator program and open Deep Research systems on two basic queries. Compared to a standard open Deep Research agent, our prototype achieves up to 1.95x better F1-score. Furthermore, even if we give the agent access to semantic operators as tools, our prototype still achieves cost and runtime savings of up to 76.8% and 72.7% thanks to its optimized execution.

[Arxiv](https://arxiv.org/abs/2509.02751)