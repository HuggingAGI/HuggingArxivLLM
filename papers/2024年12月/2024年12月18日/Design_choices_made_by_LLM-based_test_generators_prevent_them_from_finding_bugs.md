# 基于 LLM 的测试生成器的设计选择使其无法发现漏洞。

发布时间：2024年12月18日

`LLM应用` `软件测试` `软件开发`

> Design choices made by LLM-based test generators prevent them from finding bugs

# 摘要

> 如今，利用大型语言模型（LLMs）自动生成测试用例的研究与商业工具日益增多。本文深入探究了诸如 Codium CoverAgent 和 CoverUp 等近期基于 LLM 的测试生成工具，能否切实找出错误，或者不经意间验证了错误代码。鉴于错误唯有通过失败的测试用例方能暴露，我们提出疑问：当这些工具的测试判定被设定为通过时，它们能否真正达成软件测试的预期目标？以真实的人类编写的错误代码作为输入，我们对这些工具进行评估，揭示了 LLM 生成的测试无法检测错误的情况，更令人担忧的是，其设计会因在生成的测试套件中验证错误以及拒绝揭示错误的测试，而让局面愈发糟糕。这些发现引发了有关基于 LLM 的测试生成工具背后设计的有效性及其对软件质量和测试套件可靠性影响的重要问题。

> There is an increasing amount of research and commercial tools for automated test case generation using Large Language Models (LLMs). This paper critically examines whether recent LLM-based test generation tools, such as Codium CoverAgent and CoverUp, can effectively find bugs or unintentionally validate faulty code. Considering bugs are only exposed by failing test cases, we explore the question: can these tools truly achieve the intended objectives of software testing when their test oracles are designed to pass? Using real human-written buggy code as input, we evaluate these tools, showing how LLM-generated tests can fail to detect bugs and, more alarmingly, how their design can worsen the situation by validating bugs in the generated test suite and rejecting bug-revealing tests. These findings raise important questions about the validity of the design behind LLM-based test generation tools and their impact on software quality and test suite reliability.

[Arxiv](https://arxiv.org/abs/2412.14137)