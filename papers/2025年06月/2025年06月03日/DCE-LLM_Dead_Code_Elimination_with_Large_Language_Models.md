# DCE-LLM：基于大型语言模型的死代码消除

发布时间：2025年06月03日

`LLM应用

理由：这篇论文主要探讨了如何利用基于LLM的方法来解决软件开发中的死代码问题，属于将LLM技术应用于实际问题的范畴。` `软件工程` `软件开发工具`

> DCE-LLM: Dead Code Elimination with Large Language Models

# 摘要

> 死代码在软件开发中带来多重挑战，如增大二进制文件体积、增加维护难度，还可能掩盖逻辑错误或被用于恶意软件混淆。对于基于LLM的代码任务，死代码会引入漏洞，误导模型，引发安全问题。现代编译器和IDE虽提供死代码消除功能，但复杂模式仍可能绕过这些工具。我们亟需一种包含分类、定位、解释和修复的通用方法，但现有工具往往需要大量手动操作。

为此，我们推出DCE-LLM——一个基于小型CodeBERT模型的自动化死代码消除框架。通过结合基于归属度的行选择器，DCE-LLM能高效定位可疑代码。LLMs在大规模标注死代码数据集上微调后，可生成判断、提供详细解释并自动生成修复补丁。DCE-LLM凭借其高级不可达性检测、自动化修复能力和多语言支持，显著超越现有工具。实验数据显示，DCE-LLM在未使用和不可达代码检测上的F1分数超过94%，远超GPT-4o 30%。


> Dead code introduces several challenges in software development, such as increased binary size and maintenance difficulties. It can also obscure logical errors and be exploited for obfuscation in malware. For LLM-based code-related tasks, dead code introduces vulnerabilities that can mislead these models, raising security concerns. Although modern compilers and IDEs offer dead code elimination, sophisticated patterns can bypass these tools. A universal approach that includes classification, location, explanation, and correction is needed, yet current tools often require significant manual effort. We present DCE-LLM, a framework for automated dead code elimination using a small CodeBERT model with an attribution-based line selector to efficiently locate suspect code. LLMs then generate judgments and explanations, fine-tuned on a large-scale, annotated dead code dataset to provide detailed explanations and patches. DCE-LLM outperforms existing tools, with advanced unreachability detection, automated correction, and support for multiple programming languages. Experimental results show DCE-LLM achieves over 94% F1 scores for unused and unreachable code, significantly surpassing GPT-4o by 30%.

[Arxiv](https://arxiv.org/abs/2506.11076)