# MELON：间接提示注入防御——基于遮蔽重执行与工具对比

发布时间：2025年02月07日

`Agent` `网络安全`

> MELON: Indirect Prompt Injection Defense via Masked Re-execution and Tool Comparison

# 摘要

> 近期研究发现，LLM代理易受间接提示注入（IPI）攻击。攻击者将恶意任务隐藏在工具检索的信息中，可能诱导代理执行未经授权的操作。现有的IPI防御措施存在显著局限性：要么需要大量模型训练资源，要么无法有效应对复杂攻击，要么损害正常功能。我们提出了一种新型IPI防御方法——MELON（Masked re-Execution and TooL comparisON）。我们的方法基于以下观察：在成功攻击下，代理的下一步行动将更多依赖恶意任务，而非用户任务。基于此，我们设计了MELON，通过使用屏蔽函数修改用户提示，重新执行代理轨迹来检测攻击。若原始执行与屏蔽执行生成的动作相似，则判定为攻击。我们还引入了三个关键设计，以减少潜在的误报和漏报。在IPI基准测试AgentDojo上的广泛评估表明，MELON在攻击防御和功能保留方面均优于现有最优防御方法。此外，我们将MELON与现有最优提示增强防御相结合（记为MELON-Aug），进一步提升了性能。我们还进行了详细的消融研究，以验证我们的关键设计。


> Recent research has explored that LLM agents are vulnerable to indirect prompt injection (IPI) attacks, where malicious tasks embedded in tool-retrieved information can redirect the agent to take unauthorized actions. Existing defenses against IPI have significant limitations: either require essential model training resources, lack effectiveness against sophisticated attacks, or harm the normal utilities. We present MELON (Masked re-Execution and TooL comparisON), a novel IPI defense. Our approach builds on the observation that under a successful attack, the agent's next action becomes less dependent on user tasks and more on malicious tasks. Following this, we design MELON to detect attacks by re-executing the agent's trajectory with a masked user prompt modified through a masking function. We identify an attack if the actions generated in the original and masked executions are similar. We also include three key designs to reduce the potential false positives and false negatives. Extensive evaluation on the IPI benchmark AgentDojo demonstrates that MELON outperforms SOTA defenses in both attack prevention and utility preservation. Moreover, we show that combining MELON with a SOTA prompt augmentation defense (denoted as MELON-Aug) further improves its performance. We also conduct a detailed ablation study to validate our key designs.

[Arxiv](https://arxiv.org/abs/2502.05174)