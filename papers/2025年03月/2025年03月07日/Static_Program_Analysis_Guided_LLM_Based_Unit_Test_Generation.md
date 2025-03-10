# 静态程序分析指导的基于LLM的单元测试生成

发布时间：2025年03月07日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于生成Java方法的单元测试，属于LLM的应用领域。它展示了如何通过优化提示来提升生成效果，并在实际项目中验证了方法的有效性。` `软件工程` `程序分析`

> Static Program Analysis Guided LLM Based Unit Test Generation

# 摘要

> 我们提出了一种利用大型语言模型（LLMs）自动化生成Java方法单元测试的新方法。现有基于LLM的方法主要依赖两种方式：一是目标方法的示例用法，二是提供目标方法所属的整个类作为输入提示和上下文。然而，前者因示例用法缺失（尤其是针对新编写的待测方法）而难以实施，后者则因扩展性不足而难以应对复杂场景——目标方法越复杂、关联类越大，就越难生成足够的测试代码（受限于LLM的提示和上下文长度等因素）。我们发现，通过程序分析为目标方法生成简洁且精确的上下文信息来增强提示，可以显著提升LLMs生成单元测试代码的效果。我们已在大型商业项目和流行开源项目中验证了这一方法的有效性。

> We describe a novel approach to automating unit test generation for Java methods using large language models (LLMs). Existing LLM-based approaches rely on sample usage(s) of the method to test (focal method) and/or provide the entire class of the focal method as input prompt and context. The former approach is often not viable due to the lack of sample usages, especially for newly written focal methods. The latter approach does not scale well enough; the bigger the complexity of the focal method and larger associated class, the harder it is to produce adequate test code (due to factors such as exceeding the prompt and context lengths of the underlying LLM). We show that augmenting prompts with \emph{concise} and \emph{precise} context information obtained by program analysis %of the focal method increases the effectiveness of generating unit test code through LLMs. We validate our approach on a large commercial Java project and a popular open-source Java project.

[Arxiv](https://arxiv.org/abs/2503.05394)