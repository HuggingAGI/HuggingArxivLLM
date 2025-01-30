# ASTRAL: 大型语言模型的自动化安全测试

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要讨论了如何利用自动化工具（ASTRAL）来测试大型语言模型（LLMs）的安全性，并提出了生成和执行测试用例的方法。虽然涉及了检索增强生成（RAG）和LLM的应用，但核心内容集中在LLM的实际应用场景——安全性测试。因此，将其分类为LLM应用更为合适。` `人工智能` `安全测试`

> ASTRAL: Automated Safety Testing of Large Language Models

# 摘要

> 大型语言模型（LLMs）因其理解和生成复杂类人内容的能力而备受瞩目。然而，确保其安全性至关重要，因为它们可能产生有害或不安全的响应。现有LLM测试框架虽能应对多种安全问题（如毒品、恐怖主义、动物虐待），但因数据集不平衡和过时，常面临挑战。本文介绍了ASTRAL，一个自动化生成和执行测试用例（即提示）以测试LLM安全性的工具。首先，我们提出了一种新颖的黑盒覆盖标准，用于生成平衡且多样化的不安全测试输入，涵盖多种安全类别和语言写作特征（如不同风格和说服性写作技巧）。其次，我们采用基于LLM的方法，结合检索增强生成（RAG）、少样本提示策略和网络浏览，生成最新的测试输入。最后，与现有LLM测试自动化技术类似，我们利用LLM作为测试预言机，区分安全与不安全的测试输出，实现完全自动化的测试方法。我们对知名LLM进行了广泛评估，得出以下关键发现：i）GPT3.5在作为测试预言机时表现优异，准确检测不安全响应，甚至超越更新的LLM（如GPT-4）及专门检测不安全输出的LLM（如LlamaGuard）；ii）与现有静态数据集相比，我们的方法在相同测试输入下能发现近两倍的不安全LLM行为；iii）我们的黑盒覆盖标准结合网络浏览，能有效指导LLM生成最新的不安全测试输入，显著增加不安全行为的数量。

> Large Language Models (LLMs) have recently gained attention due to their ability to understand and generate sophisticated human-like content. However, ensuring their safety is paramount as they might provide harmful and unsafe responses. Existing LLM testing frameworks address various safety-related concerns (e.g., drugs, terrorism, animal abuse) but often face challenges due to unbalanced and obsolete datasets. In this paper, we present ASTRAL, a tool that automates the generation and execution of test cases (i.e., prompts) for testing the safety of LLMs. First, we introduce a novel black-box coverage criterion to generate balanced and diverse unsafe test inputs across a diverse set of safety categories as well as linguistic writing characteristics (i.e., different style and persuasive writing techniques). Second, we propose an LLM-based approach that leverages Retrieval Augmented Generation (RAG), few-shot prompting strategies and web browsing to generate up-to-date test inputs. Lastly, similar to current LLM test automation techniques, we leverage LLMs as test oracles to distinguish between safe and unsafe test outputs, allowing a fully automated testing approach. We conduct an extensive evaluation on well-known LLMs, revealing the following key findings: i) GPT3.5 outperforms other LLMs when acting as the test oracle, accurately detecting unsafe responses, and even surpassing more recent LLMs (e.g., GPT-4), as well as LLMs that are specifically tailored to detect unsafe LLM outputs (e.g., LlamaGuard); ii) the results confirm that our approach can uncover nearly twice as many unsafe LLM behaviors with the same number of test inputs compared to currently used static datasets; and iii) our black-box coverage criterion combined with web browsing can effectively guide the LLM on generating up-to-date unsafe test inputs, significantly increasing the number of unsafe LLM behaviors.

[Arxiv](https://arxiv.org/abs/2501.17132)