# 内隐学习：情景记忆借助对经验的灵活复用，为参数化学习提供补充

发布时间：2025年09月19日

`其他` `基础理论`

> Latent learning: episodic memory complements parametric learning by enabling flexible reuse of experiences

# 摘要

> 机器学习系统何时会泛化失败？又有哪些机制能提升其泛化能力？为此，我们从认知科学中获得启发，指出机器学习系统的一大短板在于缺乏“潜伏学习”能力——即学习那些与当前任务无关、但未来可能派上用场的信息。我们发现，这一视角能将诸多失败案例串联起来，从语言建模中的“反转诅咒”，到基于智能体导航的最新研究发现。接着，我们重点探讨了认知科学的启示——情景记忆或许是解决这些问题的关键一环。相应地，我们证明，配备“先知检索机制”的系统能更灵活地调用学习经验，进而在上述诸多挑战中实现更优泛化。我们还找出了有效运用检索功能的核心要素，例如“示例内上下文学习”的重要性——它能帮助系统掌握跨检索示例调用信息的能力。总之，我们的研究结果揭示了当前机器学习系统相较于自然智能数据效率偏低的一个潜在原因，并有助于理解检索方法如何与参数学习互补，从而提升泛化性能。

> When do machine learning systems fail to generalize, and what mechanisms could improve their generalization? Here, we draw inspiration from cognitive science to argue that one weakness of machine learning systems is their failure to exhibit latent learning -- learning information that is not relevant to the task at hand, but that might be useful in a future task. We show how this perspective links failures ranging from the reversal curse in language modeling to new findings on agent-based navigation. We then highlight how cognitive science points to episodic memory as a potential part of the solution to these issues. Correspondingly, we show that a system with an oracle retrieval mechanism can use learning experiences more flexibly to generalize better across many of these challenges. We also identify some of the essential components for effectively using retrieval, including the importance of within-example in-context learning for acquiring the ability to use information across retrieved examples. In summary, our results illustrate one possible contributor to the relative data inefficiency of current machine learning systems compared to natural intelligence, and help to understand how retrieval methods can complement parametric learning to improve generalization.

[Arxiv](https://arxiv.org/abs/2509.16189)