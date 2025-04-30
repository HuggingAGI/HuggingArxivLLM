# BrAIcht，一个戏剧化的智能体，能够像贝托尔特·布莱希特的角色一样说话。

发布时间：2025年04月29日

`LLM应用` `AI对话`

> BrAIcht, a theatrical agent that speaks like Bertolt Brecht's characters

# 摘要

> 本项目推出了一款名为 BrAIcht 的 AI 对话代理，它能够以著名德国剧作家 Bertolt Brecht 的独特风格创作对话。BrAIcht 基于拥有 70 亿参数的大型语言模型德国 LeoLM，该模型是在经过优化以适应德语任务的 Llama2 基础模型上构建的。微调过程中，我们采用了 Bertolt Brecht 的 29 部戏剧以及 907 部其他与 Bertolt Brecht 风格相似的德语戏剧，构建了一个更加多样化的训练数据集。受限于内存容量，我们采用了名为 QLoRA 的参数高效微调技术来训练大型语言模型。实验结果表明，BrAIcht 在以 Bertolt Brecht 风格生成对话方面表现出色，这一结论得到了 BLEU 分数和困惑度的双重验证。

> This project introduces BrAIcht, an AI conversational agent that creates dialogues in the distinctive style of the famous German playwright Bertolt Brecht. BrAIcht is fine-tuned using German LeoLM, a large language model with 7 billion parameters and a modified version of the base Llama2 suitable for German language tasks. For fine-tuning, 29 plays of Bertolt Brecht and 907 of other German plays that are stylistically similar to Bertolt Brecht are used to form a more di-erse dataset. Due to the limited memory capacity, a parameterefficient fine-tuning technique called QLoRA is implemented to train the large language model. The results, based on BLEU score and perplexity, show very promising performance of BrAIcht in generating dialogues in the style of Bertolt Brecht.

[Arxiv](https://arxiv.org/abs/2504.20552)