# 基于本地大型语言模型的隐私保护型网络表单填写推荐器

发布时间：2025年09月01日

`LLM应用` `金融科技` `零售与电商`

> A Privacy-Preserving Recommender for Filling Web Forms Using a Local Large Language Model

# 摘要

> Web应用在教育、金融、电子商务等关键领域的应用日益广泛，这凸显了确保其无故障运行的重要性。Web表单测试是评估无故障性能的有效手段，而制定有效的测试场景是实现全面准确评估的核心。这一过程的核心在于为表单字段填充合适的数值，从而生成有效的测试用例。然而，手动生成这些数值不仅耗时，还容易出错。为解决这一问题，人们开发了多种工具来辅助测试人员。随着大型语言模型（LLMs）的兴起，新一代工具开始尝试更智能地完成这项任务。尽管已有不少基于LLM的工具问世，但由于这类模型通常依赖云基础设施，在测试机密Web表单时，其使用可能导致意外数据泄露和机密性受损的风险，这引发了人们的担忧。本文提出了一种基于大型语言模型的隐私保护推荐器，可在本地运行。该工具通过推荐有效的字段值，帮助测试人员开展Web表单测试。它会分析表单的HTML结构，检测输入类型，并根据每个字段的类型和上下文内容提取约束条件，进而指导正确的字段填充。

> Web applications are increasingly used in critical domains such as education, finance, and e-commerce. This highlights the need to ensure their failure-free performance. One effective method for evaluating failure-free performance is web form testing, where defining effective test scenarios is key to a complete and accurate evaluation. A core aspect of this process involves filling form fields with suitable values to create effective test cases. However, manually generating these values is time-consuming and prone to errors. To address this, various tools have been developed to assist testers. With the appearance of large language models (LLMs), a new generation of tools seeks to handle this task more intelligently. Although many LLM-based tools have been introduced, as these models typically rely on cloud infrastructure, their use in testing confidential web forms raises concerns about unintended data leakage and breaches of confidentiality. This paper introduces a privacy-preserving recommender that operates locally using a large language model. The tool assists testers in web form testing by suggesting effective field values. This tool analyzes the HTML structure of forms, detects input types, and extracts constraints based on each field's type and contextual content, guiding proper field filling.

[Arxiv](https://arxiv.org/abs/2509.01527)