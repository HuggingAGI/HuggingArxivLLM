# # WebThinker: 赋予大型推理模型深度研究能力

发布时间：2025年04月30日

`LLM应用` `科学研究` `学术领域`

> WebThinker: Empowering Large Reasoning Models with Deep Research Capability

# 摘要

> 大型推理模型（LRMs）如 OpenAI-o1 和 DeepSeek-R1 虽然展现出卓越的长时推理能力，但其静态知识库的局限性限制了在复杂任务中的表现。为突破这一限制，我们推出 	extbf{WebThinker}，赋予 LRMs 自主网络搜索与报告生成的能力。通过 	extbf{Deep Web Explorer} 模块，模型能够实时补全知识缺口，结合 	extbf{自主思考-搜索-起草策略} 实现推理与信息处理的无缝衔接。借助 	extbf{基于 RL 的训练策略}，我们进一步优化了模型的工具利用效率。在多项复杂推理基准测试和科学报告生成任务中，WebThinker 表现远超现有方案，标志着深度研究系统能力的重要突破。项目代码已开源，详情请访问 https://github.com/RUC-NLPIR/WebThinker。


> Large reasoning models (LRMs), such as OpenAI-o1 and DeepSeek-R1, demonstrate impressive long-horizon reasoning capabilities. However, their reliance on static internal knowledge limits their performance on complex, knowledge-intensive tasks and hinders their ability to produce comprehensive research reports requiring synthesis of diverse web information. To address this, we propose \textbf{WebThinker}, a deep research agent that empowers LRMs to autonomously search the web, navigate web pages, and draft research reports during the reasoning process. WebThinker integrates a \textbf{Deep Web Explorer} module, enabling LRMs to dynamically search, navigate, and extract information from the web when encountering knowledge gaps. It also employs an \textbf{Autonomous Think-Search-and-Draft strategy}, allowing the model to seamlessly interleave reasoning, information gathering, and report writing in real time. To further enhance research tool utilization, we introduce an \textbf{RL-based training strategy} via iterative online Direct Preference Optimization (DPO). Extensive experiments on complex reasoning benchmarks (GPQA, GAIA, WebWalkerQA, HLE) and scientific report generation tasks (Glaive) demonstrate that WebThinker significantly outperforms existing methods and strong proprietary systems. Our approach enhances LRM reliability and applicability in complex scenarios, paving the way for more capable and versatile deep research systems. The code is available at https://github.com/RUC-NLPIR/WebThinker.

[Arxiv](https://arxiv.org/abs/2504.21776)