# MatchFixAgent：语言无关的自主仓库级代码翻译验证与修复

发布时间：2025年09月19日

`Agent` `基础理论`

> MatchFixAgent: Language-Agnostic Autonomous Repository-Level Code Translation Validation and Repair

# 摘要

> 代码翻译是将源代码从一种编程语言（PL）转换为另一种的过程。验证翻译的功能等效性并在必要时进行修复，是代码翻译的关键环节。现有的自动化验证与修复方法因工程成本高昂而难以适配多种编程语言，且依赖于现有但往往不完善的测试套件，导致等效性误判和修复效果不佳。为此，我们开发了MatchFixAgent——一个基于大型语言模型（LLM）、与编程语言无关的翻译等效性验证与修复框架。该框架采用多智能体架构，将等效性验证拆解为多个子任务，确保对翻译进行全面且一致的语义分析；随后将分析结果传递给测试智能体，用于编写和执行测试；若测试失败，修复智能体则尝试修复翻译错误；最终由判定智能体综合语义分析与测试结果，做出等效性（或不等效性）判定。
  我们将MatchFixAgent的验证与修复效果同四种仓库级代码翻译技术进行了对比，使用了来自这些技术成果的2219个翻译对（涵盖6个编程语言对），这些翻译对取自24个GitHub项目，代码总量超90万行。结果显示，MatchFixAgent能对99.2%的翻译对做出等效性（或不等效性）判定，其中72.8%的判定结果与先前工作一致；当判定结果不一致时，60.7%的情况下MatchFixAgent的判定是正确的。此外，MatchFixAgent可修复50.6%的不等效翻译，而先前工作仅为18.5%。这表明，MatchFixAgent不仅对多种编程语言对的适应性远超现有方法，还能提供高精度的验证结果。

> Code translation transforms source code from one programming language (PL) to another. Validating the functional equivalence of translation and repairing, if necessary, are critical steps in code translation. Existing automated validation and repair approaches struggle to generalize to many PLs due to high engineering overhead, and they rely on existing and often inadequate test suites, which results in false claims of equivalence and ineffective translation repair. We develop MatchFixAgent, a large language model (LLM)-based, PL-agnostic framework for equivalence validation and repair of translations. MatchFixAgent features a multi-agent architecture that divides equivalence validation into several sub-tasks to ensure thorough and consistent semantic analysis of the translation. Then it feeds this analysis to test agent to write and execute tests. Upon observing a test failure, the repair agent attempts to fix the translation bug. The final (in)equivalence decision is made by the verdict agent, considering semantic analyses and test execution results.
  We compare MatchFixAgent's validation and repair results with four repository-level code translation techniques. We use 2,219 translation pairs from their artifacts, which cover 6 PL pairs, and are collected from 24 GitHub projects totaling over 900K lines of code. Our results demonstrate that MatchFixAgent produces (in)equivalence verdicts for 99.2% of translation pairs, with the same equivalence validation result as prior work on 72.8% of them. When MatchFixAgent's result disagrees with prior work, we find that 60.7% of the time MatchFixAgent's result is actually correct. In addition, we show that MatchFixAgent can repair 50.6% of inequivalent translation, compared to prior work's 18.5%. This demonstrates that MatchFixAgent is far more adaptable to many PL pairs than prior work, while producing highly accurate validation results.

[Arxiv](https://arxiv.org/abs/2509.16187)