# # 探索指令调整对大型语言模型易受错误信息影响的作用
研究指令调整对大型语言模型对错误信息的易感性的影响

发布时间：2025年07月24日

`LLM应用` `人工智能`

> Exploring the Impact of Instruction-Tuning on LLM's Susceptibility to Misinformation

# 摘要

> 指令微调让大型语言模型（LLMs）更精准地执行用户指令，既提升了模型的实用性，又减少了有害输出。然而，这一过程可能增加模型对用户输入的依赖性，导致模型不加筛选地接受误导信息，甚至生成幻觉内容。现有研究表明，LLMs容易接受与自身参数知识相矛盾的外部信息，但关于指令微调对这一现象的直接影响的研究却很少。本研究聚焦于指令微调对LLMs接受误导信息的影响。分析发现，指令微调后的LLMs在面对用户提供的误导信息时，接受的可能性显著增加。与基础模型的对比显示，指令微调使模型更依赖用户提供的信息，易受误导的角色从模型本身转向了用户。此外，我们还研究了其他影响误导信息接受程度的因素，包括提示结构中用户角色的作用、误导信息的长度以及系统提示中是否存在警告信息。研究结果强调了采取系统性方法来减轻指令微调的意外后果、提升LLMs在实际应用中可靠性的必要性。


> Instruction-tuning enhances the ability of large language models (LLMs) to follow user instructions more accurately, improving usability while reducing harmful outputs. However, this process may increase the model's dependence on user input, potentially leading to the unfiltered acceptance of misinformation and the generation of hallucinations. Existing studies primarily highlight that LLMs are receptive to external information that contradict their parametric knowledge, but little research has been conducted on the direct impact of instruction-tuning on this phenomenon. In our study, we investigate the impact of instruction-tuning on LLM's susceptibility to misinformation. Our analysis reveals that instruction-tuned LLMs are significantly more likely to accept misinformation when it is presented by the user. A comparison with base models shows that instruction-tuning increases reliance on user-provided information, shifting susceptibility from the assistant role to the user role. Furthermore, we explore additional factors influencing misinformation susceptibility, such as the role of the user in prompt structure, misinformation length, and the presence of warnings in the system prompt. Our findings underscore the need for systematic approaches to mitigate unintended consequences of instruction-tuning and enhance the reliability of LLMs in real-world applications.

[Arxiv](https://arxiv.org/abs/2507.18203)