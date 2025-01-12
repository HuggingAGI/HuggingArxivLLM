# RARe：具有上下文示例的检索增强式检索
发布时间：2024年10月26日


> RARe: Retrieval Augmented Retrieval with In-Context Examples
>
> 我们探究在仅解码器语言模型（LLMs）中被广泛运用的上下文示例，能否提升检索任务中嵌入模型的性能。和在 LLMs 中的情况不同，在推理时直接把上下文示例（查询 - 文档对）添加到目标查询前，无法直接生效。我们提出了一种简便的方法，让检索器能够运用上下文示例。我们的方法 RARe，用与目标查询语义相近的上下文示例对预训练模型进行微调。这能应用于适配各种基础架构（比如仅解码器语言模型、检索器模型），在各种开放域检索数据集（BeIR、RAR-b）中持续实现高达 +2.72％ nDCG 的性能增益。特别是，我们发现相较于使用不含上下文示例查询的模型，RARe 展现出更强的域外泛化能力，这和 LLMs 中的上下文学习相似。我们进一步对上下文示例扩充的设计选择加以分析，为该领域的未来工作筑牢根基。
>
> https://arxiv.org/abs/2410.20088

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2410.20088](https://arxiv.org/abs/2410.20088)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)