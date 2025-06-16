# 从COBOL到Java的转换实现自动化验证

发布时间：2025年04月14日

`LLM应用

论文摘要讨论了基于大型语言模型的生成式AI技术在代码转换中的应用，特别是将旧式语言转换为现代语言，并提出了一种验证工具。这属于LLM的实际应用，因此归类为LLM应用。` `软件工程` `人工智能`

> Automated Validation of COBOL to Java Transformation

# 摘要

> 近年来，基于大型语言模型（LLM）的生成式AI技术取得了显著进展，使得将COBOL等旧式语言的企业级代码转换为Java或Python等现代语言成为可能。虽然基于LLM的自动转换结果令人鼓舞，但生成的代码无法保证与原代码完全等效。为此，我们提出了一种框架和工具，用于验证COBOL与转换后的Java代码的等价性。这些结果不仅可以帮助修复代码中的问题，还能为AI模型提供反馈以改进性能。我们开发了一种基于符号执行的测试生成方法，能够自动为源COBOL程序生成单元测试，并模拟外部资源调用。我们还生成了与COBOL等效的JUnit测试用例，并运行这些测试以验证原程序与转换后程序的语义等价性。

> Recent advances in Large Language Model (LLM) based Generative AI techniques have made it feasible to translate enterpriselevel code from legacy languages such as COBOL to modern languages such as Java or Python. While the results of LLM-based automatic transformation are encouraging, the resulting code cannot be trusted to correctly translate the original code. We propose a framework and a tool to help validate the equivalence of COBOL and translated Java. The results can also help repair the code if there are some issues and provide feedback to the AI model to improve. We have developed a symbolic-execution-based test generation to automatically generate unit tests for the source COBOL programs which also mocks the external resource calls. We generate equivalent JUnit test cases with equivalent mocking as COBOL and run them to check semantic equivalence between original and translated programs.

[Arxiv](https://arxiv.org/abs/2506.10999)