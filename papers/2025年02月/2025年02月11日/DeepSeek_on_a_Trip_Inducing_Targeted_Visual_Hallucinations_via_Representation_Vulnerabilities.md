# 深度探索：一场定向视觉幻觉的奇幻之旅——揭示表征漏洞背后的视觉魔法

发布时间：2025年02月11日

`LLM应用

论文摘要讨论了多模态大型语言模型（MLLMs）中的视觉语言融合机制的脆弱性，并提出了一种嵌入操控攻击方法，诱导视觉幻觉。这属于模型应用层面的安全问题，因此归类为LLM应用。` `人工智能安全` `开源技术`

> DeepSeek on a Trip: Inducing Targeted Visual Hallucinations via Representation Vulnerabilities

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）代表着AI技术的最前沿，其中DeepSeek模型作为开源领域的佼佼者，其性能已可与闭源系统相媲美。然而，这些模型在展现强大能力的同时，其视觉语言融合机制也带来了特定的脆弱性。我们针对DeepSeek Janus实施了一种适应性嵌入操控攻击，通过系统性优化图像嵌入，成功诱导目标视觉幻觉的产生。在COCO、DALL-E 3和SVIT数据集上的广泛实验表明，我们在开放性问题上实现了高达98.0%的幻觉率，同时保持了被操控图像的高视觉保真度（SSIM > 0.88）。分析表明，无论是1B还是7B版本的DeepSeek Janus均易受此类攻击影响，且闭合形式评估显示与开放性提问相比，幻觉率始终保持更高水平。我们引入了一种基于LLaMA-3.1 8B Instruct的新型多提示幻觉检测框架，用于稳健评估。鉴于DeepSeek的开源特性和广泛应用潜力，这些发现的潜在影响尤为令人担忧。本研究强调了在MLLM部署流水线中实施嵌入级安全措施的迫切需求，并为负责任的AI实现的更广泛讨论做出了贡献。

> Multimodal Large Language Models (MLLMs) represent the cutting edge of AI technology, with DeepSeek models emerging as a leading open-source alternative offering competitive performance to closed-source systems. While these models demonstrate remarkable capabilities, their vision-language integration mechanisms introduce specific vulnerabilities. We implement an adapted embedding manipulation attack on DeepSeek Janus that induces targeted visual hallucinations through systematic optimization of image embeddings. Through extensive experimentation across COCO, DALL-E 3, and SVIT datasets, we achieve hallucination rates of up to 98.0% while maintaining high visual fidelity (SSIM > 0.88) of the manipulated images on open-ended questions. Our analysis demonstrates that both 1B and 7B variants of DeepSeek Janus are susceptible to these attacks, with closed-form evaluation showing consistently higher hallucination rates compared to open-ended questioning. We introduce a novel multi-prompt hallucination detection framework using LLaMA-3.1 8B Instruct for robust evaluation. The implications of these findings are particularly concerning given DeepSeek's open-source nature and widespread deployment potential. This research emphasizes the critical need for embedding-level security measures in MLLM deployment pipelines and contributes to the broader discussion of responsible AI implementation.

[Arxiv](https://arxiv.org/abs/2502.07905)