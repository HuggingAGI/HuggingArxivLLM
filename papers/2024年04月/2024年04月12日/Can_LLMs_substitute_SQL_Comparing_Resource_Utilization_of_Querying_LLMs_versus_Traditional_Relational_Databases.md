# 大型语言模型能否取代SQL？探究在查询过程中，LLMs与传统关系型数据库在资源消耗方面的对比。

发布时间：2024年04月12日

`LLM应用` `软件工程` `数据库系统`

> Can LLMs substitute SQL? Comparing Resource Utilization of Querying LLMs versus Traditional Relational Databases

# 摘要

> 大型语言模型（LLMs）能够自动执行软件工程中的多样任务。这项研究评估了LLM在解析和执行针对关系型数据库系统中SQL的自然语言查询方面的资源消耗与准确性。我们对参数规模从7亿到340亿的九种LLM进行了实证分析，包括Llama2 7B、Llama2 13B、Mistral、Mixtral、Optimus-7B、SUS-chat-34B、platypus-yi-34b、NeuralHermes-2.5-Mistral-7B和Starling-LM-7B-alpha，并采用了一个小型交易数据集作为测试对象。研究结果显示，利用LLM进行数据库查询会带来较大的能源消耗（即便对于小型和量化模型也是如此），这种做法对环境并不友好。鉴于LLM的高资源消耗，我们不建议用其取代关系型数据库。

> Large Language Models (LLMs) can automate or substitute different types of tasks in the software engineering process. This study evaluates the resource utilization and accuracy of LLM in interpreting and executing natural language queries against traditional SQL within relational database management systems. We empirically examine the resource utilization and accuracy of nine LLMs varying from 7 to 34 Billion parameters, including Llama2 7B, Llama2 13B, Mistral, Mixtral, Optimus-7B, SUS-chat-34B, platypus-yi-34b, NeuralHermes-2.5-Mistral-7B and Starling-LM-7B-alpha, using a small transaction dataset. Our findings indicate that using LLMs for database queries incurs significant energy overhead (even small and quantized models), making it an environmentally unfriendly approach. Therefore, we advise against replacing relational databases with LLMs due to their substantial resource utilization.

![大型语言模型能否取代SQL？探究在查询过程中，LLMs与传统关系型数据库在资源消耗方面的对比。](../../../paper_images/2404.08727/The_average_execution_energy_consumption_matrices_for_direct_query_results_of_LLM_models.png)

![大型语言模型能否取代SQL？探究在查询过程中，LLMs与传统关系型数据库在资源消耗方面的对比。](../../../paper_images/2404.08727/The_average_execution_energy_consumption_matrices_for_SQL_query_generation_of_LLM_models.png)

[Arxiv](https://arxiv.org/abs/2404.08727)