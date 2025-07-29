# 基于事件的三维场景多人实时互动叙事

发布时间：2025年07月25日

`LLM应用` `虚拟现实` `影视制作`

> Event-Driven Storytelling with Multiple Lifelike Humans in a 3D Scene

# 摘要

> 我们提出了一种创新框架，能够生成包含多个角色的生动虚拟动态场景，每个角色都具备符合场景的上下文动作。这一任务需要对人与人之间以及人与环境之间的复杂互动进行全面理解。我们巧妙地利用大型语言模型（LLM）的强大能力，将其转化为可处理的子问题，从而实现大规模多智能体行为的生成，突破了传统方法的限制。具体而言，我们的事件生成器将场景的时间发展分解为一系列小型事件，每个事件都涉及明确的动作和相关角色与物体。随后，我们通过空间引导对角色位置进行采样，并合成其动作。为了确保上下文的全面性和可扩展性，我们设计了一个高层模块，将事件转化为相对描述，从而能够精确定位。作为首个大规模且多样化解决这一问题的研究，我们提供了一个基准测试，以全面评估上下文推理能力。实验结果和用户研究表明，我们的框架不仅能够有效捕捉场景上下文，还具备卓越的扩展性。更多详情，包括代码、基准测试和结果视频，均可在我们的项目页面获取：https://rms0329.github.io/Event-Driven-Storytelling/。

> In this work, we propose a framework that creates a lively virtual dynamic scene with contextual motions of multiple humans. Generating multi-human contextual motion requires holistic reasoning over dynamic relationships among human-human and human-scene interactions. We adapt the power of a large language model (LLM) to digest the contextual complexity within textual input and convert the task into tangible subproblems such that we can generate multi-agent behavior beyond the scale that was not considered before. Specifically, our event generator formulates the temporal progression of a dynamic scene into a sequence of small events. Each event calls for a well-defined motion involving relevant characters and objects. Next, we synthesize the motions of characters at positions sampled based on spatial guidance. We employ a high-level module to deliver scalable yet comprehensive context, translating events into relative descriptions that enable the retrieval of precise coordinates. As the first to address this problem at scale and with diversity, we offer a benchmark to assess diverse aspects of contextual reasoning. Benchmark results and user studies show that our framework effectively captures scene context with high scalability. The code and benchmark, along with result videos, are available at our project page: https://rms0329.github.io/Event-Driven-Storytelling/.

[Arxiv](https://arxiv.org/abs/2507.19232)