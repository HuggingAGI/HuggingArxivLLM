# MME-VideoOCR：对多模态大语言模型在视频场景中的OCR能力进行评估

发布时间：2025年05月27日

`LLM应用` `视频处理` `OCR`

> MME-VideoOCR: Evaluating OCR-Based Capabilities of Multimodal LLMs in Video Scenarios

# 摘要

> 多模态大型语言模型（MLLMs）在静态图像OCR中表现出色，但在视频OCR领域却面临诸多挑战，如运动模糊、时间变化和视觉效果等因素的影响。为更好地指导实用MLLMs的训练，我们推出了MME-VideoOCR基准测试，涵盖视频OCR的多种应用场景。该基准包含10个任务类别、25个独立任务，横跨44种不同场景，不仅涉及文本识别，还包括对视频文本内容的深度理解和推理。MME-VideoOCR由1,464个分辨率、宽高比和时长各异的视频组成，并附有2,000个精心策划、人工标注的问题-答案对。我们在该基准上评估了18个先进MLLMs，发现即使最优模型（Gemini-2.5 Pro）也只能达到73.7%的准确率。分析显示，现有MLLMs在处理单一或少数帧文本任务时表现优异，但在需要整体视频理解的任务上表现欠佳，尤其在时空推理、跨帧信息整合或抵抗语言偏见方面存在明显局限。研究结果还突显了高分辨率视觉输入和充分时间覆盖在动态视频OCR中的重要性。

> Multimodal Large Language Models (MLLMs) have achieved considerable accuracy in Optical Character Recognition (OCR) from static images. However, their efficacy in video OCR is significantly diminished due to factors such as motion blur, temporal variations, and visual effects inherent in video content. To provide clearer guidance for training practical MLLMs, we introduce the MME-VideoOCR benchmark, which encompasses a comprehensive range of video OCR application scenarios. MME-VideoOCR features 10 task categories comprising 25 individual tasks and spans 44 diverse scenarios. These tasks extend beyond text recognition to incorporate deeper comprehension and reasoning of textual content within videos. The benchmark consists of 1,464 videos with varying resolutions, aspect ratios, and durations, along with 2,000 meticulously curated, manually annotated question-answer pairs. We evaluate 18 state-of-the-art MLLMs on MME-VideoOCR, revealing that even the best-performing model (Gemini-2.5 Pro) achieves an accuracy of only 73.7%. Fine-grained analysis indicates that while existing MLLMs demonstrate strong performance on tasks where relevant texts are contained within a single or few frames, they exhibit limited capability in effectively handling tasks that demand holistic video comprehension. These limitations are especially evident in scenarios that require spatio-temporal reasoning, cross-frame information integration, or resistance to language prior bias. Our findings also highlight the importance of high-resolution visual input and sufficient temporal coverage for reliable OCR in dynamic video scenarios.

[Arxiv](https://arxiv.org/abs/2505.21333)