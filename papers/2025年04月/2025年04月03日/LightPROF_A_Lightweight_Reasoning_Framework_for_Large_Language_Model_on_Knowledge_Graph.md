# LightPROF：知识图谱上大型语言模型的轻量级推理框架

发布时间：2025年04月03日

`LLM应用` `知识图谱`

> LightPROF: A Lightweight Reasoning Framework for Large Language Model on Knowledge Graph

# 摘要

> 大型语言模型（LLMs）在文本理解和零样本推理方面表现卓越，但知识更新的延迟可能导致推理错误或产生有害结果。知识图谱（KGs）通过结构化组织和连接实体与关系，为LLMs提供丰富可靠的情境信息。然而，现有基于KG的推理方法仅以文本形式注入知识，忽略了结构信息，且依赖参数量大的模型，带来高资源消耗。为此，我们提出轻量高效的LightPROF框架，充分挖掘LLMs潜力，以参数高效的方式解决复杂推理任务。

具体而言，LightPROF采用“检索-嵌入-推理”流程：首先通过检索模块从KG中精准稳定地获取推理图；然后利用基于Transformer的知识适配器，从KG中提取整合事实与结构信息，并将其映射至LLM的token嵌入空间，生成LLM友好的提示进行最终推理。LightPROF仅需训练知识适配器，即可与任意开源LLM兼容。实验表明，LightPROF在小规模LLMs上表现优异，且在输入令牌数量和推理时间方面具有显著优势。

> Large Language Models (LLMs) have impressive capabilities in text understanding and zero-shot reasoning. However, delays in knowledge updates may cause them to reason incorrectly or produce harmful results. Knowledge Graphs (KGs) provide rich and reliable contextual information for the reasoning process of LLMs by structurally organizing and connecting a wide range of entities and relations. Existing KG-based LLM reasoning methods only inject KGs' knowledge into prompts in a textual form, ignoring its structural information. Moreover, they mostly rely on close-source models or open-source models with large parameters, which poses challenges to high resource consumption. To address this, we propose a novel Lightweight and efficient Prompt learning-ReasOning Framework for KGQA (LightPROF), which leverages the full potential of LLMs to tackle complex reasoning tasks in a parameter-efficient manner. Specifically, LightPROF follows a "Retrieve-Embed-Reason process", first accurately, and stably retrieving the corresponding reasoning graph from the KG through retrieval module. Next, through a Transformer-based Knowledge Adapter, it finely extracts and integrates factual and structural information from the KG, then maps this information to the LLM's token embedding space, creating an LLM-friendly prompt to be used by the LLM for the final reasoning. Additionally, LightPROF only requires training Knowledge Adapter and can be compatible with any open-source LLM. Extensive experiments on two public KGQA benchmarks demonstrate that LightPROF achieves superior performance with small-scale LLMs. Furthermore, LightPROF shows significant advantages in terms of input token count and reasoning time.

[Arxiv](https://arxiv.org/abs/2504.03137)