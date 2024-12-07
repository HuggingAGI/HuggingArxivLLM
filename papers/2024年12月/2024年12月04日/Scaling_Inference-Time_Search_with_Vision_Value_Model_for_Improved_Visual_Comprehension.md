# 借助视觉价值模型拓展推理时间搜索，以增强视觉理解

发布时间：2024年12月04日

`LLM应用` `视觉语言模型` `多模态`

> Scaling Inference-Time Search with Vision Value Model for Improved Visual Comprehension

# 摘要

> 尽管视觉语言模型（VLMs）取得了重大进展，但在通过增加推理时间计算来提升响应质量方面，仍缺少有效的办法。在近期大型语言模型的研究中，此能力被视为迈向自我改进模型的关键一步。在本文中，我们推出了视觉价值模型（VisVM），它能够引导 VLM 在推理时间进行搜索，从而生成具有更优视觉理解的响应。具体来说，VisVM 不但评估当前搜索步骤中生成的句子质量，还能预测当前步骤可能产生的后续句子的质量，进而提供长期价值。如此一来，VisVM 让 VLMs 避免生成易产生幻觉或细节不足的句子，进而生成更高质量的响应。实验结果显示，与贪婪解码和采用其他视觉奖励信号的搜索方法相比，VisVM 引导的搜索显著增强了 VLMs 生成具有更丰富视觉细节和更少幻觉的描述性标题的能力。此外，我们发现用 VisVM 引导的标题对模型进行自训练能够提升 VLM 在众多多模态基准测试中的表现，这表明了开发自我改进的 VLMs 的潜力。我们的价值模型和代码可在 https://github.com/si0wang/VisVM 获取。

> Despite significant advancements in vision-language models (VLMs), there lacks effective approaches to enhance response quality by scaling inference-time computation. This capability is known to be a core step towards the self-improving models in recent large language model studies. In this paper, we present Vision Value Model (VisVM) that can guide VLM inference-time search to generate responses with better visual comprehension. Specifically, VisVM not only evaluates the generated sentence quality in the current search step, but also anticipates the quality of subsequent sentences that may result from the current step, thus providing a long-term value. In this way, VisVM steers VLMs away from generating sentences prone to hallucinations or insufficient detail, thereby producing higher quality responses. Experimental results demonstrate that VisVM-guided search significantly enhances VLMs' ability to generate descriptive captions with richer visual details and fewer hallucinations, compared with greedy decoding and search methods with other visual reward signals. Furthermore, we find that self-training the model with the VisVM-guided captions improve VLM's performance across a wide range of multimodal benchmarks, indicating the potential for developing self-improving VLMs. Our value model and code are available at https://github.com/si0wang/VisVM.

[Arxiv](https://arxiv.org/abs/2412.03704)