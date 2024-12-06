# OCR 对 RAG 造成阻碍：评估 OCR 对检索增强生成的连锁影响
发布时间：2024年12月03日

`RAG`
> OCR Hinders RAG: Evaluating the Cascading Impact of OCR on Retrieval-Augmented Generation
>
> 检索增强生成（RAG）整合外部知识来强化大型语言模型（LLMs），能减少幻觉并融入最新信息，无需重新训练。作为 RAG 的关键部分，外部知识库一般通过用光学字符识别（OCR）从非结构化 PDF 文档中提取结构化数据来构建。但由于 OCR 预测不完美以及结构化数据本身的非均匀表示，知识库难免存在各种 OCR 噪声。在本文中，我们推出了 OHRBench，这是首个用于理解 OCR 对 RAG 系统级联影响的基准。OHRBench 涵盖了从六个真实 RAG 应用领域精心筛选的 350 个非结构化 PDF 文档，还有源自文档多模态元素的问答，对用于 RAG 的现有 OCR 解决方案构成挑战。为更好地理解 OCR 对 RAG 系统的影响，我们明确了两种主要的 OCR 噪声类型：语义噪声和格式噪声，并通过扰动生成一组具有不同程度每种噪声的结构化数据。借助 OHRBench，我们先是对当前的 OCR 解决方案进行了全面评估，发现没有一个能为 RAG 系统构建高质量的知识库。接着，我们系统评估了这两种噪声类型的影响，展现了 RAG 系统的脆弱性。此外，我们探讨了在 RAG 系统中使用无 OCR 的视觉语言模型（VLMs）的可能性。代码：https://github.com/opendatalab/OHR-Bench
>
> https://arxiv.org/abs/2412.02592

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.02592](https://arxiv.org/abs/2412.02592)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)