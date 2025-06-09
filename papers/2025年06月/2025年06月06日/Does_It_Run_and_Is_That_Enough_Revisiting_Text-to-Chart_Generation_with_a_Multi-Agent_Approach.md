# 它能运行，这就足够了吗？多智能体方法重新审视文本到图表生成

发布时间：2025年06月06日

`Agent

这篇论文主要探讨了多智能体管道在解决图表生成问题中的应用，通过分离不同的任务模块，利用现有模型提升执行效率和减少错误率，属于智能体协作的应用研究。` `数据可视化` `人机交互`

> Does It Run and Is That Enough? Revisiting Text-to-Chart Generation with a Multi-Agent Approach

# 摘要

> 大型语言模型能够将自然语言的图表描述转化为可执行代码，但即使经过监督微调和强化学习，仍有约15%的生成脚本无法执行。我们研究这种顽固的错误率是否源于模型本身的限制，还是由于依赖单一提示设计。为探索这一问题，我们提出了一种轻量级的多智能体管道，将草稿、执行、修复和判断分离，仅使用现成的GPT-4o-mini模型。在	extsc{Text2Chart31}基准测试中，我们的系统在三次修复迭代内将执行错误率降至4.5%，优于最强的微调基线近5个百分点，同时计算需求大幅减少。在	extsc{ChartX}基准测试中也观察到类似的表现，错误率为4.6%，显示出强大的泛化能力。在现有基准下，执行成功率已基本解决。然而，人工审查发现，100个采样图表中有6个包含幻觉，而基于LLM的可访问性审核显示，仅33.3%（	extsc{Text2Chart31}）和7.2%（	extsc{ChartX}）的生成图表满足基本色盲指南。这些发现表明，未来工作应将重点从执行可靠性转向提高图表美观度、语义保真度和可访问性。

> Large language models can translate natural-language chart descriptions into runnable code, yet approximately 15\% of the generated scripts still fail to execute, even after supervised fine-tuning and reinforcement learning. We investigate whether this persistent error rate stems from model limitations or from reliance on a single-prompt design. To explore this, we propose a lightweight multi-agent pipeline that separates drafting, execution, repair, and judgment, using only an off-the-shelf GPT-4o-mini model. On the \textsc{Text2Chart31} benchmark, our system reduces execution errors to 4.5\% within three repair iterations, outperforming the strongest fine-tuned baseline by nearly 5 percentage points while requiring significantly less compute. Similar performance is observed on the \textsc{ChartX} benchmark, with an error rate of 4.6\%, demonstrating strong generalization. Under current benchmarks, execution success appears largely solved. However, manual review reveals that 6 out of 100 sampled charts contain hallucinations, and an LLM-based accessibility audit shows that only 33.3\% (\textsc{Text2Chart31}) and 7.2\% (\textsc{ChartX}) of generated charts satisfy basic colorblindness guidelines. These findings suggest that future work should shift focus from execution reliability toward improving chart aesthetics, semantic fidelity, and accessibility.

[Arxiv](https://arxiv.org/abs/2506.06175)