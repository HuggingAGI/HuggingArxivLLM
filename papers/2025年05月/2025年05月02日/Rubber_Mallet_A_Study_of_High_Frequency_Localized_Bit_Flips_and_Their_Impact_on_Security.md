# 橡胶锤：高频局部比特翻转及其对安全的影响研究

发布时间：2025年05月02日

`其他

理由：这篇论文主要探讨了Rowhammer攻击对DRAM的影响以及如何利用这种攻击来绕过安全措施，特别是针对大型语言模型的定向攻击。虽然提到了大型语言模型，但论文的核心内容是关于硬件安全和攻击技术，因此更符合“其他”分类。` `计算机硬件` `网络安全`

> Rubber Mallet: A Study of High Frequency Localized Bit Flips and Their Impact on Security

# 摘要

> 现代DRAM密度的提升使其更容易受到Rowhammer攻击的影响，这种攻击通过反复访问特定内存行来引发比特翻转。本文分析了先进Rowhammer技术绕过现有硬件防御所生成的比特翻转模式。首先，我们研究了相邻比特翻转现象——即两个或多个物理相邻的比特同时被破坏——并证明其发生的频率显著高于先前记录。我们还发现，如果一个字节内有多个比特翻转，它们更可能是相邻的而非随机分布的：例如，如果一个字节内有4个比特翻转，那么它们全部相邻的概率高达87%。此外，我们展示了同一行内的比特翻转会自然聚集在一起，这可能是由于攻击的物理基础所致。接下来，我们研究了由多个相邻或邻近比特翻转启用的两种故障注入攻击。首先，我们展示了这些相关翻转如何支持高效的密码签名修复攻击，成功从OpenSSL实现中恢复ECDSA私钥，而单比特方法则无法实现。其次，我们介绍了一种针对大型语言模型的定向攻击，利用Rowhammer引发的GGUF模型文件中分词器字典的损坏。该攻击通过将关键安全令牌替换为无害的替代品，有效重写系统提示中的安全指令，绕过模型护栏，同时在其他上下文中保持正常功能。我们跨多个DRAM配置的实验结果表明，当前的内存保护方案不足以抵御这些复杂的攻击向量，这些攻击可以通过精确、最小的修改而非随机破坏来实现其目标。

> The increasing density of modern DRAM has heightened its vulnerability to Rowhammer attacks, which induce bit flips by repeatedly accessing specific memory rows. This paper presents an analysis of bit flip patterns generated by advanced Rowhammer techniques that bypass existing hardware defenses. First, we investigate the phenomenon of adjacent bit flips--where two or more physically neighboring bits are corrupted simultaneously--and demonstrate they occur with significantly higher frequency than previously documented. We also show that if multiple bits flip within a byte, they are more likely to be adjacent than randomly distributed: for example, if 4 bits flip within a byte, there is an 87% chance that they are all adjacent. We also demonstrate that bit flips within a row will naturally cluster together likely due to the underlying physics of the attack. We then investigate two fault injection attacks enabled by multiple adjacent or nearby bit flips. First, we show how these correlated flips enable efficient cryptographic signature correction attacks, successfully recovering ECDSA private keys from OpenSSL implementations where single-bit approaches would be unfeasible. Second, we introduce a targeted attack against large language models by exploiting Rowhammer-induced corruptions in tokenizer dictionaries of GGUF model files. This attack effectively rewrites safety instructions in system prompts by swapping safety-critical tokens with benign alternatives, circumventing model guardrails while maintaining normal functionality in other contexts. Our experimental results across multiple DRAM configurations reveal that current memory protection schemes are inadequate against these sophisticated attack vectors, which can achieve their objectives with precise, minimal modifications rather than random corruption.

[Arxiv](https://arxiv.org/abs/2505.01518)