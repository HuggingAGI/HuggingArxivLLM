# ProfiLLM：基于大语言模型的聊天机器人用户隐式画像框架

发布时间：2025年06月16日

`LLM应用` `IT/网络安全` `聊天机器人`

> ProfiLLM: An LLM-Based Framework for Implicit Profiling of Chatbot Users

# 摘要

> 尽管对话式AI取得了显著进展，但大型语言模型（LLM）驱动的聊天机器人在个性化响应方面仍面临挑战，尤其在IT/网络安全（ITSec）等专业知识密集型领域，用户知识水平差异较大，个性化不足问题尤为突出。现有方法主要依赖静态用户分类或显式自我报告信息，限制了其对用户熟练程度的动态感知能力。本文提出ProfiLLM，一个通过聊天机器人交互实现隐式动态用户画像的新框架。该框架包含可跨领域适应的分类法，以及基于LLM的用户画像方法。我们在ITSec领域进行了应用，利用故障排除交互推断聊天机器人用户的技术熟练程度。具体而言，我们开发了ProfiLLM[ITSec]，并在263个合成用户的1,760段类人聊天对话中评估其性能。结果显示，ProfiLLM[ITSec]能够快速准确地推断ITSec画像，单次提示后将实际与预测分数之间的差距缩小了55-65%，随后仅有小幅波动和进一步优化。除了评估我们的新隐式动态画像框架，我们还提出了一种基于LLM的人设模拟方法、ITSec熟练程度的结构化分类法、代码库以及聊天机器人交互数据集，以支持未来研究。

> Despite significant advancements in conversational AI, large language model (LLM)-powered chatbots often struggle with personalizing their responses according to individual user characteristics, such as technical expertise, learning style, and communication preferences. This lack of personalization is particularly problematic in specialized knowledge-intense domains like IT/cybersecurity (ITSec), where user knowledge levels vary widely. Existing approaches for chatbot personalization primarily rely on static user categories or explicit self-reported information, limiting their adaptability to an evolving perception of the user's proficiency, obtained in the course of ongoing interactions. In this paper, we propose ProfiLLM, a novel framework for implicit and dynamic user profiling through chatbot interactions. This framework consists of a taxonomy that can be adapted for use in diverse domains and an LLM-based method for user profiling in terms of the taxonomy. To demonstrate ProfiLLM's effectiveness, we apply it in the ITSec domain where troubleshooting interactions are used to infer chatbot users' technical proficiency. Specifically, we developed ProfiLLM[ITSec], an ITSec-adapted variant of ProfiLLM, and evaluated its performance on 1,760 human-like chatbot conversations from 263 synthetic users. Results show that ProfiLLM[ITSec] rapidly and accurately infers ITSec profiles, reducing the gap between actual and predicted scores by up to 55--65\% after a single prompt, followed by minor fluctuations and further refinement. In addition to evaluating our new implicit and dynamic profiling framework, we also propose an LLM-based persona simulation methodology, a structured taxonomy for ITSec proficiency, our codebase, and a dataset of chatbot interactions to support future research.

[Arxiv](https://arxiv.org/abs/2506.13980)