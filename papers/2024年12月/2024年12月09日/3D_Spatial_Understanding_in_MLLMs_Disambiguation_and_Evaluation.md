# 在多模态大型语言模型（MLLMs）中的 3D 空间理解：消歧与评估

发布时间：2024年12月09日

`LLM应用` `机器人` `3D 视觉`

> 3D Spatial Understanding in MLLMs: Disambiguation and Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）在图像字幕和问答等任务方面进展显著。不过，这些模型虽能生成逼真的字幕，却常在提供精准指令上遭遇难题，尤其在复杂 3D 环境中定位和消除对象歧义时。随着 MLLMs 与协作机器人系统的融合加深，这种能力愈发关键。当目标对象被相似对象（干扰物）环绕时，机器人必须给出清晰、具备空间感知的指令，从而有效地引导人类。我们把这一挑战称作上下文对象定位与消歧，它比传统 3D 密集字幕的限制更严格，特别是在确保目标唯一性方面。对此，我们提出了简单有效的技术，以增强模型定位和消除目标对象歧义的能力。我们的方法不仅在评估句子相似度的常规指标上达到了领先水平，还通过 3D 视觉基础模型展现出了更强的 3D 空间理解能力。

> Multimodal Large Language Models (MLLMs) have made significant progress in tasks such as image captioning and question answering. However, while these models can generate realistic captions, they often struggle with providing precise instructions, particularly when it comes to localizing and disambiguating objects in complex 3D environments. This capability is critical as MLLMs become more integrated with collaborative robotic systems. In scenarios where a target object is surrounded by similar objects (distractors), robots must deliver clear, spatially-aware instructions to guide humans effectively. We refer to this challenge as contextual object localization and disambiguation, which imposes stricter constraints than conventional 3D dense captioning, especially regarding ensuring target exclusivity. In response, we propose simple yet effective techniques to enhance the model's ability to localize and disambiguate target objects. Our approach not only achieves state-of-the-art performance on conventional metrics that evaluate sentence similarity, but also demonstrates improved 3D spatial understanding through 3D visual grounding model.

[Arxiv](https://arxiv.org/abs/2412.06613)