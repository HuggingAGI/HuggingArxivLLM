# 在 confidential 计算环境中评估 DeepSeek 模型的性能表现
发布时间：2025年02月16日

`DEEPSEEK`
> Evaluating the Performance of the DeepSeek Model in Confidential Computing Environment
>
> 随着大型语言模型（LLMs）在云环境中的广泛应用，模型保密性和数据隐私等关键安全性问题日益凸显。可信计算通过可信执行环境（TEEs）提供了解决这些挑战的潜在方案。然而，现有的主要基于CPU的TEE实现难以高效支持LLM推理与训练的资源密集型特性。本研究首次对DeepSeek模型在英特尔信任域扩展（TDX）技术支持下的可信计算环境进行了性能评估。我们对DeepSeek模型在仅CPU、CPU-GPU混合以及基于TEE的三种实现方式下的表现进行了全面基准测试。研究发现，对于较小的参数集（如DeepSeek-R1-1.5B），TDX实现相较于CPU版本在安全环境下的计算性能更优。这一结果表明，在资源受限的系统中，仍有可能实现高效且安全的LLM模型部署。整体来看，GPU与CPU的性能比平均为12，且模型规模越小，该比率越低。此外，我们还为优化CPU-GPU可信计算方案提供了基础性的见解与指导，助力实现可扩展且安全的AI部署。我们的研究发现为隐私保护AI技术的发展注入了新动力，为在可信计算环境中实现高效且安全的LLM推理奠定了坚实基础。
>
> https://arxiv.org/abs/2502.11347

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.11347](https://arxiv.org/abs/2502.11347)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)