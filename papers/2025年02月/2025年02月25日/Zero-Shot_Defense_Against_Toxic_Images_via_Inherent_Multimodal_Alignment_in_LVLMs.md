# 零样本防御有毒图像：大语言模型中固有的多模态对齐

发布时间：2025年02月25日

`LLM应用` `计算机视觉`

> Zero-Shot Defense Against Toxic Images via Inherent Multimodal Alignment in LVLMs

# 摘要

> 大型视觉-语言模型（LVLMs）在多模态理解方面取得了显著进展，这得益于它们在大规模视觉数据集上的广泛预训练和微调。然而，尽管它们拥有强大的文本安全机制，但仍然容易受到有害视觉输入的攻击。现有的安全措施通常依赖于预过滤或微调，这会导致高昂的成本并降低整体实用性。为了解决这一关键漏洞，我们引入了SafeCLIP，这是一种轻量级方法，它利用LVLM固有的多模态对齐能力来实现零样本有害图像检测。通过将CLIP丢弃的CLS令牌投影到其文本空间并与有害描述符进行匹配，SafeCLIP无需任何架构修改即可检测有害内容，仅增加极小的延迟，并在推理和微调过程中支持动态安全校正。实验表明，SafeCLIP仅需3.2%的误报率和7.2%的开销，就能实现66.9%的防御成功率。相比之下，现有最优方法仅达到52.9%的成功率，但误报率为10.7%，开销高达210%。我们的研究表明，利用固有的多模态对齐能力可以实现高效且低成本的LVLM安全性。代码可在anonymous.4open.science/r/safeclip-2C01获取。

> Large Vision-Language Models (LVLMs) have made significant strides in multimodal comprehension, thanks to extensive pre-training and fine-tuning on large-scale visual datasets. However, despite their robust textual safety mechanisms, they remain vulnerable to harmful visual inputs. Existing safeguards-typically relying on pre-filtering or fine-tuning-incur high costs and diminish overall utility. To address this critical vulnerability, we introduce SafeCLIP, a lightweight method that leverages LVLMs inherent multimodal alignment for zero-shot toxic image detection. By projecting CLIPs discarded CLS token into its text space and matching it with toxic descriptors, SafeCLIP detects harmful content without any architectural changes-adding minimal latency and enabling dynamic safety corrections during inference and fine-tuning.Experiments show that SafeCLIP achieves a 66.9% defense success rate with only 3.2% false positive rate and 7.2% overhead. In contrast, state-of-the-art methods achieve 52.9% success but have a 10.7% false positive rate and 210% overhead. Our work demonstrates that leveraging inherent multimodal alignment can yield efficient, low-cost LVLM safety. Code is available at anonymous.4open.science/r/safeclip-2C01.

[Arxiv](https://arxiv.org/abs/2503.00037)