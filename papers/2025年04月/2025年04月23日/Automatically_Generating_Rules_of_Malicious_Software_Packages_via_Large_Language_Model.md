# 基于大型语言模型的恶意软件规则自动生成方法

发布时间：2025年04月23日

`LLM应用

摘要中提到，RuleLLM利用大语言模型自动生成安全规则，应用于开源软件生态系统。这属于将LLM应用于安全工具的自动化，因此归类为LLM应用。` `软件供应链安全` `开源软件`

> Automatically Generating Rules of Malicious Software Packages via Large Language Model

# 摘要

> 当前的安全工具主要依赖于专家编写的规则，难以应对软件供应链攻击的挑战。为解决这一问题，我们提出了 RuleLLM，它利用大语言模型 (LLMs) 自动为开源软件 (OSS) 生态系统生成安全规则。该工具通过分析恶意软件的元数据和代码片段，生成可用于软件开发的 YARA 和 Semgrep 规则。具体而言，规则生成分为三个步骤：创建、优化和对齐。我们通过实验验证了 RuleLLM 的效果，在包含 1,633 个恶意包的数据集上，生成了 763 条规则（452 条 YARA 和 311 条 Semgrep），准确率为 85.2%，召回率为 91.8%，优于现有工具。此外，我们还提出了一个包含 11 个类别和 38 个子类别的规则分类法。

> Today's security tools predominantly rely on predefined rules crafted by experts, making them poorly adapted to the emergence of software supply chain attacks. To tackle this limitation, we propose a novel tool, RuleLLM, which leverages large language models (LLMs) to automate rule generation for OSS ecosystems. RuleLLM extracts metadata and code snippets from malware as its input, producing YARA and Semgrep rules that can be directly deployed in software development. Specifically, the rule generation task involves three subtasks: crafting rules, refining rules, and aligning rules. To validate RuleLLM's effectiveness, we implemented a prototype system and conducted experiments on the dataset of 1,633 malicious packages. The results are promising that RuleLLM generated 763 rules (452 YARA and 311 Semgrep) with a precision of 85.2\% and a recall of 91.8\%, outperforming state-of-the-art (SOTA) tools and scored-based approaches. We further analyzed generated rules and proposed a rule taxonomy: 11 categories and 38 subcategories.

[Arxiv](https://arxiv.org/abs/2504.17198)