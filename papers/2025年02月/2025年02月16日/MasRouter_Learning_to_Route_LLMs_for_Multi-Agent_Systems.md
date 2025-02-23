# MasRouter：为多智能体系统智能路由大型语言模型

发布时间：2025年02月16日

`Agent` `多智能体系统` `系统优化`

> MasRouter: Learning to Route LLMs for Multi-Agent Systems

# 摘要

> 基于大型语言模型（LLMs）的多智能体系统（MAS）虽然拓展了LLMs的能力边界，但在成本控制和动态选择LLMs方面仍面临诸多挑战。现有的LLM路由方法虽能在单智能体场景下通过定制化选择降低开销，却忽视了MAS中协作模式与智能体角色选择这一关键问题。针对这一难题，我们首次提出了多智能体系统路由（MASR）问题，并将其所有组件整合到统一的路由框架中。为此，我们推出了MasRouter——首个高性能、经济高效且具有归纳能力的MASR解决方案。MasRouter通过级联控制器网络实现协作模式确定、角色分配和LLM路由，逐步构建出一个兼具有效性和效率的MAS。实验结果表明，MasRouter在以下方面表现卓越：（1）性能优越，在MBPP上比现有最优方法提升了1.8%~8.2%；（2）经济性突出，在HumanEval上与现有最优方法相比，开销降低了52.07%；（3）灵活易用，可无缝集成到主流MAS框架中，通过定制路由进一步降低17.21%~28.17%的开销。项目代码已开源，访问地址为https://github.com/yanweiyue/masrouter。

> Multi-agent systems (MAS) powered by Large Language Models (LLMs) have been demonstrated to push the boundaries of LLM capabilities, yet they often incur significant costs and face challenges in dynamic LLM selection. Current LLM routing methods effectively reduce overhead in single-agent scenarios by customizing LLM selection for each query, but they overlook the critical decisions regarding collaboration modes and agent roles in MAS. In response to this challenge, we first introduce the problem of Multi-Agent System Routing (MASR), which integrates all components of MAS into a unified routing framework. Toward this goal, we propose MasRouter, the first high-performing, cost-effective, and inductive MASR solution. MasRouter employs collaboration mode determination, role allocation, and LLM routing through a cascaded controller network, progressively constructing a MAS that balances effectiveness and efficiency. Extensive experiments demonstrate that MasRouter is (1) high-performing, achieving a $1.8\%\sim8.2\%$ improvement over the state-of-the-art method on MBPP; (2) economical, reducing overhead by up to $52.07\%$ compared to SOTA methods on HumanEval; and (3) plug-and-play, seamlessly integrating with mainstream MAS frameworks, reducing overhead by $17.21\%\sim28.17\%$ via customized routing. The code is available at https://github.com/yanweiyue/masrouter.

[Arxiv](https://arxiv.org/abs/2502.11133)