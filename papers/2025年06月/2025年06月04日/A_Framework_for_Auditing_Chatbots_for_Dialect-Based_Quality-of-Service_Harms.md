# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月04日

`LLM应用` `客户服务` `聊天机器人`

> A Framework for Auditing Chatbots for Dialect-Based Quality-of-Service Harms

# 摘要

> 如今，越来越多的在线活动参与者会与基于大型语言模型（LLM）的聊天机器人互动。先前研究表明，LLMs 可能存在方言偏见，即当提示文本使用少数群体方言时，模型可能生成有害回应。然而，这种偏见是否以及如何影响基于 LLM 的系统（如聊天机器人）仍不明确。我们回顾了现有用于审查 LLM 方言偏见的方法，发现这些方法因实质性和生态效度问题，无法直接应用于审查基于 LLM 的聊天机器人。为解决这一问题，我们提出了一种框架，通过衡量聊天机器人在多大程度上产生服务质量损害（即系统对不同人群并非同等有效时）来审查其方言偏见。我们的框架具有以下三个关键特性，使其在实践中具有实用价值：首先，通过利用动态生成的文本而非现成文本，我们的框架能够测试任何方言，支持多轮对话，并代表用户在现实世界中与聊天机器人互动的方式。其次，通过衡量服务质量损害，我们的框架将审查结果与聊天机器人使用的真实世界结果相一致。第三，我们的框架只需对基于 LLM 的聊天机器人进行查询访问，这意味着它可以被内部审计人员、外部审计人员甚至个人用户同等有效地利用，以促进问责。为了展示我们框架的有效性，我们对 Amazon Rufus 进行了案例研究审计，这是一个在客户服务领域广泛使用的基于 LLM 的聊天机器人。我们的结果显示，Rufus 对用少数群体英语方言编写的提示产生质量较低的回应，并且这些服务质量损害因提示中存在拼写错误而加剧。

> Increasingly, individuals who engage in online activities are expected to interact with large language model (LLM)-based chatbots. Prior work has shown that LLMs can display dialect bias, which occurs when they produce harmful responses when prompted with text written in minoritized dialects. However, whether and how this bias propagates to systems built on top of LLMs, such as chatbots, is still unclear. We conduct a review of existing approaches for auditing LLMs for dialect bias and show that they cannot be straightforwardly adapted to audit LLM-based chatbots due to issues of substantive and ecological validity. To address this, we present a framework for auditing LLM-based chatbots for dialect bias by measuring the extent to which they produce quality-of-service harms, which occur when systems do not work equally well for different people. Our framework has three key characteristics that make it useful in practice. First, by leveraging dynamically generated instead of pre-existing text, our framework enables testing over any dialect, facilitates multi-turn conversations, and represents how users are likely to interact with chatbots in the real world. Second, by measuring quality-of-service harms, our framework aligns audit results with the real-world outcomes of chatbot use. Third, our framework requires only query access to an LLM-based chatbot, meaning that it can be leveraged equally effectively by internal auditors, external auditors, and even individual users in order to promote accountability. To demonstrate the efficacy of our framework, we conduct a case study audit of Amazon Rufus, a widely-used LLM-based chatbot in the customer service domain. Our results reveal that Rufus produces lower-quality responses to prompts written in minoritized English dialects, and that these quality-of-service harms are exacerbated by the presence of typos in prompts.

[Arxiv](https://arxiv.org/abs/2506.04419)