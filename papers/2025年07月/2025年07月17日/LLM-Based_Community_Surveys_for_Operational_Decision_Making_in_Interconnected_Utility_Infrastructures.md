# # 基于LLM的社区调查在互联公用事业基础设施中的运营决策应用

发布时间：2025年07月17日

`LLM应用

理由：这篇论文主要探讨了在灾害期间修复基础设施的决策问题，并提出了一种结合异构功能图（HFG）和社区偏好的方法。其中，论文创新性地使用了大型语言模型（LLM）作为代理调研工具，用于生成不同角色和灾害场景，从而收集社区对修复顺序的偏好意见。这表明论文的重点在于将LLM应用于实际问题中，属于LLM的应用研究。` `基础设施` `灾害管理`

> LLM-Based Community Surveys for Operational Decision Making in Interconnected Utility Infrastructures

# 摘要

> 我们采用异构功能图（HFG）来建模相互依赖的基础设施系统和社区，该图清晰地展现了各功能间的依赖关系。这种图结构自然形成了一种功能偏序，为灾害期间的修复决策提供了有益的顺序参考。然而，仅凭这些技术标准在功能直接影响社区的实际操作层面指导有限，因为功能修复顺序可根据具体情况进行调整，不会违背系统约束。为弥补这一研究空白并提升整体韧性，我们引入社区偏好，将HFG中的偏序关系优化为全序。我们的方法是通过调研获取社区对修复顺序的偏好意见，同时考虑资源限制因素。鉴于真实世界调研数据获取的延迟与成本问题，我们创新性地采用大型语言模型（LLM）作为代理调研工具。具体而言，我们利用LLM生成代表不同个体的独特角色，每个角色均基于不同的灾害经历设定。随后，我们构建多样化灾害场景，每个模拟角色针对不同社区的基础设施修复优先级提供反馈。最后，我们运用学习算法，基于这些LLM生成角色的聚合反馈，生成一个全局统一的修复顺序方案。

> We represent interdependent infrastructure systems and communities alike with a hetero-functional graph (HFG) that encodes the dependencies between functionalities. This graph naturally imposes a partial order of functionalities that can inform the sequence of repair decisions to be made during a disaster across affected communities. However, using such technical criteria alone provides limited guidance at the point where the functionalities directly impact the communities, since these can be repaired in any order without violating the system constraints. To address this gap and improve resilience, we integrate community preferences to refine this partial order from the HFG into a total order. Our strategy involves getting the communities' opinions on their preferred sequence for repair crews to address infrastructure issues, considering potential constraints on resources. Due to the delay and cost associated with real-world survey data, we utilize a Large Language Model (LLM) as a proxy survey tool. We use the LLM to craft distinct personas representing individuals, each with varied disaster experiences. We construct diverse disaster scenarios, and each simulated persona provides input on prioritizing infrastructure repair needs across various communities. Finally, we apply learning algorithms to generate a global order based on the aggregated responses from these LLM-generated personas.

[Arxiv](https://arxiv.org/abs/2507.13577)