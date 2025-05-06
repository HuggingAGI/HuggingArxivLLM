# 再见，蓝皮书？借助大型语言模型自动化法律流程

发布时间：2025年05月05日

`LLM应用` `引用格式`

> Bye-bye, Bluebook? Automating Legal Procedure with Large Language Models

# 摘要

> 法律实践需要严格遵守程序规则。在美国，《The Bluebook: A Uniform System of Citation》堪称是最复杂的程序规则之一。严格遵循其长达500多页的复杂格式说明，是法律评论编辑的核心职责，却也是众多律师的噩梦。为了测试大型语言模型（LLMs）是否能应对如此复杂的程序规则，我们创建了一个包含866个Bluebook任务的专用数据集，并对来自OpenAI、Anthropic、Google、Meta和DeepSeek的旗舰LLMs进行了测试。结果显示，（1）这些模型仅能在69%-74%的情况下生成完全符合Bluebook格式的引用，（2）而通过上下文学习Bluebook的规则系统，准确率也仅提升至77%。这些发现提醒我们，在法律领域中，对于那些需要严格遵守程序规则的方面，使用现成的LLMs实现自动化可能并不可靠。

> Legal practice requires careful adherence to procedural rules. In the United States, few are more complex than those found in The Bluebook: A Uniform System of Citation. Compliance with this system's 500+ pages of byzantine formatting instructions is the raison d'etre of thousands of student law review editors and the bete noire of lawyers everywhere. To evaluate whether large language models (LLMs) are able to adhere to the procedures of such a complicated system, we construct an original dataset of 866 Bluebook tasks and test flagship LLMs from OpenAI, Anthropic, Google, Meta, and DeepSeek. We show (1) that these models produce fully compliant Bluebook citations only 69%-74% of the time and (2) that in-context learning on the Bluebook's underlying system of rules raises accuracy only to 77%. These results caution against using off-the-shelf LLMs to automate aspects of the law where fidelity to procedure is paramount.

[Arxiv](https://arxiv.org/abs/2505.02763)