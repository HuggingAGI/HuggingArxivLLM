# 全面评测：多语言大语言模型在前端工程工作流中的基准测试

发布时间：2025年05月22日

`LLM应用` `软件工程`

> FullFront: Benchmarking MLLMs Across the Full Front-End Engineering Workflow

# 摘要

> 前端工程是一个从设计构思到代码实现再到持续优化的复杂流程。现有基准测试主要关注将视觉设计转化为代码，而我们提出的FullFront则是一个全面评估多模态大语言模型（MLLMs）在前端开发全流程中能力的基准测试。FullFront聚焦三个核心任务：网页设计（概念化阶段）、网页感知质量保证（理解视觉组织与元素）和网页代码生成（实现阶段）。与现有基准测试使用臃肿的爬取网站或简化的LLM生成HTML不同，FullFront采用创新的两阶段流程，将真实网页转换为干净标准化的HTML，同时保持多样化视觉设计并规避版权问题。测试显示，当前MLLMs在页面感知、代码生成（尤其在图像处理和布局方面）以及交互实现方面存在明显局限。我们的研究定量展示了不同模型和任务之间的性能差异，并揭示了MLLMs与人类专家在前端工程能力上的显著差距。FullFront基准测试和代码已在GitHub上开放：https://github.com/Mikivishy/FullFront。

> Front-end engineering involves a complex workflow where engineers conceptualize designs, translate them into code, and iteratively refine the implementation. While recent benchmarks primarily focus on converting visual designs to code, we present FullFront, a benchmark designed to evaluate Multimodal Large Language Models (MLLMs) \textbf{across the full front-end development pipeline}. FullFront assesses three fundamental tasks that map directly to the front-end engineering pipeline: Webpage Design (conceptualization phase), Webpage Perception QA (comprehension of visual organization and elements), and Webpage Code Generation (implementation phase). Unlike existing benchmarks that use either scraped websites with bloated code or oversimplified LLM-generated HTML, FullFront employs a novel, two-stage process to transform real-world webpages into clean, standardized HTML while maintaining diverse visual designs and avoiding copyright issues. Extensive testing of state-of-the-art MLLMs reveals significant limitations in page perception, code generation (particularly for image handling and layout), and interaction implementation. Our results quantitatively demonstrate performance disparities across models and tasks, and highlight a substantial gap between current MLLM capabilities and human expert performance in front-end engineering. The FullFront benchmark and code are available in https://github.com/Mikivishy/FullFront.

[Arxiv](https://arxiv.org/abs/2505.17399)