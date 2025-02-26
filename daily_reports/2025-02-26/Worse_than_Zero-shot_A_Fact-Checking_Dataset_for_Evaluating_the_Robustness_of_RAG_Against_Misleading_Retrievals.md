# 比零-shot更糟糕？用于评估RAG在误导性检索下鲁棒性的事实核查数据集
发布时间：2025年02月22日

`RAG`
> Worse than Zero-shot? A Fact-Checking Dataset for Evaluating the Robustness of RAG Against Misleading Retrievals
>
> 检索增强生成（RAG）在缓解大型语言模型（LLMs）幻觉问题上表现突出，但LLMs在处理误导性检索时仍存在明显短板。尤其是在面对矛盾或有选择性框架的证据时，LLMs往往难以保持自身推理能力，容易受到现实世界中错误信息的干扰。在现实世界中，误导性和矛盾性信息泛滥，尤其是在政治领域，证据常被有选择性地构建、不完整或带有明显倾向性。然而，现有RAG基准测试大多基于理想化的"干净"检索环境，模型只需从高质量文档中准确检索并生成答案即可成功。这种假设与现实条件严重脱节，导致对RAG系统性能的过高评估。为解决这一问题，我们推出RAGuard——首个专注于评估RAG系统在误导性检索环境下稳健性的事实核查数据集。与以往依赖合成噪声的基准测试不同，RAGuard从Reddit讨论中获取真实数据，捕捉自然发生的错误信息。它将检索证据分为支持性、误导性和不相关性三类，为评估RAG系统应对复杂检索信息的能力提供了现实且具有挑战性的测试环境。实验结果表明，面对误导性检索时，所有基于LLM的RAG系统的表现均劣于零-shot基线（即完全不进行检索），凸显了其在噪声环境中的脆弱性。我们相信，RAGuard将推动未来研究，使RAG系统在理想化数据集之外得到改进，从而在现实应用中更加可靠。
>
> https://arxiv.org/abs/2502.16101

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.16101](https://arxiv.org/abs/2502.16101)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)