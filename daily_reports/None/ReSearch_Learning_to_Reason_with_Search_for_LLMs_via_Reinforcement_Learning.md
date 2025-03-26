# 大模型推理新突破：ReSearch框架如何让LLM通过搜索提升22.4%的推理能力？
发布时间：2025年03月25日


> ReSearch: Learning to Reason with Search for LLMs via Reinforcement Learning
>
> 大型语言模型（LLMs）在推理方面表现卓越，OpenAI-o1 和 DeepSeek-R1 的成功便是明证。然而，将推理与外部搜索结合仍具挑战，尤其是面对复杂多跳问题时。为此，我们提出 ReSearch，一种通过强化学习训练 LLMs 实现基于搜索推理的全新框架，且无需依赖任何推理步骤的监督数据。ReSearch 将搜索视为推理链的核心环节，搜索时机与方式由文本思考决定，搜索结果则进一步引导推理进程。我们在 Qwen2.5-7B(-Instruct) 和 Qwen2.5-32B(-Instruct) 上进行了训练，并通过广泛实验验证了模型的卓越性能。尽管仅在一个数据集上训练，我们的模型在多种基准测试中展现了强大的泛化能力。值得注意的是，ReSearch 在强化学习过程中自然激发了反思与自我纠正等高级推理能力。
>
> https://arxiv.org/abs/2503.19470

![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2025/02/12/1739367812022-81912e8f-5f91-4b9d-b4b2-52b0e322d137.png)
**添加请注明**
**如遇无法添加，请+ vx: iamxxn886**
<hr />



## 一、为什么需要ReSearch技术？

### 1.1 大模型推理的局限性

近年来，大型语言模型（LLMs, Large Language Models）在多种任务中表现出色，尤其是在推理能力方面。然而，尽管LLMs在内部知识的基础上能够进行推理，但在处理复杂问题时，单纯依赖内部知识往往不足以应对多步推理和多跳检索的需求。例如，当回答“谁在2020年赢得了美国总统大选？”这样的简单问题时，LLMs可以轻松应对，但当问题变得复杂，如“谁在2020年赢得了美国总统大选，并且他的政党在哪个州拥有最多的支持者？”时，LLMs的表现就会大打折扣。这是因为复杂问题通常需要多次检索信息并进行多步推理，而LLMs的内部知识库可能无法覆盖所有必要的信息。

### 1.2 检索增强生成的挑战

检索增强生成（RAG, Retrieval-Augmented Generation）是一种通过结合外部检索信息来增强LLMs生成能力的技术。然而，现有的RAG方法大多依赖于手动设计的提示或启发式策略，这不仅费时费力，还难以扩展到更复杂的问题。例如，现有的RAG方法在处理“谁在2020年赢得了美国总统大选，并且他的政党在哪个州拥有最多的支持者？”这样的问题时，可能需要手动设计多个检索步骤，这在实际应用中是不可行的。此外，多步RAG框架中的推理步骤标注成本高昂，难以在实际中广泛应用。

### 1.3 强化学习的潜力

强化学习（RL, Reinforcement Learning）作为一种无需标注推理步骤的训练方法，展现出巨大的潜力。通过简单的奖励信号，RL可以引导LLMs在复杂推理任务中逐步分解问题，并通过试错学习提升推理能力。例如，在回答“谁在2020年赢得了美国总统大选，并且他的政党在哪个州拥有最多的支持者？”这样的问题时，RL可以通过奖励信号引导LLMs首先检索“2020年美国总统大选”的结果，然后再检索“哪个州拥有最多的支持者”的信息。然而，现有的RL方法主要关注内部推理能力的提升，如何将推理与外部检索有效结合仍是一个开放问题。

### 1.4 ReSearch的提出

