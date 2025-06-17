# 查询大型汽车软件模型：智能体方法与直接LLM方法的对比

发布时间：2025年06月16日

`LLM应用` `嵌入式`

> Querying Large Automotive Software Models: Agentic vs. Direct LLM Approaches

# 摘要

> 大型语言模型（LLMs）为通过自然语言与复杂软件模型交互提供了新途径，尤其在处理难以全面掌握的大规模软件模型时展现出独特优势。本文探讨了两种基于LLMs的问答方法：直接提示和智能体方法。通过专为汽车和嵌入式领域设计的Ecore元模型评估发现，智能体方法在准确性上与直接提示相当，但在效率上更具优势，使其成为汽车行业的理想选择。此外，小型LLMs的本地执行能力为隐私和合规性要求提供了关键保障。未来研究将拓展至更多格式的软件模型和更复杂的智能体架构。

> Large language models (LLMs) offer new opportunities for interacting with complex software artifacts, such as software models, through natural language. They present especially promising benefits for large software models that are difficult to grasp in their entirety, making traditional interaction and analysis approaches challenging. This paper investigates two approaches for leveraging LLMs to answer questions over software models: direct prompting, where the whole software model is provided in the context, and an agentic approach combining LLM-based agents with general-purpose file access tools. We evaluate these approaches using an Ecore metamodel designed for timing analysis and software optimization in automotive and embedded domains. Our findings show that while the agentic approach achieves accuracy comparable to direct prompting, it is significantly more efficient in terms of token usage. This efficiency makes the agentic approach particularly suitable for the automotive industry, where the large size of software models makes direct prompting infeasible, establishing LLM agents as not just a practical alternative but the only viable solution. Notably, the evaluation was conducted using small LLMs, which are more feasible to be executed locally - an essential advantage for meeting strict requirements around privacy, intellectual property protection, and regulatory compliance. Future work will investigate software models in diverse formats, explore more complex agent architectures, and extend agentic workflows to support not only querying but also modification of software models.

[Arxiv](https://arxiv.org/abs/2506.13171)