# # 自动化验证文本约束面向AutomationML基于LLMs与SHACL

发布时间：2025年06月12日

`LLM应用

理由：这篇论文讨论了将大型语言模型（LLM）应用于自动化建模语言（AML）的约束形式化和验证过程。具体来说，LLM被用来将文本规则转化为SHACL约束，并对AML本体进行验证。这属于LLM在具体任务中的应用，因此归类为LLM应用。` `自动化`

> Automated Validation of Textual Constraints Against AutomationML via LLMs and SHACL

# 摘要

> # 自动化建模语言（AML）
AutomationML（AML）实现了工程领域中的标准化数据交换，但现有的AML建模规范通常以非正式的文本约束形式呈现。这些约束无法在AML自身中进行自动验证。本文的工作进展论文介绍了一种将此类约束形式化并验证的流水线。首先，通过RML和SPARQL将AML模型映射到OWL本体。此外，大型语言模型将文本规则转化为SHACL约束，然后对之前生成的AML本体进行验证。最后，SHACL验证结果会以自然语言自动解释。该方法通过一个AML建议示例进行演示。结果表明，即使是复杂的建模规则也可以通过半自动化方式检查，无需用户理解形式化方法或本体技术。

> AutomationML (AML) enables standardized data exchange in engineering, yet existing recommendations for proper AML modeling are typically formulated as informal and textual constraints. These constraints cannot be validated automatically within AML itself. This work-in-progress paper introduces a pipeline to formalize and verify such constraints. First, AML models are mapped to OWL ontologies via RML and SPARQL. In addition, a Large Language Model translates textual rules into SHACL constraints, which are then validated against the previously generated AML ontology. Finally, SHACL validation results are automatically interpreted in natural language. The approach is demonstrated on a sample AML recommendation. Results show that even complex modeling rules can be semi-automatically checked -- without requiring users to understand formal methods or ontology technologies.

[Arxiv](https://arxiv.org/abs/2506.10678)