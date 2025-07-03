# 上下文感知的代码连线推荐，基于LLM的智能体

发布时间：2025年07月01日

`RAG` `软件开发` `代码分析`

> Context-Aware Code Wiring Recommendation with LLM-based Agent

# 摘要

> 复制-粘贴-修改是软件开发中广泛采用的实用做法，开发人员会将从Stack Overflow、GitHub或LLM输出等平台获取的代码片段，适应性地整合到本地代码库中。在这个过程中，一个关键但尚未充分探索的方面是代码连线（code wiring），即用周围上下文中合适的变量替换粘贴代码中未解析的变量。现有解决方案主要依赖启发式规则或历史模板，往往未能有效利用上下文信息，尽管研究表明，超过一半的适应案例都与上下文相关。

本文中，我们引入了WIRL，这是一种基于LLM的代码连线代理，将其作为检索增强生成（RAG）填充任务来实现。WIRL结合了LLM、定制工具包和编排模块，用于识别未解析变量、检索上下文并执行上下文感知的替换。为了在效率和自主性之间取得平衡，该代理采用了一种混合策略：对常见模式使用确定性的基于规则的步骤，以及由状态机引导的决策过程进行智能探索。

我们在一个精心策划的高质量数据集上对WIRL进行了评估，该数据集包含真实的代码适应场景。我们的方法实现了91.7%的精确匹配准确率和90.0%的召回率，在准确率和召回率上分别比先进的LLMs高出22.6和13.7个百分点，比IntelliJ IDEA高出54.3和49.9个百分点。这些结果凸显了WIRL在涉及复杂变量依赖或多个未解析变量的上下文中的实用价值。我们相信，WIRL为现代IDE中更智能、更上下文感知的开发人员辅助工具铺平了道路。

> Copy-paste-modify is a widespread and pragmatic practice in software development, where developers adapt reused code snippets, sourced from platforms such as Stack Overflow, GitHub, or LLM outputs, into their local codebase. A critical yet underexplored aspect of this adaptation is code wiring, which involves substituting unresolved variables in the pasted code with suitable ones from the surrounding context. Existing solutions either rely on heuristic rules or historical templates, often failing to effectively utilize contextual information, despite studies showing that over half of adaptation cases are context-dependent. In this paper, we introduce WIRL, an LLM-based agent for code wiring framed as a Retrieval-Augmented Generation (RAG) infilling task. WIRL combines an LLM, a customized toolkit, and an orchestration module to identify unresolved variables, retrieve context, and perform context-aware substitutions. To balance efficiency and autonomy, the agent adopts a mixed strategy: deterministic rule-based steps for common patterns, and a state-machine-guided decision process for intelligent exploration. We evaluate WIRL on a carefully curated, high-quality dataset consisting of real-world code adaptation scenarios. Our approach achieves an exact match precision of 91.7% and a recall of 90.0%, outperforming advanced LLMs by 22.6 and 13.7 percentage points in precision and recall, respectively, and surpassing IntelliJ IDEA by 54.3 and 49.9 percentage points. These results underscore its practical utility, particularly in contexts with complex variable dependencies or multiple unresolved variables. We believe WIRL paves the way for more intelligent and context-aware developer assistance in modern IDEs.

[Arxiv](https://arxiv.org/abs/2507.01315)