# LongSafety：评估大型语言模型在长上下文中的安全性表现

发布时间：2025年02月24日

`LLM应用` `人工智能安全` `基准测试`

> LongSafety: Evaluating Long-Context Safety of Large Language Models

# 摘要

> # 摘要
随着大型语言模型（LLMs）在理解和生成长序列方面不断进步，长上下文引入了新的安全问题。然而，LLMs在长上下文任务中的安全性研究仍然不足，导致在安全性的评估与提升方面存在重大空白。为了解决这一问题，我们引入了LongSafety，这是首个专门用于评估LLMs在开放性长上下文任务中安全性的综合基准测试。

LongSafety涵盖了7类安全问题，并设计了6种用户导向的长上下文任务，总共包含1,543个测试用例，每个上下文平均长度为5,424个单词。我们对16个代表性LLMs的评估结果显示，大多数模型的安全率低于55%。我们的研究还表明，短上下文场景中的强安全性能并不一定与长上下文任务的安全性相关，突显了长上下文安全改进的独特挑战和紧迫性。

此外，通过深入分析，我们识别出长上下文模型面临的安全问题和任务类型。更重要的是，我们发现相关上下文和扩展输入序列在长上下文场景中会加剧安全风险，强调了持续关注长上下文安全挑战的重要性。我们的代码和数据可在https://github.com/thu-coai/LongSafety获取。

> As Large Language Models (LLMs) continue to advance in understanding and generating long sequences, new safety concerns have been introduced through the long context. However, the safety of LLMs in long-context tasks remains under-explored, leaving a significant gap in both evaluation and improvement of their safety. To address this, we introduce LongSafety, the first comprehensive benchmark specifically designed to evaluate LLM safety in open-ended long-context tasks. LongSafety encompasses 7 categories of safety issues and 6 user-oriented long-context tasks, with a total of 1,543 test cases, averaging 5,424 words per context. Our evaluation towards 16 representative LLMs reveals significant safety vulnerabilities, with most models achieving safety rates below 55%. Our findings also indicate that strong safety performance in short-context scenarios does not necessarily correlate with safety in long-context tasks, emphasizing the unique challenges and urgency of improving long-context safety. Moreover, through extensive analysis, we identify challenging safety issues and task types for long-context models. Furthermore, we find that relevant context and extended input sequences can exacerbate safety risks in long-context scenarios, highlighting the critical need for ongoing attention to long-context safety challenges. Our code and data are available at https://github.com/thu-coai/LongSafety.

[Arxiv](https://arxiv.org/abs/2502.16971)