# # QuestBench：大型语言模型 (LLMs) 能否在推理任务中提出正确的问题以获取信息？
发布时间：2025年03月28日


> QuestBench: Can LLMs ask the right question to acquire information in reasoning tasks?
>
> 近年来，研究者们致力于提升大型语言模型（LLMs）在数学和逻辑推理等领域的表现。然而，这些研究大多基于任务明确无误的假设。在现实应用中，LLMs收到的查询往往不完整，需要通过获取缺失信息来解决。我们将这类问题形式化为一个带有缺失变量赋值的约束满足问题（CSP）。通过研究该形式化的一个特例——仅有一个必要变量赋值缺失的情况，我们能够系统评估LLM识别最小必要问题的能力，并量化每个问题的难度水平。我们提出了QuestBench，一套可通过最多提问一个问题即可解决的不完整推理任务集，包括：(1) Logic-Q：含一个缺失命题的逻辑推理任务，(2) Planning-Q：初始状态部分可观测的PDDL规划问题，(3) GSM-Q：含一个人工标注的缺失变量赋值的小学数学题，以及(4) GSME-Q：与GSM-Q类似，但由人工标注者将文字问题转化为方程。LLM的任务是从选项中选择正确的澄清问题。尽管当前最优模型在GSM-Q和GSME-Q上表现出色，但在Logic-Q和Planning-Q上的准确率仅为40-50%。分析表明，解决明确问题的能力可能不足以在我们的基准上取得成功：模型难以识别出正确的提问，即使它们能够解决完全指定版本的问题。此外，在Planning-Q领域，LLMs倾向于不进行保守预测，即使明确提供了“不确定”的预测选项。这凸显了对模型信息获取能力进行更深入研究的必要性。
>
> https://arxiv.org/abs/2503.22674

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.22674](https://arxiv.org/abs/2503.22674)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)