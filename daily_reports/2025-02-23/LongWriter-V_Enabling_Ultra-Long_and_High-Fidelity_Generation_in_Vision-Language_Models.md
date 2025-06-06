# LongWriter-V：助力视觉语言模型实现超长且高保真内容生成
发布时间：2025年02月20日


> LongWriter-V: Enabling Ultra-Long and High-Fidelity Generation in Vision-Language Models
>
> 现有大视觉-语言模型（LVLMs）虽能处理上下文长度达128k视觉和文本令牌的输入，但难以生成超过1,000字的连贯输出。究其原因，主要是在有监督微调（SFT）过程中缺乏长输出示例。为此，我们推出了LongWriter-V-22k，这是一个包含22,158个示例的SFT数据集，每个示例包括多个输入图像、一个指令以及长度从0到10,000字的输出。为了实现与输入图像高度一致的长输出，我们采用了直接偏好优化（DPO）对SFT模型进行优化。鉴于收集长输出（如3,000字）的人类反馈成本高昂，我们提出了IterDPO，该方法通过迭代修正将长输出分割为多个段落，并与原始输出形成偏好对。此外，我们开发了MMLongBench-Write，这是一个包含六个任务的基准测试，用于评估视觉-语言模型的长生成能力。我们使用LongWriter-V-22k和IterDPO训练的7B参数模型，在此基准测试中表现优异，超越了更大规模的专有模型如GPT-4o。代码和数据：https://github.com/THU-KEG/LongWriter-V
>
> https://arxiv.org/abs/2502.14834

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.14834](https://arxiv.org/abs/2502.14834)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)