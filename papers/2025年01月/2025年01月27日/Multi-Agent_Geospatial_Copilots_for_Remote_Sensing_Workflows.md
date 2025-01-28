# 多智能体地理空间协作者：遥感工作流的得力助手

发布时间：2025年01月27日

`Agent

理由：这篇论文介绍了GeoLLM-Squad，一个地理空间Copilot，它通过多智能体范式来处理遥感（RS）工作流。论文的核心在于将任务分配给专门的子智能体，实现了智能体编排与地理空间任务解决的分离。这明显涉及到多智能体系统的设计和应用，因此应归类为Agent。` `地理空间`

> Multi-Agent Geospatial Copilots for Remote Sensing Workflows

# 摘要

> 我们推出了GeoLLM-Squad，一个地理空间Copilot，它将多智能体范式引入遥感（RS）工作流。与依赖单一LLM的单智能体方法不同，GeoLLM-Squad通过将RS任务分配给专门的子智能体，实现了智能体编排与地理空间任务解决的分离。基于开源的AutoGen和GeoLLM-Engine框架，我们的工作实现了城市监测、森林保护、气候分析和农业研究等多样化应用的模块化集成。结果显示，尽管单智能体系统在应对复杂RS任务时难以扩展，但GeoLLM-Squad保持了稳健性能，智能体正确性比最先进基线提高了17%。这一发现突显了多智能体AI在推进RS工作流中的巨大潜力。

> We present GeoLLM-Squad, a geospatial Copilot that introduces the novel multi-agent paradigm to remote sensing (RS) workflows. Unlike existing single-agent approaches that rely on monolithic large language models (LLM), GeoLLM-Squad separates agentic orchestration from geospatial task-solving, by delegating RS tasks to specialized sub-agents. Built on the open-source AutoGen and GeoLLM-Engine frameworks, our work enables the modular integration of diverse applications, spanning urban monitoring, forestry protection, climate analysis, and agriculture studies. Our results demonstrate that while single-agent systems struggle to scale with increasing RS task complexity, GeoLLM-Squad maintains robust performance, achieving a 17% improvement in agentic correctness over state-of-the-art baselines. Our findings highlight the potential of multi-agent AI in advancing RS workflows.

[Arxiv](https://arxiv.org/abs/2501.16254)