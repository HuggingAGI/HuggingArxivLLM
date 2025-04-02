# 思考更久，而非一味求大：通过扩展推理计算资源提升软件工程代理能力
发布时间：2025年03月31日

`代码编写`
> Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute
>
> 软件工程代理在自动化程序改进方面展现出巨大潜力。然而，这些代理对闭源或资源密集型模型的依赖，在私有环境中的部署面临严峻挑战。这促使我们思考：	extit{开源且个人可部署的LLM能否实现与现有方案相当的代码推理性能？}
    为解决这一问题，我们提出了一种统一的推理时计算缩放框架，通过提升推理时计算量而非依赖更大模型来优化性能。我们的框架包含两大互补策略：内部推理时计算与外部推理时计算。
    在内部推理时计算中，我们创新性地提出了一种基于真实软件仓库的	extit{开发上下文感知的轨迹合成方法}，用于启动故障定位、补丁生成等多阶段推理流程。我们通过拒绝采样机制优化推理轨迹质量，并从准确性和复杂性两个维度严格评估轨迹。
    在外部推理时计算方面，我们设计了一种全新的	extit{基于开发过程的搜索策略}，该策略由奖励模型和执行验证共同引导。这种方法能够在关键开发决策点实现计算资源的精准分配，有效克服现有仅基于“终点验证”的方法局限性。
    实验结果表明，我们的	extbf{320亿参数模型在SWE-bench Verified基准测试中达到了46%的问题解决率}，显著超越了更大规模的模型如DeepSeek R1 671B和OpenAI o1。此外，我们首次实验证明了推理时缩放现象在SWE代理中的有效性，发现	extbf{模型会智能地为更具挑战性的问题分配更多计算资源}，从而显著提升推理能力。
    为推动相关研究，我们公开发布了所有训练数据、模型和代码。访问我们的GitHub仓库了解更多细节：https://github.com/yingweima2022/SWE-Reasoner
>
> https://arxiv.org/abs/2503.23803

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.23803](https://arxiv.org/abs/2503.23803)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)