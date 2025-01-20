# 探究LLMs在自动化技术债务偿还中的有效性

发布时间：2025年01月16日

`LLM应用

**理由**：这篇论文主要探讨了如何利用大型语言模型（LLMs）来自动偿还自认技术债务（SATD），并提出了新的数据集和评估指标。研究重点在于LLMs在代码维护和修复任务中的应用，属于LLM在实际软件开发中的具体应用场景。因此，分类为LLM应用是合适的。` `软件工程` `代码维护`

> Understanding the Effectiveness of LLMs in Automated Self-Admitted Technical Debt Repayment

# 摘要

> # 摘要
自认技术债务（SATD）——开发者通过注释有意承认代码中的次优解决方案——对软件可维护性构成了重大挑战。若未及时解决，SATD会降低代码质量并增加维护成本。尽管大型语言模型（LLMs）在代码生成和程序修复等任务中表现出色，但其在自动偿还SATD方面的潜力仍待挖掘。
  本文中，我们指出了训练和评估LLMs用于SATD偿还的三大挑战：（1）数据集的代表性和可扩展性，（2）去除无关的SATD偿还，（3）现有评估指标的局限性。针对前两个挑战，我们采用了一种语言无关的SATD追踪工具，并设计了一个10步过滤流程，从代码库中提取SATD偿还，生成了两个大规模数据集：58,722个Python项目和97,347个Java项目。为改进评估，我们引入了两个基于代码差异的指标：BLEU-diff和CrystalBLEU-diff，它们专注于代码变化而非整体代码。此外，我们还提出了一个新指标LEMOD，兼具可解释性和信息量。
  基于新基准和评估指标，我们评估了两种自动SATD偿还方法：微调较小模型和使用五种大规模模型的提示工程。结果显示，微调的小模型在Exact Match（EM）得分上与基于提示的方法相当，但在基于BLEU的指标和LEMOD上表现稍逊。值得注意的是，Gemma-2-9B在EM上表现最佳，解决了10.1%的Python和8.1%的Java SATD，而Llama-3.1-70B-Instruct和GPT-4o-mini在BLEU-diff、CrystalBLEU-diff和LEMOD指标上表现突出。我们的研究贡献了一个稳健的基准、改进的评估指标以及对LLMs的全面评估，推动了自动SATD偿还领域的研究进展。

> Self-Admitted Technical Debt (SATD), cases where developers intentionally acknowledge suboptimal solutions in code through comments, poses a significant challenge to software maintainability. Left unresolved, SATD can degrade code quality and increase maintenance costs. While Large Language Models (LLMs) have shown promise in tasks like code generation and program repair, their potential in automated SATD repayment remains underexplored.
  In this paper, we identify three key challenges in training and evaluating LLMs for SATD repayment: (1) dataset representativeness and scalability, (2) removal of irrelevant SATD repayments, and (3) limitations of existing evaluation metrics. To address the first two dataset-related challenges, we adopt a language-independent SATD tracing tool and design a 10-step filtering pipeline to extract SATD repayments from repositories, resulting two large-scale datasets: 58,722 items for Python and 97,347 items for Java. To improve evaluation, we introduce two diff-based metrics, BLEU-diff and CrystalBLEU-diff, which measure code changes rather than whole code. Additionally, we propose another new metric, LEMOD, which is both interpretable and informative. Using our new benchmarks and evaluation metrics, we evaluate two types of automated SATD repayment methods: fine-tuning smaller models, and prompt engineering with five large-scale models. Our results reveal that fine-tuned small models achieve comparable Exact Match (EM) scores to prompt-based approaches but underperform on BLEU-based metrics and LEMOD. Notably, Gemma-2-9B leads in EM, addressing 10.1% of Python and 8.1% of Java SATDs, while Llama-3.1-70B-Instruct and GPT-4o-mini excel on BLEU-diff, CrystalBLEU-diff, and LEMOD metrics. Our work contributes a robust benchmark, improved evaluation metrics, and a comprehensive evaluation of LLMs, advancing research on automated SATD repayment.

[Arxiv](https://arxiv.org/abs/2501.09888)