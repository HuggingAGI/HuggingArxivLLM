# LLMs 能否混淆代码？关于大型语言模型在汇编代码混淆方面的系统分析

发布时间：2024年12月20日

`LLM应用` `网络安全` `软件开发`

> Can LLMs Obfuscate Code? A Systematic Analysis of Large Language Models into Assembly Code Obfuscation

# 摘要

> 恶意软件的作者常常运用代码混淆手段，让其恶意软件更难以被检测出来。现有的生成混淆代码的工具往往需要获取原始源代码（比如 C++ 或 Java 代码），而且增添新的混淆方式是个不简单、耗费人力的过程。在本次研究中，我们提出了这样一个问题：大型语言模型（LLMs）有没有可能生成新的混淆汇编代码？倘若如此，这会给反病毒引擎带来风险，还可能增强攻击者创建新混淆模式的灵活性。我们通过开发包含 MetamorphASM 数据集（MAD）以及三种代码混淆技术（死代码、寄存器替换和控制流变更）的 MetamorphASM 基准，给出了肯定的答案。MetamorphASM 借助包含 328,200 个混淆汇编代码样本的 MAD，对 LLMs 生成和分析混淆代码的能力进行了系统性评估。我们发布了此数据集，并分析了各类 LLMs（如 GPT-3.5/4、GPT-4o-mini、Starcoder、CodeGemma、CodeLlama、CodeT5 和 LLaMA 3.1）生成混淆汇编代码的成功率。评估采用了已有的信息理论指标和人工审查，以确保正确性，并为研究人员研究和开发应对此风险的措施奠定基础。源代码可在以下 GitHub 链接获取：https://github.com/mohammadi-ali/MetamorphASM。

> Malware authors often employ code obfuscations to make their malware harder to detect. Existing tools for generating obfuscated code often require access to the original source code (e.g., C++ or Java), and adding new obfuscations is a non-trivial, labor-intensive process. In this study, we ask the following question: Can Large Language Models (LLMs) potentially generate a new obfuscated assembly code? If so, this poses a risk to anti-virus engines and potentially increases the flexibility of attackers to create new obfuscation patterns. We answer this in the affirmative by developing the MetamorphASM benchmark comprising MetamorphASM Dataset (MAD) along with three code obfuscation techniques: dead code, register substitution, and control flow change. The MetamorphASM systematically evaluates the ability of LLMs to generate and analyze obfuscated code using MAD, which contains 328,200 obfuscated assembly code samples. We release this dataset and analyze the success rate of various LLMs (e.g., GPT-3.5/4, GPT-4o-mini, Starcoder, CodeGemma, CodeLlama, CodeT5, and LLaMA 3.1) in generating obfuscated assembly code. The evaluation was performed using established information-theoretic metrics and manual human review to ensure correctness and provide the foundation for researchers to study and develop remediations to this risk. The source code can be found at the following GitHub link: https://github.com/mohammadi-ali/MetamorphASM.

[Arxiv](https://arxiv.org/abs/2412.16135)