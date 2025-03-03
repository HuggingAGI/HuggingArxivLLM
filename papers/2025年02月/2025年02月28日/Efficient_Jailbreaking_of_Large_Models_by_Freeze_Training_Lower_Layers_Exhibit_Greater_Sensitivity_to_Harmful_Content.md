# 冻结训练技术实现大型模型逃逸：模型下层结构对有害内容表现出更高的敏感度

发布时间：2025年02月28日

`LLM理论` `人工智能`

> Efficient Jailbreaking of Large Models by Freeze Training: Lower Layers Exhibit Greater Sensitivity to Harmful Content

# 摘要

> 大型语言模型在广泛应用中引发了学术界和工业界对其安全问题的高度关注。本研究通过对模型参数进行采样和归一化处理，生成了参数分布的可视化热力图，发现隐藏层中某些层的参数分布存在显著差异。进一步分析显示，下层对有害内容生成尤为敏感。基于此，我们采用冻结训练策略，仅对下层进行监督微调。实验结果表明，该方法在保持高越狱成功率和危害评分的同时，显著降低了训练时间和GPU内存消耗，优于对所有层应用LoRA方法进行微调的效果。该方法已成功扩展至其他开源大模型，验证了其通用性和有效性。与其他越狱方法的对比进一步凸显了我们的方法优势。通过创新性地提出逐层统计分析大型模型参数的方法，本研究为模型可解释性提供了新视角。这些发现强调了在快速发展的大型语言模型领域中，持续研究和实施自适应安全措施的必要性，以防范潜在的越狱攻击风险，推动更 robust 和安全的大型语言模型发展。

> With the widespread application of Large Language Models across various domains, their security issues have increasingly garnered significant attention from both academic and industrial communities. This study conducts sampling and normalization of the parameters of the LLM to generate visual representations and heatmaps of parameter distributions, revealing notable discrepancies in parameter distributions among certain layers within the hidden layers. Further analysis involves calculating statistical metrics for each layer, followed by the computation of a Comprehensive Sensitivity Score based on these metrics, which identifies the lower layers as being particularly sensitive to the generation of harmful content. Based on this finding, we employ a Freeze training strategy, selectively performing Supervised Fine-Tuning only on the lower layers. Experimental results demonstrate that this method significantly reduces training duration and GPU memory consumption while maintaining a high jailbreak success rate and a high harm score, outperforming the results achieved by applying the LoRA method for SFT across all layers. Additionally, the method has been successfully extended to other open-source large models, validating its generality and effectiveness across different model architectures. Furthermore, we compare our method with ohter jailbreak method, demonstrating the superior performance of our approach. By innovatively proposing a method to statistically analyze and compare large model parameters layer by layer, this study provides new insights into the interpretability of large models. These discoveries emphasize the necessity of continuous research and the implementation of adaptive security measures in the rapidly evolving field of LLMs to prevent potential jailbreak attack risks, thereby promoting the development of more robust and secure LLMs.

[Arxiv](https://arxiv.org/abs/2502.20952)