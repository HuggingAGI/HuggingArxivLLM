# ReSum：借助上下文摘要解锁长程搜索智能

发布时间：2025年09月16日

`Agent` `基础理论`

> ReSum: Unlocking Long-Horizon Search Intelligence via Context Summarization

# 摘要

> 基于大型语言模型（LLM）的网络智能体在知识密集型任务上表现卓越，但在ReAct等范式中受限于上下文窗口大小。涉及多实体、复杂关系和高度不确定性的复杂查询需要大量搜索步骤，往往在得出完整答案前就耗尽了上下文预算。为解决这一难题，我们提出ReSum——一种通过周期性上下文总结实现无限探索的全新范式。ReSum能将不断累积的交互历史转化为紧凑的推理状态，在突破上下文限制的同时，始终掌握先前的发现。为适配该范式，我们设计了ReSum-GRPO，将GRPO与分段轨迹训练、优势广播相结合，帮助智能体适应基于总结的推理模式。在三个基准测试中对不同规模网络智能体的大量实验表明，ReSum相比ReAct平均绝对提升4.5%，经过ReSum-GRPO训练后，性能更是进一步提升高达8.2%。值得关注的是，仅用1K训练样本，我们的WebResummer-30B（基于WebSailor-30B的ReSum-GRPO训练版本）在BrowseComp-zh数据集上的Pass@1达到33.3%，在BrowseComp-en上达到18.3%，性能超越了现有开源网络智能体。

> Large Language Model (LLM)-based web agents demonstrate strong performance on knowledge-intensive tasks but are hindered by context window limitations in paradigms like ReAct. Complex queries involving multiple entities, intertwined relationships, and high uncertainty demand extensive search cycles that rapidly exhaust context budgets before reaching complete solutions. To overcome this challenge, we introduce ReSum, a novel paradigm that enables indefinite exploration through periodic context summarization. ReSum converts growing interaction histories into compact reasoning states, maintaining awareness of prior discoveries while bypassing context constraints. For paradigm adaptation, we propose ReSum-GRPO, integrating GRPO with segmented trajectory training and advantage broadcasting to familiarize agents with summary-conditioned reasoning. Extensive experiments on web agents of varying scales across three benchmarks demonstrate that ReSum delivers an average absolute improvement of 4.5\% over ReAct, with further gains of up to 8.2\% following ReSum-GRPO training. Notably, with only 1K training samples, our WebResummer-30B (a ReSum-GRPO-trained version of WebSailor-30B) achieves 33.3\% Pass@1 on BrowseComp-zh and 18.3\% on BrowseComp-en, surpassing existing open-source web agents.

[Arxiv](https://arxiv.org/abs/2509.13313)