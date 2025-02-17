# 多样化推理与验证：助力高级推理能力

发布时间：2025年02月14日

`LLM应用`

> Diverse Inference and Verification for Advanced Reasoning

# 摘要

> 推理型大语言模型（LLMs）如 OpenAI 的 o1、o3 和 DeepSeek 的 R1 在数学和编程领域取得了显著进展，但在解决国际数学奥林匹克（IMO）组合数学题、抽象与推理语料库（ARC）谜题以及人类最后考试（HLE）问题等高级任务时仍面临挑战。我们采用多样化推理方法，在测试时结合多种模型和方法。通过验证数学和代码问题，并对其他问题进行拒绝采样，我们发现这是一种简单有效的策略。我们使用 Lean 自动验证 IMO 问题的正确性，通过代码解决 ARC 谜题，并发现最佳的 N 策略能够有效回答 HLE 问题。我们的方法显著提升了准确率：将 IMO 组合数学题的准确率从 33.3% 提高到 77.8%，HLE 问题的准确率从 8% 提高到 37%。此外，我们解决了 948 位人类无法解决的 80% ARC 谜题，以及 o3 高计算模型无法解决的 26.5% ARC 谜题。通过测试时间模拟、强化学习和基于推理反馈的元学习，我们调整智能体图表示、变化提示词、代码和数据集，从而提升泛化能力。我们的方法可靠、健壮且可扩展，并且秉承可重复研究的精神，将在发表后公开发布。

> Reasoning LLMs such as OpenAI o1, o3 and DeepSeek R1 have made significant progress in mathematics and coding, yet find challenging advanced tasks such as International Mathematical Olympiad (IMO) combinatorics problems, Abstraction and Reasoning Corpus (ARC) puzzles, and Humanity's Last Exam (HLE) questions. We use a diverse inference approach that combines multiple models and methods at test time. We find that verifying mathematics and code problems, and rejection sampling on other problems is simple and effective. We automatically verify correctness of solutions to IMO problems by Lean, and ARC puzzles by code, and find that best-of-N effectively answers HLE questions. Our approach increases answer accuracy on IMO combinatorics problems from 33.3% to 77.8%, accuracy on HLE questions from 8% to 37%, and solves 80% of ARC puzzles that 948 humans could not and 26.5% of ARC puzzles that o3 high compute does not. Test-time simulations, reinforcement learning, and meta-learning with inference feedback improve generalization by adapting agent graph representations and varying prompts, code, and datasets. Our approach is reliable, robust, and scalable, and in the spirit of reproducible research, we will make it publicly available upon publication.

[Arxiv](https://arxiv.org/abs/2502.09955)