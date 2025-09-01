# Morae：主动暂停UI智能体供用户选择

发布时间：2025年08月29日

`Agent` `零售与电商`

> Morae: Proactively Pausing UI Agents for User Choices

# 摘要

> 用户界面（UI）智能体有望帮助盲人和低视力（BLV）用户更轻松地使用原本难以访问或复杂的界面。然而，目前的UI智能体往往端到端执行任务，既不让用户参与关键决策，也不告知他们重要的上下文信息，这削弱了用户的自主性。例如，在我们的实地研究中，一位BLV参与者要求购买最便宜的气泡水，智能体却在多个同价选项中自动选定了一款，完全没有提及其他不同口味或评分更高的替代产品。为解决这一问题，我们研发了Morae——一种能在任务执行时自动识别决策点并暂停，让用户自主选择的UI智能体。Morae借助大型多模态模型，结合UI代码与截图解读用户指令，并在需要做选择时主动提示用户确认。在针对BLV参与者的真实网络任务研究中，与包括OpenAI Operator在内的基准智能体相比，Morae帮助用户完成了更多任务，且所选选项更贴合他们的个人偏好。更重要的是，这项研究展示了一种“混合主动式”交互模式——用户既能享受UI智能体的自动化便利，又能充分表达自己的偏好。

> User interface (UI) agents promise to make inaccessible or complex UIs easier to access for blind and low-vision (BLV) users. However, current UI agents typically perform tasks end-to-end without involving users in critical choices or making them aware of important contextual information, thus reducing user agency. For example, in our field study, a BLV participant asked to buy the cheapest available sparkling water, and the agent automatically chose one from several equally priced options, without mentioning alternative products with different flavors or better ratings. To address this problem, we introduce Morae, a UI agent that automatically identifies decision points during task execution and pauses so that users can make choices. Morae uses large multimodal models to interpret user queries alongside UI code and screenshots, and prompt users for clarification when there is a choice to be made. In a study over real-world web tasks with BLV participants, Morae helped users complete more tasks and select options that better matched their preferences, as compared to baseline agents, including OpenAI Operator. More broadly, this work exemplifies a mixed-initiative approach in which users benefit from the automation of UI agents while being able to express their preferences.

[Arxiv](https://arxiv.org/abs/2508.21456)