# 爱立信利用程序分析增强的微调大型语言模型生成测试代码

发布时间：2025年04月23日

`LLM应用` `软件开发` `测试代码生成`

> Test code generation at Ericsson using Program Analysis Augmented Fine Tuned LLMs

# 摘要

> 我们介绍了爱立信中使用大型语言模型（LLMs）生成测试代码的方法。输入是以自然语言描述的测试步骤（英文），输出是实现该测试步骤的Java代码。我们发现，直接使用提示方法无法满足需求，因为LLM会假设一些代码库中并不存在的功能和签名。为了解决这一问题，我们结合了检索增强生成（RAG）和提示工程，通过静态程序分析扩展了简单的提示，增加了额外的上下文信息。此外，我们还通过微调底层LLM获得了进一步的改进。微调基于一个自定义设计的提示模板，其中包含了预先依赖的类、它们的公共方法以及从RAG获得的两个示例输出。实验结果表明，微调后的模型在传统F1分数指标上，显著提升了生成代码与原始开发人员编写的测试代码的对应性和一致性。具体而言，对一个8x7b专家混合模型（MoE）进行微调，平均性能提升了8%，这一结果甚至与一个规模大得多的8x22b MoE模型相当。

> We describe test code generation using Large Language Models (LLMs) in Ericsson. Our input is a test step in natural language (English) and our output is code (Java) which accomplishes the test step. We describe how straight forward prompting does not suffice and results in LLM assuming functions and signatures which are not present in the code repository. We then show how we alleviate the problem by a combination of Retrieval Augmented Generation (RAG) along with prompt engineering that expanded the simple prompt with additional contextual information using static program analysis. We then describe further improvements that we obtained by fine-tuning the underlying LLM. The fine tuning is done based on a custom designed prompt template which has pre-dependent classes, their public methods as well two exemplar outputs obtained from RAG. Our results establish that our fine tuned models help improve the correspondence or conformity with the original developer written test code as measured by the traditional metrics of F1-score based on the methods used in the generated code. Fine tuning of a 8x7b Mixture of Experts (MoE) model leads to an average improvement of 8\% over the base model and is comparable to the scores on a much larger 8x22b MoE model.

[Arxiv](https://arxiv.org/abs/2506.11006)