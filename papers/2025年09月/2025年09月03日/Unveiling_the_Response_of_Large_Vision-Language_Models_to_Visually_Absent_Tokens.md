# 揭示大型视觉-语言模型对视觉缺失标记的响应

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Unveiling the Response of Large Vision-Language Models to Visually Absent Tokens

# 摘要

> 大型视觉语言模型（LVLMs）能联合理解视觉与文本输入，生成符合上下文的响应。但我们发现，它们常误将缺乏视觉证据的文本输入当作图像内容，进而产生错误回答。为此，我们探究LVLMs是否具备判断文本概念是否在图像中有视觉依据的内在能力，结果发现前馈网络（FFN）中存在一类特定神经元子集——视觉缺失感知（VA）神经元，它们通过独特的激活模式持续提示视觉缺失。基于这些模式，我们开发了检测模块，可系统判断输入标记是否具有视觉依据。根据检测结果，我们提出优化生成输出的方法：在生成过程中重新解读问题提示，或替换检测到的缺失标记。大量实验证实，该方法能有效缓解模型错误假设文本输入存在视觉对应物的倾向，并在多种LVLMs上具有通用性。

> Large Vision-Language Models (LVLMs) generate contextually relevant responses by jointly interpreting visual and textual inputs. However, our finding reveals they often mistakenly perceive text inputs lacking visual evidence as being part of the image, leading to erroneous responses. In light of this finding, we probe whether LVLMs possess an internal capability to determine if textual concepts are grounded in the image, and discover a specific subset of Feed-Forward Network (FFN) neurons, termed Visual Absence-aware (VA) neurons, that consistently signal the visual absence through a distinctive activation pattern. Leveraging these patterns, we develop a detection module that systematically classifies whether an input token is visually grounded. Guided by its prediction, we propose a method to refine the outputs by reinterpreting question prompts or replacing the detected absent tokens during generation. Extensive experiments show that our method effectively mitigates the models' tendency to falsely presume the visual presence of text input and its generality across various LVLMs.

[Arxiv](https://arxiv.org/abs/2509.03025)