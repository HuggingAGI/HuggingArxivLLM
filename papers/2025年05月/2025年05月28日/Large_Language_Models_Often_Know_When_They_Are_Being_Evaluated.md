# 大型语言模型往往心知肚明，知道自己正处于评估之中

发布时间：2025年05月28日

`LLM理论` `人工智能`

> Large Language Models Often Know When They Are Being Evaluated

# 摘要

> 如果AI模型能够察觉自己正在接受评估，评估的有效性可能会大打折扣。例如，模型在评估过程中可能会表现出系统性不同的行为，导致用于部署和治理决策的基准可靠性降低。我们研究前沿语言模型是否能够准确判断文本记录是否来自评估而非真实世界部署，我们将这一能力称为评估感知能力。为此，我们构建了一个包含1,000个提示和文本记录的多样化基准，这些数据来自61个不同的数据集，涵盖公开基准（如MMLU、SWEBench）、真实世界部署交互以及来自脚手架框架（如网络浏览代理）的代理轨迹。前沿模型明显展现出超越随机水平的评估感知能力（Gemini-2.5-Pro的AUC达到$0.83$），但尚未超越我们的简单人工基线（AUC为$0.92$）。此外，无论是AI模型还是人类，在智能体场景下识别评估的能力均优于聊天场景。另外，我们测试了模型是否能够识别评估的目的。在多项选择和开放性问题中，AI模型在识别评估测试内容方面远超随机猜测水平。我们的研究结果表明，前沿模型已经展现出显著的、尽管尚未超越人类水平的评估感知能力。我们建议在未来模型开发中持续跟踪这一能力。

> If AI models can detect when they are being evaluated, the effectiveness of evaluations might be compromised. For example, models could have systematically different behavior during evaluations, leading to less reliable benchmarks for deployment and governance decisions. We investigate whether frontier language models can accurately classify transcripts based on whether they originate from evaluations or real-world deployment, a capability we call evaluation awareness. To achieve this, we construct a diverse benchmark of 1,000 prompts and transcripts from 61 distinct datasets. These span public benchmarks (e.g., MMLU, SWEBench), real-world deployment interactions, and agent trajectories from scaffolding frameworks (e.g., web-browsing agents). Frontier models clearly demonstrate above-random evaluation awareness (Gemini-2.5-Pro reaches an AUC of $0.83$), but do not yet surpass our simple human baseline (AUC of $0.92$). Furthermore, both AI models and humans are better at identifying evaluations in agentic settings compared to chat settings. Additionally, we test whether models can identify the purpose of the evaluation. Under multiple-choice and open-ended questioning, AI models far outperform random chance in identifying what an evaluation is testing for. Our results indicate that frontier models already exhibit a substantial, though not yet superhuman, level of evaluation-awareness. We recommend tracking this capability in future models.

[Arxiv](https://arxiv.org/abs/2505.23836)