# LLM 作为知识图谱推理器：基于直觉感知的知识图谱推理助力冷启动序列推荐
发布时间：2024年12月16日


> LLM is Knowledge Graph Reasoner: LLM's Intuition-aware Knowledge Graph Reasoning for Cold-start Sequential Recommendation
>
> # 摘要
知识图谱（KGs）以图结构表示实体间关系，是实现精准内容推荐的有力工具。然而，传统KG推荐方法存在两大挑战：时间信息利用不足和冷启动场景表现不佳。与此同时，大型语言模型（LLMs）作为从海量网络数据中学习的知识库，因其在推荐系统中的应用潜力而备受关注。尽管LLMs推荐方法能发挥其高推荐素养，但输入令牌限制使其难以处理整个推荐领域数据集，导致可扩展性问题。为此，我们提出了LLM直觉感知知识图谱推理模型（LIKR）。该模型将LLMs视为输出KG探索策略的推理器，通过强化学习训练推荐代理，整合LLM直觉和KG嵌入等推荐策略。LIKR通过提示工程融入时间意识，并从有限交互中生成用户偏好文本表示，从而提升冷启动场景的推荐性能。此外，LIKR利用KGs表示推荐领域数据集，并将LLM输出限制为KG探索策略，有效避免了可扩展性问题。真实数据集实验表明，LIKR在冷启动顺序推荐场景中优于现有最先进方法。
>
> https://arxiv.org/abs/2412.12464

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.12464](https://arxiv.org/abs/2412.12464)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)