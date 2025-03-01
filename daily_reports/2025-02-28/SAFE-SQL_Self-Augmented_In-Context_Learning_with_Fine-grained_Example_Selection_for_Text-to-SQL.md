# SAFE-SQL: 基于自增强上下文学习与细粒度示例选择的文本到SQL转换方法
发布时间：2025年02月16日

`代码编写`
> SAFE-SQL: Self-Augmented In-Context Learning with Fine-grained Example Selection for Text-to-SQL
>
> Text-to-SQL旨在将自然语言问题转换为可执行的SQL查询。虽然之前的方法，如骨架掩码选择，通过检索相似的训练示例来引导大型语言模型（LLMs）表现出强大的性能，但在现实场景中，当缺乏这些示例时，它们往往表现不佳。为了解决这一问题，我们提出了SAFE-SQL框架，它通过生成和筛选自增广示例来提升SQL生成效果。SAFE-SQL首先提示一个LLM生成多个与测试输入相关的Text-to-SQL示例，然后通过三个相关性评估筛选这些示例，构建高质量的上下文学习示例。利用自生成的示例，SAFE-SQL不仅超越了之前的零样本和少样本Text-to-SQL框架，还实现了更高的执行准确性。特别地，我们的方法在额外困难和未见场景中表现更优，而传统方法往往在此类场景中失效。
>
> https://arxiv.org/abs/2502.11438

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.11438](https://arxiv.org/abs/2502.11438)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)