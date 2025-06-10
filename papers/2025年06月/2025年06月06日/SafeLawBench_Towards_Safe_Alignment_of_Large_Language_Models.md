# # SafeLawBench：致力于大型语言模型的安全对齐

发布时间：2025年06月06日

`LLM理论` `法律合规`

> SafeLawBench: Towards Safe Alignment of Large Language Models

# 摘要

> 大型语言模型（LLMs）的广泛应用引发了对其安全性的高度重视，但受限于现有安全基准的主观性，目前仍缺乏明确的安全性评估标准。为填补这一空白，我们从法律角度出发，首次提出了SafeLawBench基准。该基准基于法律标准将安全风险划分为三个等级，构建了一个系统化、全面化的评估框架。它包含24,860道多选题和1,106个开放领域问答任务。我们通过零-shot和少-shot提示方法，对2个闭源LLMs和18个开源LLMs进行了评估，凸显了各模型的安全特性。同时，我们还考察了LLMs在安全相关推理稳定性和拒绝行为方面的表现。此外，研究发现多数投票机制能够有效提升模型性能。值得注意的是，即便Claude-3.5-Sonnet和GPT-4o等顶尖SOTA模型，在SafeLawBench的多选任务中准确率也未突破80.5%，而20个LLMs的平均准确率仅为68.8%。我们呼吁研究社区优先关注并深入研究LLMs的安全性问题。

> With the growing prevalence of large language models (LLMs), the safety of LLMs has raised significant concerns. However, there is still a lack of definitive standards for evaluating their safety due to the subjective nature of current safety benchmarks. To address this gap, we conducted the first exploration of LLMs' safety evaluation from a legal perspective by proposing the SafeLawBench benchmark. SafeLawBench categorizes safety risks into three levels based on legal standards, providing a systematic and comprehensive framework for evaluation. It comprises 24,860 multi-choice questions and 1,106 open-domain question-answering (QA) tasks. Our evaluation included 2 closed-source LLMs and 18 open-source LLMs using zero-shot and few-shot prompting, highlighting the safety features of each model. We also evaluated the LLMs' safety-related reasoning stability and refusal behavior. Additionally, we found that a majority voting mechanism can enhance model performance. Notably, even leading SOTA models like Claude-3.5-Sonnet and GPT-4o have not exceeded 80.5% accuracy in multi-choice tasks on SafeLawBench, while the average accuracy of 20 LLMs remains at 68.8\%. We urge the community to prioritize research on the safety of LLMs.

[Arxiv](https://arxiv.org/abs/2506.06636)