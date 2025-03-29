# # Qwen2.5-Omni 技术报告
发布时间：2025年03月26日


> Qwen2.5-Omni Technical Report
>
> 本报告中，我们推出 Qwen2.5-Omni——一款端到端多模态模型，它能够感知文本、图像、音频和视频等多种信息形式，并以流式方式同步生成文本和自然语音。为了实现多模态信息的流式输入处理，音频和视觉编码器均采用基于块的处理方式。为确保视频与音频的时间同步，我们创新性地将音频和视频按顺序交错组织，并提出了名为 TMRoPE（时间对齐的多模态 RoPE）的新位置嵌入方法。针对文本与语音的并发生成需求，我们设计了	extbf{Thinker-Talker}架构：其中，Thinker 作为负责文本生成的大语言模型，而 Talker 则是双轨自回归模型，直接利用 Thinker 的隐藏表示生成音频令牌输出。Thinker 和 Talker 均支持端到端训练与推理。在音频令牌流式解码方面，我们引入滑动窗口 DiT，通过限制感受野来减少初始延迟。Qwen2.5-Omni 在性能上与同规模的 Qwen2.5-VL 相当，超越 Qwen2-Audio。在 Omni-Bench 等多模态基准测试中，它达到了当前最优水平。值得注意的是，Qwen2.5-Omni 在端到端语音指令遵循任务中的表现与文本输入处理能力相当，这一结论在 MMLU 和 GSM8K 等基准测试中得到验证。在语音生成方面，Qwen2.5-Omni 的流式 Talker 在鲁棒性和自然度上优于现有大多数流式与非流式方案。
>
> https://arxiv.org/abs/2503.20215

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.20215](https://arxiv.org/abs/2503.20215)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)