# HoarePrompt：通过自然语言进行程序正确性的结构化推理

发布时间：2025年03月25日

`LLM应用` `软件工程` `程序分析`

> HoarePrompt: Structural Reasoning About Program Correctness in Natural Language

# 摘要

> 软件需求通常以自然语言形式表达，但验证程序与自然语言需求的一致性是一个极具挑战性且尚未充分探索的问题。大型语言模型（LLMs）被视为解决这一难题的潜在方案，然而实践表明，它们在此类任务中表现欠佳，往往难以检测连简单错误都发现不了。为填补这一空白，我们提出了HoarePrompt，一种将程序分析与验证的核心思想融入自然语言处理的创新方法。受最强后置条件演算启发，HoarePrompt采用系统化的分步流程，通过LLM生成代码各关键点的可达程序状态描述。针对循环结构，我们引入了基于少量样本驱动的k-归纳法，这是模型检查领域广泛应用的k-归纳方法的改编版本。在程序状态描述完成后，HoarePrompt借助LLM评估标注有状态描述的程序是否符合自然语言需求。为评估程序正确性分类器在自然语言需求下的表现，我们构建了CoCoClaNeL数据集，这是一个极具挑战性的编程竞赛问题解决方案集合。实验结果显示，与直接采用Zero-shot-CoT提示进行正确性分类相比，HoarePrompt使MCC提升了62%。此外，HoarePrompt在通过LLM驱动的测试生成评估正确性的分类器方面表现更优，MCC提升了93%。其中，归纳推理机制为MCC贡献了28%的提升，充分证明了其在循环管理上的有效性。

> While software requirements are often expressed in natural language, verifying the correctness of a program against natural language requirements is a hard and underexplored problem. Large language models (LLMs) are promising candidates for addressing this challenge, however our experience shows that they are ineffective in this task, often failing to detect even straightforward bugs. To address this gap, we introduce HoarePrompt, a novel approach that adapts fundamental ideas from program analysis and verification to natural language artifacts. Drawing inspiration from the strongest postcondition calculus, HoarePrompt employs a systematic, step-by-step process in which an LLM generates natural language descriptions of reachable program states at various points in the code. To manage loops, we propose few-shot-driven k-induction, an adaptation of the k-induction method widely used in model checking. Once program states are described, HoarePrompt leverages the LLM to assess whether the program, annotated with these state descriptions, conforms to the natural language requirements. For evaluating the quality of classifiers of program correctness with respect to natural language requirements, we constructed CoCoClaNeL, a challenging dataset of solutions to programming competition problems. Our experiments show that HoarePrompt improves the MCC by 62% compared to directly using Zero-shot-CoT prompts for correctness classification. Furthermore, HoarePrompt outperforms a classifier that assesses correctness via LLM-based test generation by increasing the MCC by 93%. The inductive reasoning mechanism contributes a 28% boost to MCC, underscoring its effectiveness in managing loops.

[Arxiv](https://arxiv.org/abs/2503.19599)