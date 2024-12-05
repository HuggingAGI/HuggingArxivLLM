# CredID：用于大型语言模型识别的可信多位水印

发布时间：2024年12月04日

`LLM应用` `隐私安全`

> CredID: Credible Multi-Bit Watermark for Large Language Models Identification

# 摘要

> 大型语言模型（LLMs）在复杂的自然语言处理任务中应用广泛，然而因缺乏身份识别，引发了隐私与安全方面的忧虑。为此，本文提出了一个包含可信第三方（TTP）和多个LLM供应商的多方可信水印框架（CredID）来应对这些问题。在水印嵌入环节，供应商向TTP索要种子来生成水印文本，且无需发送用户的提示。在提取阶段，TTP协调各供应商从文本中提取并验证水印。这既提供了可信的水印方案，又保护了供应商的隐私。另外，当下的水印算法在文本质量、信息容量和稳健性上存在难题，难以满足LLMs的多元识别需求。所以，我们提出了一种新颖的多比特水印算法和一个开源工具包来助力研究。实验表明，我们的CredID在不损害文本质量的前提下，提升了水印的可信度和效率。而且，我们成功运用此框架在多个LLM供应商中达成了高精度的识别。

> Large Language Models (LLMs) are widely used in complex natural language processing tasks but raise privacy and security concerns due to the lack of identity recognition. This paper proposes a multi-party credible watermarking framework (CredID) involving a trusted third party (TTP) and multiple LLM vendors to address these issues. In the watermark embedding stage, vendors request a seed from the TTP to generate watermarked text without sending the user's prompt. In the extraction stage, the TTP coordinates each vendor to extract and verify the watermark from the text. This provides a credible watermarking scheme while preserving vendor privacy. Furthermore, current watermarking algorithms struggle with text quality, information capacity, and robustness, making it challenging to meet the diverse identification needs of LLMs. Thus, we propose a novel multi-bit watermarking algorithm and an open-source toolkit to facilitate research. Experiments show our CredID enhances watermark credibility and efficiency without compromising text quality. Additionally, we successfully utilized this framework to achieve highly accurate identification among multiple LLM vendors.

[Arxiv](https://arxiv.org/abs/2412.03107)