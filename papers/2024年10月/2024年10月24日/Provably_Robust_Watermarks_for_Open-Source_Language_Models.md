# 开源语言模型的可证明鲁棒水印

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了在开源大型语言模型（LLM）中嵌入水印的技术，这是一种具体的应用场景。论文提出了一个新的水印方案，并展示了其在特定条件下的不可移除性和鲁棒性。这属于LLM在实际应用中的技术改进和安全性增强，因此归类为LLM应用。` `人工智能` `信息安全`

> Provably Robust Watermarks for Open-Source Language Models

# 摘要

> 随着高质量语言模型的迅猛发展，识别AI生成文本的新方法变得至关重要。水印技术作为领先的解决方案，有望成为生成式AI时代的关键工具。现有方法在推理阶段嵌入水印，并依赖于LLM的规格和参数保密，因此不适用于开源场景。我们提出了首个适用于开源LLM的水印方案，通过修改模型参数实现水印嵌入，且仅需模型输出即可检测水印。令人惊讶的是，我们证明了在特定对手知识假设下，水印不可移除。通过OPT-6.7B和OPT-1.3B的实验，我们展示了方案对令牌替换和参数扰动的鲁棒性。实验表明，模型扰动攻击需将质量分数降至0（满分100）才能将检测率降至50%。

> The recent explosion of high-quality language models has necessitated new methods for identifying AI-generated text. Watermarking is a leading solution and could prove to be an essential tool in the age of generative AI. Existing approaches embed watermarks at inference and crucially rely on the large language model (LLM) specification and parameters being secret, which makes them inapplicable to the open-source setting. In this work, we introduce the first watermarking scheme for open-source LLMs. Our scheme works by modifying the parameters of the model, but the watermark can be detected from just the outputs of the model. Perhaps surprisingly, we prove that our watermarks are unremovable under certain assumptions about the adversary's knowledge. To demonstrate the behavior of our construction under concrete parameter instantiations, we present experimental results with OPT-6.7B and OPT-1.3B. We demonstrate robustness to both token substitution and perturbation of the model parameters. We find that the stronger of these attacks, the model-perturbation attack, requires deteriorating the quality score to 0 out of 100 in order to bring the detection rate down to 50%.

[Arxiv](https://arxiv.org/abs/2410.18861)