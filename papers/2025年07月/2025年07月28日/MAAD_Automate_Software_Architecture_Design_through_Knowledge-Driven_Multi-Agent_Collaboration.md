# MAAD: 利用知识驱动的多智能体协作技术实现软件架构设计自动化

发布时间：2025年07月28日

`Agent` `软件工程` `软件开发`

> MAAD: Automate Software Architecture Design through Knowledge-Driven Multi-Agent Collaboration

# 摘要

> 软件架构设计是软件开发中至关重要但复杂且知识密集的阶段。它不仅需要深厚的专业领域知识、开发经验和架构理解，还需要在相互竞争的质量属性之间做出权衡，并适应不断变化的需求。传统上，这一过程耗时且劳动密集，高度依赖架构师，尤其在敏捷开发的压力下，往往导致设计替代方案有限。

尽管基于大型语言模型（LLM）的代理在多种软件工程任务中表现出色，但它们在架构设计中的应用仍然相对较少，尤其是在应对多样化的领域知识和复杂的决策制定方面，需要进一步探索。为了解决这些挑战，我们提出了MAAD（多代理架构设计），这是一个采用知识驱动的多代理系统（MAS）的自动化框架，用于架构设计。

MAAD协调四个专门的代理（分析师、建模师、设计师和评估师），协同工作以解释需求规格并生成包含基于质量属性的评估报告的架构蓝图。我们通过案例研究和与先进MAS基线MetaGPT的比较实验来评估MAAD。结果显示，MAAD的优势在于生成全面的架构组件，并提供深入且结构化的架构评估报告。

来自11个需求规格的工业界架构师反馈进一步证实了MAAD的实际可用性。最后，我们探索了MAAD框架在三个大型语言模型（GPT-4o、DeepSeek-R1和Llama 3.3）上的性能，发现GPT-4o在生成架构设计方面表现更优，突显了在MAS驱动的架构设计中选择合适LLM的重要性。

> Software architecture design is a critical, yet inherently complex and knowledge-intensive phase of software development. It requires deep domain expertise, development experience, architectural knowledge, careful trade-offs among competing quality attributes, and the ability to adapt to evolving requirements. Traditionally, this process is time-consuming and labor-intensive, and relies heavily on architects, often resulting in limited design alternatives, especially under the pressures of agile development. While Large Language Model (LLM)-based agents have shown promising performance across various SE tasks, their application to architecture design remains relatively scarce and requires more exploration, particularly in light of diverse domain knowledge and complex decision-making. To address the challenges, we proposed MAAD (Multi-Agent Architecture Design), an automated framework that employs a knowledge-driven Multi-Agent System (MAS) for architecture design. MAAD orchestrates four specialized agents (i.e., Analyst, Modeler, Designer and Evaluator) to collaboratively interpret requirements specifications and produce architectural blueprints enriched with quality attributes-based evaluation reports. We then evaluated MAAD through a case study and comparative experiments against MetaGPT, a state-of-the-art MAS baseline. Our results show that MAAD's superiority lies in generating comprehensive architectural components and delivering insightful and structured architecture evaluation reports. Feedback from industrial architects across 11 requirements specifications further reinforces MAAD's practical usability. We finally explored the performance of the MAAD framework with three LLMs (GPT-4o, DeepSeek-R1, and Llama 3.3) and found that GPT-4o exhibits better performance in producing architecture design, emphasizing the importance of LLM selection in MAS-driven architecture design.

[Arxiv](https://arxiv.org/abs/2507.21382)