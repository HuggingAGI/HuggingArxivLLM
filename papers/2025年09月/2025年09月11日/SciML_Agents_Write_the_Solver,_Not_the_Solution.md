# # SciML智能体：编写求解器，而非解决方案

发布时间：2025年09月11日

`Agent` `基础理论`

> SciML Agents: Write the Solver, Not the Solution

# 摘要

> 科学机器学习领域的最新研究尝试通过神经网络（如物理知情神经网络、神经常微分方程、神经算子等）直接预测目标值以解决科学任务，但要实现高精度和强鲁棒性仍面临挑战。我们提出一种新思路：利用大型语言模型（LLMs）编写代码，借力数十年积累的数值算法。这一方式将学习解函数的负担转变为做出领域适配的数值决策。我们探究：大型语言模型能否成为科学机器学习（SciML）智能体？即，给定自然语言描述的常微分方程（ODE），能否生成科学合理的可运行代码——包括选择合适的求解器（刚性或非刚性）并执行稳定性检查。

目前，科学计算任务中此类能力的评估尚缺乏基准。为此，我们首次构建了两个新数据集：一个含对抗性“误导性”问题的诊断数据集，以及一个涵盖1000个多样化常微分方程任务的大规模基准。诊断数据集包含“表面看似刚性、实则需代数简化才能证明非刚性”的问题；大规模基准则覆盖刚性与非刚性常微分方程场景。

我们从两个维度对开源和闭源大型语言模型展开评估：（i）无引导提示 vs 融入领域知识的引导提示；（ii）现成模型 vs 微调版本。评估围绕参考解，同时衡量代码的可执行性与数值有效性。结果显示，若提供充足上下文和引导提示，新一代指令跟随模型在这两项指标上均能实现高精度。多数情况下，最新开源系统无需微调便表现优异；而较旧或规模较小的模型通过微调仍能提升性能。综上，我们的初步研究表明：通过精心设计提示与微调，可构建出能可靠求解简单常微分方程问题的专用大型语言模型智能体。

> Recent work in scientific machine learning aims to tackle scientific tasks directly by predicting target values with neural networks (e.g., physics-informed neural networks, neural ODEs, neural operators, etc.), but attaining high accuracy and robustness has been challenging. We explore an alternative view: use LLMs to write code that leverages decades of numerical algorithms. This shifts the burden from learning a solution function to making domain-aware numerical choices. We ask whether LLMs can act as SciML agents that, given a natural-language ODE description, generate runnable code that is scientifically appropriate, selecting suitable solvers (stiff vs. non-stiff), and enforcing stability checks. There is currently no benchmark to measure this kind of capability for scientific computing tasks. As such, we first introduce two new datasets: a diagnostic dataset of adversarial "misleading" problems; and a large-scale benchmark of 1,000 diverse ODE tasks. The diagnostic set contains problems whose superficial appearance suggests stiffness, and that require algebraic simplification to demonstrate non-stiffness; and the large-scale benchmark spans stiff and non-stiff ODE regimes. We evaluate open- and closed-source LLM models along two axes: (i) unguided versus guided prompting with domain-specific knowledge; and (ii) off-the-shelf versus fine-tuned variants. Our evaluation measures both executability and numerical validity against reference solutions. We find that with sufficient context and guided prompts, newer instruction-following models achieve high accuracy on both criteria. In many cases, recent open-source systems perform strongly without fine-tuning, while older or smaller models still benefit from fine-tuning. Overall, our preliminary results indicate that careful prompting and fine-tuning can yield a specialized LLM agent capable of reliably solving simple ODE problems.

[Arxiv](https://arxiv.org/abs/2509.09936)