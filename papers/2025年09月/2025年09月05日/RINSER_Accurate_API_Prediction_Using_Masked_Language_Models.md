# RINSER：基于掩码语言模型的准确API预测

发布时间：2025年09月05日

`LLM应用` `基础理论`

> RINSER: Accurate API Prediction Using Masked Language Models

# 摘要

> 恶意软件作者常通过混淆在二进制文件中隐藏API标识，导致人类专家分析程序行为和意图时既困难又耗时。因此，自动API预测工具成为高效分析未知二进制文件的关键——它们能加速恶意软件分类，同时减轻人工分析师的负担。本文提出了RINSER（基于掩码语言模型学习的精确API预测）——一个用于预测Windows API（WinAPI）函数名的自动化框架。RINSER创新性地提出了“API代码指纹”概念（即一组与API相关的汇编指令），并支持x86 PE二进制文件。该框架基于BERT的掩码语言模型（LM）实现API名称的大规模预测：在普通二进制文件上准确率达85.77%，在剥离符号的二进制文件上仍有82.88%。我们在一个大型数据集上对RINSER进行了评估：该数据集包含来自11,098个恶意软件二进制文件的470万个API代码指纹，涵盖4,123个独特的Windows API，是目前此类最大的公开数据集。值得注意的是，RINSER在数据集中成功识别出65个与C2通信、间谍活动及规避相关的混淆Windows API，而商业反汇编工具IDA对此完全无能为力。此外，通过与三种最先进方法的对比，RINSER的预测准确率高出20%以上；我们还验证了其对对抗性攻击的强韧性——即便面对指令随机化和代码位移攻击，性能下降也不超过3%。

> Malware authors commonly use obfuscation to hide API identities in binary files, making analysis difficult and time-consuming for a human expert to understand the behavior and intent of the program. Automatic API prediction tools are necessary to efficiently analyze unknown binaries, facilitating rapid malware triage while reducing the workload on human analysts. In this paper, we present RINSER (AccuRate API predictioN using maSked languagE model leaRning), an automated framework for predicting Windows API (WinAPI) function names. RINSER introduces the novel concept of API codeprints, a set of API-relevant assembly instructions, and supports x86 PE binaries. RINSER relies on BERT's masked language model (LM) to predict API names at scale, achieving 85.77% accuracy for normal binaries and 82.88% accuracy for stripped binaries. We evaluate RINSER on a large dataset of 4.7M API codeprints from 11,098 malware binaries, covering 4,123 unique Windows APIs, making it the largest publicly available dataset of this type. RINSER successfully discovered 65 obfuscated Windows APIs related to C2 communication, spying, and evasion in our dataset, which the commercial disassembler IDA failed to identify. Furthermore, we compared RINSER against three state-of-the-art approaches, showing over 20% higher prediction accuracy. We also demonstrated RINSER's resilience to adversarial attacks, including instruction randomization and code displacement, with a performance drop of no more than 3%.

[Arxiv](https://arxiv.org/abs/2509.04887)