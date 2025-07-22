# # 配置化多智能体框架，用于对基于大语言模型的智能体进行可扩展和现实测试

发布时间：2025年07月19日

`Agent` `智能体测试` `对话系统`

> Configurable multi-agent framework for scalable and realistic testing of llm-based agents

# 摘要

> 大型语言模型（LLM）智能体的复杂行为和对上下文的敏感性，使得传统的静态基准和手动测试方法迅速过时。为此，我们推出Neo——一个可配置的多智能体框架，专注于实现基于LLM系统的多轮实际性能评估。Neo通过共享上下文中心，巧妙地结合了问题生成智能体和评估智能体，实现了领域提示、场景控制和动态反馈的模块化组合。测试输入基于涵盖对话流程、用户意图和情感基调的概率状态模型进行采样，从而生成多样化且类人化的对话，能够在每一轮对话后进行智能适应。在生产级别的卖家财务助理聊天机器人中应用，Neo不仅以3.3%的故障率（接近专家级人工红队的5.8%）发现了五个攻击类别的边缘情况故障，还实现了10-12倍的吞吐量提升，仅需45分钟即可生成180个连贯的测试问题，而人工 effort则需要16小时。Neo的随机策略在主题覆盖和对话深度之间找到了平衡，提供了比手动编写脚本更广泛的行为探索。因此，Neo为可扩展的、自我演进的LLM问答奠定了基础：其智能体接口、状态控制器和反馈循环是模型不可知论的，并且可以扩展到更丰富的事实依据和政策合规性检查。我们发布该框架，以促进对新兴智能体系统的可重复、高保真测试。

> Large-language-model (LLM) agents exhibit complex, context-sensitive behaviour that quickly renders static benchmarks and ad-hoc manual testing obsolete.
  We present Neo, a configurable, multi-agent framework that automates realistic, multi-turn evaluation of LLM-based systems. Neo couples a Question Generation Agent and an Evaluation Agent through a shared context-hub, allowing domain prompts, scenario controls and dynamic feedback to be composed modularly. Test inputs are sampled from a probabilistic state model spanning dialogue flow, user intent and emotional tone, enabling diverse, human-like conversations that adapt after every turn.
  Applied to a production-grade Seller Financial Assistant chatbot, Neo (i) uncovered edge-case failures across five attack categories with a 3.3% break rate close to the 5.8% achieved by expert human red-teamers, and (ii) delivered 10-12X higher throughput, generating 180 coherent test questions in around 45 mins versus 16h of human effort. Beyond security probing, Neo's stochastic policies balanced topic coverage and conversational depth, yielding broader behavioural exploration than manually crafted scripts.
  Neo therefore lays a foundation for scalable, self-evolving LLM QA: its agent interfaces, state controller and feedback loops are model-agnostic and extensible to richer factual-grounding and policy-compliance checks. We release the framework to facilitate reproducible, high-fidelity testing of emerging agentic systems.

[Arxiv](https://arxiv.org/abs/2507.14705)