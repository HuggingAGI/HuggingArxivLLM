# 手势GPT：迈向无需示例的自由手勢理解——借助大型语言模型智能体

发布时间：2024年11月03日

`LLM应用

这篇论文探讨了如何利用大型语言模型（LLM）来实现更自然的手势交互界面。通过构建一个多代理框架，GestureGPT，论文展示了LLM在处理和理解自由形式手势中的应用，特别是在智能家居控制和在线视频流等真实场景中的验证。因此，这篇论文属于LLM应用类别。` `交互设计` `用户体验`

> GestureGPT: Toward Zero-Shot Free-Form Hand Gesture Understanding with Large Language Model Agents

# 摘要

> 现有的手势界面仅支持固定的手势集，这些手势由设计者或用户预先定义，导致了学习或演示成本，降低了自然性。人类则通过综合分析手势、情境、经验和常识来理解自由形式的手势。这样，用户无需学习、演示或关联特定手势。我们提出GestureGPT，一个模仿人类手势理解流程的自由形式手势理解框架，旨在实现自然的自由形式手势交互界面。我们的框架利用多个大型语言模型（LLM）代理来管理和综合手势及情境信息，然后通过将手势与界面功能关联来推断交互意图。具体来说，我们的三代理框架包括一个手势描述代理，它能够根据手部关键点坐标自动分割并生成对手势姿势和动作的自然语言描述。该描述由手势推理代理通过自我推理和查询交互情境（如交互历史、 gaze 数据）进行解析，这些情境信息由情境管理代理进行管理。经过迭代交流后，手势推理代理通过将其与交互功能关联来辨别用户的意图。我们在两个真实场景下对我们的框架进行了离线验证：智能家居控制和在线视频流。智能家居任务的平均零样本 Top-1/Top-5 接地准确率分别为 44.79%/83.59%，视频流任务的准确率分别为 37.50%/73.44%。我们还进行了广泛的讨论，包括模型选择的理由、泛化能力以及未来研究方向等，以支持实际系统的开发。

> Existing gesture interfaces only work with a fixed set of gestures defined either by interface designers or by users themselves, which introduces learning or demonstration efforts that diminish their naturalness. Humans, on the other hand, understand free-form gestures by synthesizing the gesture, context, experience, and common sense. In this way, the user does not need to learn, demonstrate, or associate gestures. We introduce GestureGPT, a free-form hand gesture understanding framework that mimics human gesture understanding procedures to enable a natural free-form gestural interface. Our framework leverages multiple Large Language Model agents to manage and synthesize gesture and context information, then infers the interaction intent by associating the gesture with an interface function. More specifically, our triple-agent framework includes a Gesture Description Agent that automatically segments and formulates natural language descriptions of hand poses and movements based on hand landmark coordinates. The description is deciphered by a Gesture Inference Agent through self-reasoning and querying about the interaction context (e.g., interaction history, gaze data), which is managed by a Context Management Agent. Following iterative exchanges, the Gesture Inference Agent discerns the user's intent by grounding it to an interactive function. We validated our framework offline under two real-world scenarios: smart home control and online video streaming. The average zero-shot Top-1/Top-5 grounding accuracies are 44.79%/83.59% for smart home tasks and 37.50%/73.44% for video streaming tasks. We also provide an extensive discussion that includes rationale for model selection, generalizability, and future research directions for a practical system etc.

[Arxiv](https://arxiv.org/abs/2310.12821)