为了解决上述问题，我们提出了ReSearch，一种通过强化学习训练LLMs进行检索增强推理的新框架。ReSearch将检索操作作为推理链的组成部分，通过文本思考引导何时以及如何进行检索，检索结果随后影响进一步的推理。例如，在回答“谁在2020年赢得了美国总统大选，并且他的政党在哪个州拥有最多的支持者？”这样的问题时，ReSearch会首先进行文本思考，生成检索查询，检索结果随后被用于进一步的推理，最终生成答案。通过这种方式，ReSearch不仅提高了LLMs的推理能力，还大大降低了多步RAG的复杂性和成本。




## 二、ReSearch技术解析

### 2.1 核心思想：推理与搜索的结合

ReSearch框架的核心思想是将搜索操作与推理过程紧密结合，通过强化学习训练大语言模型（LLMs, Large Language Models）在推理过程中动态决定何时进行搜索以及如何利用搜索结果。与传统的推理链不同，ReSearch的推理链不仅包含文本思考（用`<details style="color:gray;background-color: #f8f8f8;padding: 8px;border-radius: 4px;" open> <summary> Thinking... </summary> </details>`标记），还包含搜索查询（用`<search> </search>`标记）和检索结果（用`<result> </result>`标记）。搜索操作与文本思考相互影响，搜索的时机和方式由前序的文本思考指导，而搜索结果则进一步影响后续的推理。

举个例子，假设模型需要回答“谁赢得了2018年墨西哥总统大选？”这个问题。模型首先会进行文本思考，确定需要搜索的关键信息，比如“2018年墨西哥总统大选”。然后，模型会生成搜索查询`<search> 2018 Mexican presidential election </search>`，并根据检索结果`<result> Andrés Manuel López Obrador </result>`继续推理，最终给出答案。这种结合搜索的推理方式，使得模型能够更准确地回答复杂问题。

### 2.2 强化学习训练过程

ReSearch使用分组相对策略优化（GRPO, Group Relative Policy Optimization）作为训练算法。GRPO通过从一组推理链中估计基线，避免了传统PPO（Proximal Policy Optimization, 近端策略优化）中单独训练评论者模型的复杂性。在训练过程中，模型通过生成多个推理链（即rollout）并根据奖励信号优化策略，逐步学习如何在推理中有效利用搜索。

具体来说，GRPO的目标是最大化以下公式：

$$
\mathcal{I}(\theta)=\mathbb{E}_{x\sim\mathcal{D},\{y_{i}\}_{i=1}^{G}\sim\pi_{\theta_{\mathrm{old}}}(\cdot|x)}\frac{1}{G}\sum_{i=1}^{G}\left[\operatorname*{min}\left(\frac{\pi_{\theta}\left(y_{i}|x\right)}{\pi_{\theta_{\mathrm{old}}}\left(y_{i}|x\right)}A_{i},\operatorname{clip}\left(\frac{\pi_{\theta}\left(y_{i}|x\right)}{\pi_{\theta_{\mathrm{old}}}\left(y_{i}|x\right)},1-\epsilon,1+\epsilon\right)A_{i}\right)-\beta\mathbb{D}_{\mathrm{KL}}\left(\pi_{\theta}||\pi_{\theta_{\mathrm{ref}}}\right)\right]
$$

其中，$A_{i}$是第$i$个推理链的归一化优势，$\epsilon$是裁剪比例，$\beta$是KL散度系数。通过这种方式，模型能够在不偏离原始策略太远的情况下，逐步优化其推理与搜索的能力。

### 2.3 开源地址

