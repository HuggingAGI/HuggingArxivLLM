# # 大型语言模型的最坏情况鲁棒性探索

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在面对对抗性攻击时的脆弱性，并提出了一种新的防御方法（DiffTextPure）。论文的核心内容集中在理论分析和鲁棒性证明上，特别是通过数学方法（如Fractal Knapsack或0-1 Knapsack求解器）推导出鲁棒性下界。这些内容属于对LLMs的理论研究和分析，因此应归类为LLM理论。` `网络安全`

> Towards the Worst-case Robustness of Large Language Models

# 摘要

> # 摘要
最近的研究表明，大型语言模型（LLMs）在面对对抗性攻击时存在脆弱性，攻击者通过精心设计的输入序列诱导模型产生有害、暴力、隐私泄露或错误的输出。尽管已有多种防御方法提出，但这些方法尚未经过强适应性攻击的评估，导致LLMs在最坏情况下的鲁棒性仍然难以解决。通过开发一种更强的白盒攻击，我们的评估结果显示，大多数典型防御方法的鲁棒性几乎为0%。为此，我们提出了	extit{DiffTextPure}，这是一种通用防御方法，它通过预定义的平滑分布对对抗性输入进行扩散，并使用预训练的语言模型对扩散后的输入进行净化。理论上，我们使用Fractal Knapsack或0-1 Knapsack求解器推导出所有平滑分布的紧致鲁棒性下界。在此框架下，我们证明了特定情况——使用均匀核平滑LLMs——对	extit{任何可能的攻击}的鲁棒性，平均$\ell_0$扰动为2.02或平均后缀长度为6.41。

> Recent studies have revealed the vulnerability of Large Language Models (LLMs) to adversarial attacks, where the adversary crafts specific input sequences to induce harmful, violent, private, or incorrect outputs. Although various defenses have been proposed, they have not been evaluated by strong adaptive attacks, leaving the worst-case robustness of LLMs still intractable. By developing a stronger white-box attack, our evaluation results indicate that most typical defenses achieve nearly 0\% robustness.To solve this, we propose \textit{DiffTextPure}, a general defense that diffuses the (adversarial) input prompt using any pre-defined smoothing distribution, and purifies the diffused input using a pre-trained language model. Theoretically, we derive tight robustness lower bounds for all smoothing distributions using Fractal Knapsack or 0-1 Knapsack solvers. Under this framework, we certify the robustness of a specific case -- smoothing LLMs using a uniform kernel -- against \textit{any possible attack} with an average $\ell_0$ perturbation of 2.02 or an average suffix length of 6.41.

[Arxiv](https://arxiv.org/abs/2501.19040)