# 红队测试多模态语言模型：评估跨提示模态与模型的危害

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Red Teaming Multimodal Language Models: Evaluating Harm Across Prompt Modalities and Models

# 摘要

> 多模态大型语言模型（MLLMs）在现实应用中日益普及，但在对抗性环境下的安全性研究仍显不足。本研究针对四种主流MLLMs（GPT-4o、Claude Sonnet 3.5、Pixtral 12B和Qwen VL Plus），在纯文本和多模态两种格式的对抗性提示下评估其无害性表现。26名红队成员组成的团队生成了726条提示，针对非法活动、虚假信息和不道德行为三大危害类别。研究团队将这些提示提交给每个模型，随后17名标注员采用5分制对2904份模型输出的有害性进行评分。结果表明，不同模型和模态的脆弱性差异显著：其中Pixtral 12B的有害响应率最高（约62%），Claude Sonnet 3.5则抵抗力最强（约10%）。与预期相悖的是，纯文本提示在绕过安全机制方面比多模态提示略胜一筹。统计分析证实，模型类型和输入模态均是有害性的显著预测因素。这些发现凸显，随着MLLMs的广泛部署，亟需建立稳健的多模态安全基准。

> Multimodal large language models (MLLMs) are increasingly used in real world applications, yet their safety under adversarial conditions remains underexplored. This study evaluates the harmlessness of four leading MLLMs (GPT-4o, Claude Sonnet 3.5, Pixtral 12B, and Qwen VL Plus) when exposed to adversarial prompts across text-only and multimodal formats. A team of 26 red teamers generated 726 prompts targeting three harm categories: illegal activity, disinformation, and unethical behaviour. These prompts were submitted to each model, and 17 annotators rated 2,904 model outputs for harmfulness using a 5-point scale. Results show significant differences in vulnerability across models and modalities. Pixtral 12B exhibited the highest rate of harmful responses (~62%), while Claude Sonnet 3.5 was the most resistant (~10%). Contrary to expectations, text-only prompts were slightly more effective at bypassing safety mechanisms than multimodal ones. Statistical analysis confirmed that both model type and input modality were significant predictors of harmfulness. These findings underscore the urgent need for robust, multimodal safety benchmarks as MLLMs are deployed more widely.

[Arxiv](https://arxiv.org/abs/2509.15478)