# CarMem: 利用类别边界提升LLM语音助手的长期记忆能力

发布时间：2025年01月16日

`Agent

理由：这篇论文描述了一个基于大型语言模型的语音助手系统，该系统能够提取、存储和检索用户偏好，以提升个性化体验。这涉及到智能代理（Agent）的设计和实现，特别是如何通过记忆系统来增强用户交互体验。因此，这篇论文应归类为Agent。` `语音助手` `车载系统`

> CarMem: Enhancing Long-Term Memory in LLM Voice Assistants through Category-Bounding

# 摘要

> 在当今的助手领域，个性化提升了互动体验，促进了长期关系，并加深了用户参与度。然而，许多系统在保留用户偏好方面表现不佳，导致用户请求重复和参与度下降。此外，工业应用中用户偏好的不透明提取引发了隐私和信任的担忧，尤其是在欧洲等法规严格的地区。为此，我们提出了一种基于预定义类别的语音助手长期记忆系统。该系统利用大型语言模型高效提取、存储和检索偏好，确保个性化和透明度。我们还推出了一个基于真实行业数据的合成多轮、多会话对话数据集（CarMem），专为车载语音助手设计。在该数据集上，我们的系统在偏好提取方面的F1得分在0.78到0.95之间，具体取决于类别粒度。维护策略将冗余偏好减少了95%，矛盾偏好减少了92%，最佳检索准确率达到0.87。总体而言，该系统在工业应用中表现出色。

> In today's assistant landscape, personalisation enhances interactions, fosters long-term relationships, and deepens engagement. However, many systems struggle with retaining user preferences, leading to repetitive user requests and disengagement. Furthermore, the unregulated and opaque extraction of user preferences in industry applications raises significant concerns about privacy and trust, especially in regions with stringent regulations like Europe. In response to these challenges, we propose a long-term memory system for voice assistants, structured around predefined categories. This approach leverages Large Language Models to efficiently extract, store, and retrieve preferences within these categories, ensuring both personalisation and transparency. We also introduce a synthetic multi-turn, multi-session conversation dataset (CarMem), grounded in real industry data, tailored to an in-car voice assistant setting. Benchmarked on the dataset, our system achieves an F1-score of .78 to .95 in preference extraction, depending on category granularity. Our maintenance strategy reduces redundant preferences by 95% and contradictory ones by 92%, while the accuracy of optimal retrieval is at .87. Collectively, the results demonstrate the system's suitability for industrial applications.

[Arxiv](https://arxiv.org/abs/2501.09645)