# 从校准到协作：LLM 不确定性量化应当更加以人为本

发布时间：2025年06月09日

`LLM理论` `人工智能`

> From Calibration to Collaboration: LLM Uncertainty Quantification Should Be More Human-Centered

# 摘要

> 大型语言模型（LLMs）在现实世界中的应用日益广泛，但其可靠性仍存疑虑。不确定性量化（UQ）被视为一种工具，通过让用户了解何时可以信任LLM预测，从而增强人与LLM之间的协作。我们主张，目前针对LLMs的不确定性量化方法并不理想，无法为在现实任务中做决策的人类用户提供有用的UQ。通过分析40种LLM UQ方法，我们发现阻碍社区朝着造福下游用户的目标前进的三个普遍做法：1）在生态效度低的基准上进行评估；2）仅考虑认识不确定性；3）优化不一定能反映下游效用的指标。针对每个问题，我们提出了具体的以用户为中心的实践和研究方向，供LLM UQ研究人员参考。我们主张，社区应采取一种更以人类为中心的方法来进行LLM不确定性量化，而不是在不具代表性的任务上使用不完美的指标进行优化。

> Large Language Models (LLMs) are increasingly assisting users in the real world, yet their reliability remains a concern. Uncertainty quantification (UQ) has been heralded as a tool to enhance human-LLM collaboration by enabling users to know when to trust LLM predictions. We argue that current practices for uncertainty quantification in LLMs are not optimal for developing useful UQ for human users making decisions in real-world tasks. Through an analysis of 40 LLM UQ methods, we identify three prevalent practices hindering the community's progress toward its goal of benefiting downstream users: 1) evaluating on benchmarks with low ecological validity; 2) considering only epistemic uncertainty; and 3) optimizing metrics that are not necessarily indicative of downstream utility. For each issue, we propose concrete user-centric practices and research directions that LLM UQ researchers should consider. Instead of hill-climbing on unrepresentative tasks using imperfect metrics, we argue that the community should adopt a more human-centered approach to LLM uncertainty quantification.

[Arxiv](https://arxiv.org/abs/2506.07461)