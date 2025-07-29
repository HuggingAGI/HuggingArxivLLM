# 揭秘大型语言扩散模型的安全隐患：揭示扩散文本生成中的潜在风险

发布时间：2025年07月25日

`LLM理论

论文摘要：大语言扩散模型（LLDMs）不仅性能媲美大型语言模型（LLMs），还在推理速度和数学推理任务中展现出独特优势。然而，LLDMs的精准快速生成能力也带来了对有害内容生成的担忧。现有针对LLMs的越狱方法在LLDMs上效果有限，未能有效揭示其安全漏洞。尽管防御措施可以一定程度上缓解问题，但LLDMs的安全稳健性及现有攻击方法的兼容性仍存疑。为此，我们深入研究了LLDMs的脆弱性，揭示了其在越狱攻击中失败的根本原因——架构差异。我们提出了一种针对扩散语言模型的并行解码越狱方法（PAD）。PAD通过多点注意力攻击，引导生成过程趋向有害输出，灵感源于LLMs中的肯定响应模式。实验结果表明，PAD在四种LLDM上实现了高达97%的越狱成功率，揭示了显著的安全漏洞。此外，与相同规模的自回归LLMs相比，LLDMs将有害生成速度提升了2倍，凸显了其滥用风险。通过全面分析，我们深入研究了LLDM架构，为扩散语言模型的安全部署提供了关键见解。` `计算机安全` `人工智能伦理`

> Jailbreaking Large Language Diffusion Models: Revealing Hidden Safety Flaws in Diffusion-Based Text Generation

# 摘要

> 大语言扩散模型（LLDMs）不仅性能媲美大型语言模型（LLMs），还在推理速度和数学推理任务中展现出独特优势。然而，LLDMs的精准快速生成能力也带来了对有害内容生成的担忧。现有针对LLMs的越狱方法在LLDMs上效果有限，未能有效揭示其安全漏洞。尽管防御措施可以一定程度上缓解问题，但LLDMs的安全稳健性及现有攻击方法的兼容性仍存疑。为此，我们深入研究了LLDMs的脆弱性，揭示了其在越狱攻击中失败的根本原因——架构差异。我们提出了一种针对扩散语言模型的并行解码越狱方法（PAD）。PAD通过多点注意力攻击，引导生成过程趋向有害输出，灵感源于LLMs中的肯定响应模式。实验结果表明，PAD在四种LLDM上实现了高达97%的越狱成功率，揭示了显著的安全漏洞。此外，与相同规模的自回归LLMs相比，LLDMs将有害生成速度提升了2倍，凸显了其滥用风险。通过全面分析，我们深入研究了LLDM架构，为扩散语言模型的安全部署提供了关键见解。

> Large Language Diffusion Models (LLDMs) exhibit comparable performance to LLMs while offering distinct advantages in inference speed and mathematical reasoning tasks.The precise and rapid generation capabilities of LLDMs amplify concerns of harmful generations, while existing jailbreak methodologies designed for Large Language Models (LLMs) prove limited effectiveness against LLDMs and fail to expose safety vulnerabilities.Successful defense cannot definitively resolve harmful generation concerns, as it remains unclear whether LLDMs possess safety robustness or existing attacks are incompatible with diffusion-based architectures.To address this, we first reveal the vulnerability of LLDMs to jailbreak and demonstrate that attack failure in LLDMs stems from fundamental architectural differences.We present a PArallel Decoding jailbreak (PAD) for diffusion-based language models. PAD introduces Multi-Point Attention Attack, which guides parallel generative processes toward harmful outputs that inspired by affirmative response patterns in LLMs. Experimental evaluations across four LLDMs demonstrate that PAD achieves jailbreak attack success rates by 97%, revealing significant safety vulnerabilities. Furthermore, compared to autoregressive LLMs of the same size, LLDMs increase the harmful generation speed by 2x, significantly highlighting risks of uncontrolled misuse.Through comprehensive analysis, we provide an investigation into LLDM architecture, offering critical insights for the secure deployment of diffusion-based language models.

[Arxiv](https://arxiv.org/abs/2507.19227)