# AgentRewardBench：评估网络智能体轨迹的自动评估方法

发布时间：2025年04月11日

`Agent` `人工智能`

> AgentRewardBench: Evaluating Automatic Evaluations of Web Agent Trajectories

# 摘要

> # 摘要
Web代理通过自然语言交互让用户在网页浏览器上完成任务。评估Web代理的轨迹至关重要，因为它帮助我们确定代理是否成功完成任务。虽然基于规则的方法在评估方面有其优势，但它们在扩展到新任务时面临挑战，并且可能无法总是识别成功的轨迹。

人类评估虽然能提供更高的准确性，但过程会更慢且昂贵。而使用LLMs的自动评估则可能避免设计新规则和手动标注轨迹的挑战，从而实现更快、更经济的评估。然而，它们在评估Web代理方面的有效性尚不明确。

为此，我们提出了AgentRewardBench，这是首个评估LLM评估器在Web代理评估中有效性的基准。该基准包含来自5个基准测试和4个LLMs的1302个轨迹。每个轨迹都经过专家评审，专家会回答有关代理成功、副作用和重复性的问题。

通过我们的基准测试，我们评估了12个LLM评估器，并发现没有单一的LLM在所有基准测试中都表现出色。我们还发现，常见基准测试中使用的基于规则的评估往往会低估Web代理的成功率，这突显了基于规则评估的关键弱点，同时也强调了开发更灵活的自动评估方法的必要性。

我们已将基准测试发布在：https://agent-reward-bench.github.io


> Web agents enable users to perform tasks on web browsers through natural language interaction. Evaluating web agents trajectories is an important problem, since it helps us determine whether the agent successfully completed the tasks. Rule-based methods are widely used for this purpose, but they are challenging to extend to new tasks and may not always recognize successful trajectories. We may achieve higher accuracy through human evaluation, but the process would be substantially slower and more expensive. Automatic evaluations with LLMs may avoid the challenges of designing new rules and manually annotating trajectories, enabling faster and cost-effective evaluation. However, it is unclear how effective they are at evaluating web agents. To this end, we propose AgentRewardBench, the first benchmark to assess the effectiveness of LLM judges for evaluating web agents. AgentRewardBench contains 1302 trajectories across 5 benchmarks and 4 LLMs. Each trajectory in AgentRewardBench is reviewed by an expert, who answers questions pertaining to the success, side effects, and repetitiveness of the agent. Using our benchmark, we evaluate 12 LLM judges and find that no single LLM excels across all benchmarks. We also find that the rule-based evaluation used by common benchmarks tends to underreport the success rate of web agents, highlighting a key weakness of rule-based evaluation and the need to develop more flexible automatic evaluations. We release the benchmark at: https://agent-reward-bench.github.io

[Arxiv](https://arxiv.org/abs/2504.08942)