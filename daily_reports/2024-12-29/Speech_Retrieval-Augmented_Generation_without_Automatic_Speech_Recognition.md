# 无需自动语音识别的语音检索增强生成
发布时间：2024年12月21日

`RAG`
> Speech Retrieval-Augmented Generation without Automatic Speech Recognition
>
> 对于语音数据的问答，常见做法是先通过自动语音识别（ASR）进行语音转录，接着在转录内容上运用基于文本的检索增强生成（RAG）。尽管这种级联式流程在诸多实际场景中成效显著，但 ASR 错误可能会影响到检索和生成环节。为突破这一局限，我们推出了 SpeechRAG，这是一个专为语音数据的开放式问答打造的全新框架。我们所提出的方法是将预先训练好的语音编码器微调为一个语音适配器，输入到基于冻结的大型语言模型（LLM）的检索模型中。通过对齐文本和语音的嵌入空间，我们的语音检索器能直接依据基于文本的查询来检索音频段落，充分利用了冻结的文本检索器的检索能力。我们在语音问答数据集上的检索实验表明，直接的语音检索不逊于基于文本的基线，且优于采用 ASR 的级联系统。在生成方面，我们使用语音语言模型（SLM）作为生成器，以音频段落而非转录内容为条件。在转录存在高词错误率（WER）的情况下，即便不微调 SLM，此方法也优于基于文本的级联模型。
>
> https://arxiv.org/abs/2412.16500

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.16500](https://arxiv.org/abs/2412.16500)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)