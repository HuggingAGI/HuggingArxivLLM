# HermesFlow：无缝填补多模态理解和生成之间的差距

发布时间：2025年02月17日

`LLM应用` `多模态模型`

> HermesFlow: Seamlessly Closing the Gap in Multimodal Understanding and Generation

# 摘要

> 自回归范式的成功在多模态大语言模型领域取得了显著进展，Show-o、Transfusion和Emu3等强大模型在统一图像理解和生成方面表现突出。我们首次发现：多模态大语言模型的理解能力普遍优于生成能力，且两者存在显著差距。为此，我们提出HermesFlow——一个简单而通用的框架，旨在无缝连接多模态大语言模型中的理解和生成能力。具体来说，我们以同源数据为输入，整理出涵盖理解和生成的同源偏好数据。通过Pair-DPO和自我对弈的迭代优化，HermesFlow利用同源偏好数据有效对齐多模态理解和生成能力。实验结果表明，相较于先前方法，我们的方法具有显著优势，尤其是在缩小多模态理解和生成之间的差距方面。这些发现凸显了HermesFlow作为下一代多模态基础模型通用对齐框架的潜力。代码：https://github.com/Gen-Verse/HermesFlow

> The remarkable success of the autoregressive paradigm has made significant advancement in Multimodal Large Language Models (MLLMs), with powerful models like Show-o, Transfusion and Emu3 achieving notable progress in unified image understanding and generation. For the first time, we uncover a common phenomenon: the understanding capabilities of MLLMs are typically stronger than their generative capabilities, with a significant gap between the two. Building on this insight, we propose HermesFlow, a simple yet general framework designed to seamlessly bridge the gap between understanding and generation in MLLMs. Specifically, we take the homologous data as input to curate homologous preference data of both understanding and generation. Through Pair-DPO and self-play iterative optimization, HermesFlow effectively aligns multimodal understanding and generation using homologous preference data. Extensive experiments demonstrate the significant superiority of our approach over prior methods, particularly in narrowing the gap between multimodal understanding and generation. These findings highlight the potential of HermesFlow as a general alignment framework for next-generation multimodal foundation models. Code: https://github.com/Gen-Verse/HermesFlow

[Arxiv](https://arxiv.org/abs/2502.12148)