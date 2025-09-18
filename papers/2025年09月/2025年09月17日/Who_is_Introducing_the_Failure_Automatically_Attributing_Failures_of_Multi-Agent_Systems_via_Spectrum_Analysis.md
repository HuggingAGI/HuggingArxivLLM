# 谁导致了故障？基于频谱分析的多智能体系统故障自动归因

发布时间：2025年09月17日

`Agent` `基础理论`

> Who is Introducing the Failure? Automatically Attributing Failures of Multi-Agent Systems via Spectrum Analysis

# 摘要

> 大型语言模型驱动的多智能体系统（MASs）正日益用于解决编程、科学发现等复杂现实问题的自动化任务。尽管前景向好，MASs仍存在诸多不足。但MASs的故障归因（即定位导致失败的具体智能体行为）研究尚浅且耗时费力，严重阻碍了系统调试与优化。为此，我们提出了首个基于频谱的MASs故障归因方法FAMAS，其通过系统的轨迹重放与抽象，结合频谱分析实现故障定位。FAMAS的核心思路是通过分析多次MAS执行的差异，评估每个智能体行为引发故障的概率。具体而言，我们设计了一种适用于MASs的新型可疑度公式，该公式融合智能体行为组与动作行为组两大关键因素，以捕捉MASs执行轨迹中的智能体激活模式与动作激活模式。在Who and When基准测试中，FAMAS与12种基线方法展开了全面对比，结果表明其性能显著优于所有对比方法。

> Large Language Model Powered Multi-Agent Systems (MASs) are increasingly employed to automate complex real-world problems, such as programming and scientific discovery. Despite their promising, MASs are not without their flaws. However, failure attribution in MASs - pinpointing the specific agent actions responsible for failures - remains underexplored and labor-intensive, posing significant challenges for debugging and system improvement. To bridge this gap, we propose FAMAS, the first spectrum-based failure attribution approach for MASs, which operates through systematic trajectory replay and abstraction, followed by spectrum analysis.The core idea of FAMAS is to estimate, from variations across repeated MAS executions, the likelihood that each agent action is responsible for the failure. In particular, we propose a novel suspiciousness formula tailored to MASs, which integrates two key factor groups, namely the agent behavior group and the action behavior group, to account for the agent activation patterns and the action activation patterns within the execution trajectories of MASs. Through expensive evaluations against 12 baselines on the Who and When benchmark, FAMAS demonstrates superior performance by outperforming all the methods in comparison.

[Arxiv](https://arxiv.org/abs/2509.13782)