# 基于知识图谱增强与大型语言模型强化框架的复杂系统诊断

发布时间：2025年05月27日

`LLM应用` `核电站` `能源行业`

> Complex System Diagnostics Using a Knowledge Graph-Informed and Large Language Model-Enhanced Framework

# 摘要

> 本文提出了一种创新性的诊断框架，融合知识图谱（KGs）和大语言模型（LLMs），专为核电站等高可靠性系统设计。传统诊断方法在处理复杂系统时常常显得力不从心，因此我们采用基于功能建模的动态主逻辑（DML）模型，构建了一个全新的诊断体系。该框架巧妙结合了两个LLM组件：一个用于从系统文档自动生成DML逻辑的工作流，另一个是辅助诊断的智能代理。生成的逻辑被整合到结构化的KG（KG-DML）中，支持多层次的故障推理。通过引入专家知识或运行数据，模型的诊断精度和深度得以进一步优化。在实际应用中，用户只需以自然语言提出问题，智能代理便会解析并选择合适的工具进行分析，包括在KG-DML中进行上下推演。不同于传统的提示嵌入方法，智能代理能够区分诊断与解释任务：对于诊断，它会调用外部工具进行结构化推理；对于普通查询，则采用基于图的检索增强生成（Graph-RAG）方法，结合KG片段生成自然解释。案例研究证实，该框架在关键诊断要素上达到了90%以上的准确率，并能稳定提取诊断依据，充分证明了其在安全关键诊断中的应用价值。

> In this paper, we present a novel diagnostic framework that integrates Knowledge Graphs (KGs) and Large Language Models (LLMs) to support system diagnostics in high-reliability systems such as nuclear power plants. Traditional diagnostic modeling struggles when systems become too complex, making functional modeling a more attractive approach. Our approach introduces a diagnostic framework grounded in the functional modeling principles of the Dynamic Master Logic (DML) model. It incorporates two coordinated LLM components, including an LLM-based workflow for automated construction of DML logic from system documentation and an LLM agent that facilitates interactive diagnostics. The generated logic is encoded into a structured KG, referred to as KG-DML, which supports hierarchical fault reasoning. Expert knowledge or operational data can also be incorporated to refine the model's precision and diagnostic depth. In the interaction phase, users submit natural language queries, which are interpreted by the LLM agent. The agent selects appropriate tools for structured reasoning, including upward and downward propagation across the KG-DML. Rather than embedding KG content into every prompt, the LLM agent distinguishes between diagnostic and interpretive tasks. For diagnostics, the agent selects and executes external tools that perform structured KG reasoning. For general queries, a Graph-based Retrieval-Augmented Generation (Graph-RAG) approach is used, retrieving relevant KG segments and embedding them into the prompt to generate natural explanations. A case study on an auxiliary feedwater system demonstrated the framework's effectiveness, with over 90% accuracy in key elements and consistent tool and argument extraction, supporting its use in safety-critical diagnostics.

[Arxiv](https://arxiv.org/abs/2505.21291)