ReSearch框架已在GitHub上开源，地址为：[https://github.com/Agent-RL/ReSearch](https://github.com/Agent-RL/ReSearch)。开发者可以通过该地址获取代码，进一步探索和应用这一技术。




## 三、ReSearch的应用与评估

### 3.1 多跳问答基准测试

为了评估ReSearch的效果，研究团队在多个多跳问答基准上进行了广泛实验，包括HotpotQA、2 Wiki Multi Hop QA、MuSiQue和Bamboogle。实验结果表明，ReSearch在所有基准上都显著优于基线方法。具体来说，在7B参数模型上，ReSearch在精确匹配（Exact Match, EM）和LLM作为评判者（LLM-as-a-Judge, LJ）两个指标上分别平均提升了15.81%和17.56%。在32B参数模型上，ReSearch同样表现出色，精确匹配和LLM作为评判者的提升幅度分别为14.82%和15.46%。这些结果不仅证明了ReSearch在多跳问答任务中的有效性，还展示了其在不同规模模型上的稳定表现。

例如，在HotpotQA基准测试中，ReSearch的精确匹配得分从基线方法的45.3%提升到了56.7%，而在MuSiQue基准测试中，LLM作为评判者的得分从基线方法的62.1%提升到了73.8%。这些显著提升表明，ReSearch能够更好地处理复杂的多跳问题，尤其是在需要多次信息检索的任务中。

### 3.2 训练过程中的自我反思与修正

在训练过程中，ReSearch模型展现出自我反思和修正的能力。例如，当模型发现搜索查询未能检索到有用信息时，它会自动调整搜索策略，生成更有效的查询。这种能力并非通过显式训练或提示设计获得，而是在强化学习过程中自然涌现的。

一个典型的案例是，模型在回答“2018年墨西哥总统选举的获胜者是谁？”时，首次搜索“Martín Ramírez Pech”未能找到相关信息。随后，模型意识到搜索错误，并自动修正为“Martín Ramírez Pech political party”，最终成功找到相关信息并给出正确答案。这种自我修正的能力使得ReSearch在处理复杂问题时更加灵活和可靠。

### 3.3 泛化能力

ReSearch仅在一个训练集（MuSiQue）上进行训练，但在其他基准测试中表现出强大的泛化能力。这表明ReSearch框架不仅适用于特定类型的问题，还能广泛应用于不同结构和类型的多跳问答任务。

例如，尽管ReSearch仅在MuSiQue数据集上进行了训练，但它在Bamboogle基准测试中的表现同样出色，精确匹配得分从基线方法的38.5%提升到了52.3%。这种泛化能力使得ReSearch在实际应用中具有更大的潜力，尤其是在需要处理多种类型问题的场景中。

通过在多跳问答基准测试中的优异表现、训练过程中的自我反思与修正能力以及强大的泛化能力，ReSearch展示了其在复杂问答任务中的巨大潜力。这些特性使得ReSearch不仅能够提升现有模型的性能，还为未来的多跳问答研究提供了新的方向。




## 四、总结

ReSearch通过将搜索操作与推理链相结合，利用强化学习（Reinforcement Learning, RL）训练大语言模型（Large Language Models, LLMs），在无需标注推理步骤的情况下显著提升了模型的推理能力。实验证明，ReSearch在多跳问答任务中表现优异，相较于现有方法，其准确率提升了8.9%到22.4%。这一框架不仅展现了强大的泛化能力，还能在训练过程中自然激发模型的自我反思和修正能力。

ReSearch的核心创新在于将搜索操作视为推理链的组成部分。模型通过文本思考决定何时以及如何进行搜索，而搜索结果则进一步影响后续的推理过程。这种设计使得模型能够自主地分解复杂问题，并通过多次检索获取必要的信息，最终生成准确的答案。例如，在回答“2018年墨西哥总统选举的获胜者是谁？”时，模型首先通过搜索确定相关政治人物及其所属国家，随后进一步检索选举结果，最终给出正确答案。

此外，ReSearch的训练过程完全基于强化学习，无需任何标注的推理步骤数据。通过简单的奖励信号（如答案正确性和格式规范性），模型能够逐步学习如何有效地结合推理与搜索。这种训练方式不仅降低了数据标注的成本，还使得模型能够适应更复杂的现实场景。

未来，ReSearch框架可以进一步扩展到更多领域和工具中，例如结合知识图谱或专业数据库，以增强模型在特定领域的推理能力。此外，探索如何将ReSearch与其他强化学习算法结合，或引入更复杂的奖励机制，也是值得研究的方向。总之，ReSearch为开发更强大、更可靠的大语言模型系统提供了新的思路，具有广泛的应用前景。



<hr />

- 论文原文: [https://arxiv.org/abs/2503.19470](https://arxiv.org/abs/2503.19470)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)