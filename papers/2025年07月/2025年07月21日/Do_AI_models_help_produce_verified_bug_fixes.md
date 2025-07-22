# AI能否生成可靠的错误修复方案？

发布时间：2025年07月21日

`LLM应用` `软件工程` `自动程序修复`

> Do AI models help produce verified bug fixes?

# 摘要

> 在软件工程领域，AI技术--特别是大型语言模型--似乎有望带来显著改进，其中一个极具吸引力的领域是自动程序修复（APR），即对软件错误进行令人满意的修正。这种期望在实践中是否能够实现？我们如何才能确定所提出的修正确实有效？如果程序员能够使用LLMs，他们将如何利用这些工具来补充自己的技能？

    为了回答这些问题，我们借助了一个程序验证环境，该环境能够正式确定所提出修正的正确性，从而对两组随机分配的程序员进行了研究，一组可以使用LLMs，另一组则不能，两组都通过证明工具验证自己的答案。研究方法基于目标-查询-度量方法，将问题划分为一般性研究目标（目标）、可获得具体答案的具体要素（查询）以及支持这些答案的测量指标（度量）。尽管目前仅应用于有限的样本量，但这些结果是迈向为AI和LLMs在提供保证正确性程序修复方面确定合适角色的第一步。

    这些结果与人们可能对AI用于调试和APR的预期相比令人惊讶。研究贡献包括：用于调试中使用LLMs的实验的详细方法学，其他项目可以重复使用；通过全程录屏实现的对程序员行为的细粒度分析；LLMs使用模式的定义，包含7种不同的类别；以及经过验证的建议，以最大化LLMs在调试和自动程序修复中的效用。

> Among areas of software engineering where AI techniques -- particularly, Large Language Models -- seem poised to yield dramatic improvements, an attractive candidate is Automatic Program Repair (APR), the production of satisfactory corrections to software bugs. Does this expectation materialize in practice? How do we find out, making sure that proposed corrections actually work? If programmers have access to LLMs, how do they actually use them to complement their own skills?
  To answer these questions, we took advantage of the availability of a program-proving environment, which formally determines the correctness of proposed fixes, to conduct a study of program debugging with two randomly assigned groups of programmers, one with access to LLMs and the other without, both validating their answers through the proof tools. The methodology relied on a division into general research questions (Goals in the Goal-Query-Metric approach), specific elements admitting specific answers (Queries), and measurements supporting these answers (Metrics). While applied so far to a limited sample size, the results are a first step towards delineating a proper role for AI and LLMs in providing guaranteed-correct fixes to program bugs.
  These results caused surprise as compared to what one might expect from the use of AI for debugging and APR. The contributions also include: a detailed methodology for experiments in the use of LLMs for debugging, which other projects can reuse; a fine-grain analysis of programmer behavior, made possible by the use of full-session recording; a definition of patterns of use of LLMs, with 7 distinct categories; and validated advice for getting the best of LLMs for debugging and Automatic Program Repair.

[Arxiv](https://arxiv.org/abs/2507.15822)