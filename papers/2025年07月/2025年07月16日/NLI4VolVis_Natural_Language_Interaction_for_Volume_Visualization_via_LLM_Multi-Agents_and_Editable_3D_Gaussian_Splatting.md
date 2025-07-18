# NLI4VolVis: 基于 LLM 多智能体与可编辑 3D 高斯体素的自然语言交互式体积可视化

发布时间：2025年07月16日

`LLM应用` `计算机图形学` `可视化`

> NLI4VolVis: Natural Language Interaction for Volume Visualization via LLM Multi-Agents and Editable 3D Gaussian Splatting

# 摘要

> 传统体积可视化（VolVis）方法，如直接体绘制，受限于 rigid的转移函数设计和高昂的计算成本。尽管新型视图合成方法提升了渲染效率，但它们对非专家用户而言需要额外的学习投入，并且缺乏语义层面的交互支持。为了解决这一问题，我们提出了NLI4VolVis，一个交互式系统，使用户能够使用自然语言探索、查询和编辑体积场景。

NLI4VolVis结合多视图语义分割和视觉-语言模型，提取并理解场景中的语义组件。我们引入了一个配备丰富功能调用工具的多智能体大型语言模型架构，用于解析用户意图并执行可视化任务。这些智能体利用外部工具和声明式的VolVis命令与基于3D可编辑高斯函数的VolVis引擎互动，支持开放词汇对象查询、实时场景编辑、最佳视图选择和2D风格化。

我们通过案例研究和用户研究验证了我们的系统，突显其在体积数据探索中更高的可访问性和可用性。我们强烈建议读者访问https://nli4volvis.github.io/查看我们的案例研究、演示视频和源代码。

> Traditional volume visualization (VolVis) methods, like direct volume rendering, suffer from rigid transfer function designs and high computational costs. Although novel view synthesis approaches enhance rendering efficiency, they require additional learning effort for non-experts and lack support for semantic-level interaction. To bridge this gap, we propose NLI4VolVis, an interactive system that enables users to explore, query, and edit volumetric scenes using natural language. NLI4VolVis integrates multi-view semantic segmentation and vision-language models to extract and understand semantic components in a scene. We introduce a multi-agent large language model architecture equipped with extensive function-calling tools to interpret user intents and execute visualization tasks. The agents leverage external tools and declarative VolVis commands to interact with the VolVis engine powered by 3D editable Gaussians, enabling open-vocabulary object querying, real-time scene editing, best-view selection, and 2D stylization. We validate our system through case studies and a user study, highlighting its improved accessibility and usability in volumetric data exploration. We strongly recommend readers check our case studies, demo video, and source code at https://nli4volvis.github.io/.

[Arxiv](https://arxiv.org/abs/2507.12621)