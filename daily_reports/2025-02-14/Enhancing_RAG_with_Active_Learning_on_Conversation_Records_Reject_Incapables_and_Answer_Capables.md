# 利用主动学习对话记录提升 RAG：筛选无能者，精准解答有能力者
发布时间：2025年02月13日

`RAG`
> Enhancing RAG with Active Learning on Conversation Records: Reject Incapables and Answer Capables
>
> 检索增强生成（RAG）是大型语言模型（LLMs）利用外部知识并减少幻觉的关键技术。然而，RAG仍然难以完全防止幻觉响应。为了解决这一问题，至关重要的是要识别容易产生幻觉的样本或引导LLMs给出正确回答，然后由专家标注这些样本以开发高质量的数据集，用于精调LLMs。然而，这类数据集日益稀缺，使其创建变得困难。本文提出利用广泛使用LLMs所产生的大量对话，构建这些数据集，训练LLMs以避免容易引发幻觉的问题，同时准确回答可管理的问题。鉴于专家标注所有对话记录不切实际，本文引入AL4RAG，利用主动学习选择最适合标注的对话样本，在标注预算内优化性能。此外，鉴于传统主动学习方法由于不合适的距离度量而与RAG不完全兼容，我们为RAG主动学习开发了一种新的样本距离测量方法。大量实验表明，我们的方法在多个指标上始终优于基线方法。
>
> https://arxiv.org/abs/2502.09073

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.09073](https://arxiv.org/abs/2502.09073)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)