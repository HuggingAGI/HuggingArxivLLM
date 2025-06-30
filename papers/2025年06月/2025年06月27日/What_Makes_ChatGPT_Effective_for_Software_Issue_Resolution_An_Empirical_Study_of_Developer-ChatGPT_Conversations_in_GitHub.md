# ChatGPT在软件问题解决中为何如此有效？基于GitHub开发者与ChatGPT对话的经验研究

发布时间：2025年06月27日

`LLM应用

分类理由：这篇论文探讨了对话式大型语言模型（如ChatGPT）在问题解决任务中的应用效果，分析了哪些对话有助于解决问题，并识别了无帮助回复的缺陷。研究结果对优化LLM在问题解决中的应用具有指导意义，属于LLM的应用研究。` `开发者工具` `问题解决`

> What Makes ChatGPT Effective for Software Issue Resolution? An Empirical Study of Developer-ChatGPT Conversations in GitHub

# 摘要

> 对话式大型语言模型在问题解决任务中应用广泛，但并非所有开发者与LLM的对话都对有效解决问题有帮助。本文分析了GitHub问题线程中共享的686段开发者与ChatGPT的对话，旨在识别使这些对话有效解决问题的特征。

首先，我们分析了对话及其对应的问题，区分了有帮助和无帮助的对话。我们从分类开发者寻求帮助的任务类型入手，以更好地理解ChatGPT最有效的场景。接着，我们考察了对话、项目和问题相关的广泛指标，揭示了与有帮助对话相关的因素。最后，我们识别了无帮助ChatGPT回复中的常见缺陷，以突出可能影响更有效开发者工具设计的领域。

研究发现，仅62%的ChatGPT对话对成功解决问题有帮助。ChatGPT在代码生成和工具/库/API推荐方面表现最佳，但在代码解释方面存在困难。有帮助的对话通常更简短、更易读，并且在语义和语言上表现出更强的一致性。规模更大、更受欢迎的项目和经验更丰富的开发者更能从ChatGPT中受益。在问题层面，ChatGPT在解决开发者活动较少、解决速度较快的简单问题上表现最佳，通常是一些界定明确的任务，如编译错误。

无帮助的ChatGPT回复中最常见的缺陷包括提供错误信息和缺乏全面性。我们的发现具有广泛影响，包括指导开发者在问题解决中采用有效交互策略、为支持最佳提示设计的工具或框架开发提供信息，以及为优化LLM用于问题解决任务提供见解。

> Conversational large-language models are extensively used for issue resolution tasks. However, not all developer-LLM conversations are useful for effective issue resolution. In this paper, we analyze 686 developer-ChatGPT conversations shared within GitHub issue threads to identify characteristics that make these conversations effective for issue resolution. First, we analyze the conversations and their corresponding issues to distinguish helpful from unhelpful conversations. We begin by categorizing the types of tasks developers seek help with to better understand the scenarios in which ChatGPT is most effective. Next, we examine a wide range of conversational, project, and issue-related metrics to uncover factors associated with helpful conversations. Finally, we identify common deficiencies in unhelpful ChatGPT responses to highlight areas that could inform the design of more effective developer-facing tools. We found that only 62% of the ChatGPT conversations were helpful for successful issue resolution. ChatGPT is most effective for code generation and tools/libraries/APIs recommendations, but struggles with code explanations. Helpful conversations tend to be shorter, more readable, and exhibit stronger semantic and linguistic alignment. Larger, more popular projects and more experienced developers benefit more from ChatGPT. At the issue level, ChatGPT performs best on simpler problems with limited developer activity and faster resolution, typically well-scoped tasks like compilation errors. The most common deficiencies in unhelpful ChatGPT responses include incorrect information and lack of comprehensiveness. Our findings have wide implications including guiding developers on effective interaction strategies for issue resolution, informing the development of tools or frameworks to support optimal prompt design, and providing insights on fine-tuning LLMs for issue resolution tasks.

[Arxiv](https://arxiv.org/abs/2506.22390)