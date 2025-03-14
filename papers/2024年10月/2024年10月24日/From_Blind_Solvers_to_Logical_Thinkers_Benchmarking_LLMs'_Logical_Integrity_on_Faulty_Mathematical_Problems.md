# 从盲目求解到逻辑思考：LLMs在错误数学问题上的逻辑完整性基准测试

发布时间：2024年10月24日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在解决数学问题时的推理能力，特别是它们是否能够识别逻辑上的不一致性。论文提出了一个基准数据集FaultyMath，并通过对多种LLMs的评估，揭示了这些模型在逻辑推理方面的局限性。研究内容涉及LLMs的内在机制和推理能力，属于对LLM理论的研究。` `人工智能`

> From Blind Solvers to Logical Thinkers: Benchmarking LLMs' Logical Integrity on Faulty Mathematical Problems

# 摘要

> 考虑这个数学问题：“莉莉昨天从她最好的朋友那里收到了3块饼干，早餐吃了5块。今天，她的朋友又给了她3块饼干。莉莉现在有多少块饼干？” 许多大型语言模型（LLMs）通过“3 - 5 + 3”这个方程得出答案“1”。然而，从人类的角度来看，这个问题存在明显缺陷：莉莉最初只有3块饼干，不可能吃掉5块。这种差异引发了一个关键问题：当前的LLMs是否仅仅是盲目求解器，只进行数学运算而不进行更深层次的推理，或者它们是否能够作为逻辑思考者，识别逻辑上的不一致性？
    为了探索这个问题，我们提出了一个基准数据集FaultyMath，其中包含了多样化的错误数学问题：i）多个数学类别，如代数、几何、数论等，ii）不同难度级别，以及iii）不同来源的错误——从违反常识到数学矛盾等。我们使用FaultyMath评估了广泛的LLMs，包括开源、闭源和数学专用模型，从三个维度进行评估：（i）模型在没有明确提示的情况下，能够多准确地检测出错误的数学问题？（ii）当提供关于问题有效性的提示——无论是正确的还是误导性的——LLMs在多大程度上能够适应并成为可靠的逻辑思考者？（iii）当LLMs识别出一个数学问题有缺陷时，它们生成的解释有多可信？通过广泛的实验和详细的分析，我们的结果表明，现有的LLMs在很大程度上充当了盲目求解器的角色，未能达到作为逻辑思考者所需的推理能力。

> Consider the math problem: "Lily received 3 cookies from her best friend yesterday and ate 5 for breakfast. Today, her friend gave her 3 more cookies. How many cookies does Lily have now?" Many large language models (LLMs) in previous research approach this problem by calculating the answer "1" using the equation "3 - 5 + 3." However, from a human perspective, we recognize the inherent flaw in this problem: Lily cannot eat 5 cookies if she initially only had 3. This discrepancy prompts a key question: Are current LLMs merely Blind Solver that apply mathematical operations without deeper reasoning, or can they function as Logical Thinker capable of identifying logical inconsistencies?
  To explore this question, we propose a benchmark dataset, FaultyMath, which includes faulty math problems of rich diversity: i) multiple mathematical categories, e.g., algebra, geometry, number theory, etc., ii) varying levels of difficulty, and iii) different origins of faultiness -- ranging from violations of common sense and ambiguous statements to mathematical contradictions and more. We evaluate a broad spectrum of LLMs, including open-source, closed-source, and math-specialized models, using FaultyMath across three dimensions: (i) How accurately can the models detect faulty math problems without being explicitly prompted to do so? (ii) When provided with hints -- either correct or misleading -- about the validity of the problems, to what extent do LLMs adapt to become reliable Logical Thinker? (iii) How trustworthy are the explanations generated by LLMs when they recognize a math problem as flawed? Through extensive experimentation and detailed analysis, our results demonstrate that existing LLMs largely function as Blind Solver and fall short of the reasoning capabilities required to perform as Logical Thinker.

[Arxiv](https://arxiv.org/abs/2410.18921)