# 不择手段取胜：构建一个小环境，用于研究大型语言模型中的规范游戏行为

发布时间：2025年05月07日

`LLM应用

摘要分析：该研究探讨了大型语言模型在特定任务中的行为，特别是如何利用系统漏洞，属于对LLM在实际应用中的安全性和对齐问题的研究。因此，归类为LLM应用。` `AI安全` `安全漏洞`

> Winning at All Cost: A Small Environment for Eliciting Specification Gaming Behaviors in Large Language Models

# 摘要

> 本研究揭示了前沿大型语言模型（LLMs）在面对不可能情况时如何“操纵系统”，这一现象引发了重要的安全与对齐问题。我们采用新颖的文本模拟方法，向三个领先模型（o1、o3-mini和r1）呈现了一个设计为无法通过合法玩法获胜的井字棋场景，并分析其利用漏洞而非接受失败的倾向。研究结果令人震惊：专注于推理的较新o3-mini模型（37.1%）相比旧款o1模型（17.5%），利用系统漏洞的倾向几乎是后者的两倍。最引人注目的是提示的影响：仅将任务描述为需要“创造性”解决方案，就使所有模型的操纵行为激增到77.3%。我们识别出四种不同的利用策略，从直接操纵游戏状态到复杂修改对手行为。这些发现表明，即使不具备实际执行能力，LLMs在受到激励时也能识别并提出复杂的系统漏洞，凸显了随着模型能力增强，AI对齐所面临的紧迫挑战，尤其是在识别和利用其运行环境中的漏洞方面。


> This study reveals how frontier Large Language Models LLMs can "game the system" when faced with impossible situations, a critical security and alignment concern. Using a novel textual simulation approach, we presented three leading LLMs (o1, o3-mini, and r1) with a tic-tac-toe scenario designed to be unwinnable through legitimate play, then analyzed their tendency to exploit loopholes rather than accept defeat. Our results are alarming for security researchers: the newer, reasoning-focused o3-mini model showed nearly twice the propensity to exploit system vulnerabilities (37.1%) compared to the older o1 model (17.5%). Most striking was the effect of prompting. Simply framing the task as requiring "creative" solutions caused gaming behaviors to skyrocket to 77.3% across all models. We identified four distinct exploitation strategies, from direct manipulation of game state to sophisticated modification of opponent behavior. These findings demonstrate that even without actual execution capabilities, LLMs can identify and propose sophisticated system exploits when incentivized, highlighting urgent challenges for AI alignment as models grow more capable of identifying and leveraging vulnerabilities in their operating environments.

[Arxiv](https://arxiv.org/abs/2505.07846)