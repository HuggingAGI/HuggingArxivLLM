# SCOPE：语音引导的协作感知框架（面向手术场景分割）

发布时间：2025年09月12日

`Agent` `医疗健康`

> SCOPE: Speech-guided COllaborative PErception Framework for Surgical Scene Segmentation

# 摘要

> 准确分割和跟踪手术场景关键元素，对实现情境感知的术中辅助与决策支持至关重要。目前的解决方案仍局限于特定领域的监督模型，这类模型不仅依赖标记数据，还需要特定领域数据才能适应新的手术场景，甚至无法处理预定义标签类别之外的元素。近年来，提示驱动的视觉基础模型（VFM）取得突破，已能在异构医学图像上实现开放集、零样本分割。但这些模型依赖人工视觉或文本提示，这限制了它们在术中手术场景的实际应用。我们提出了语音引导的协作感知（SCOPE）框架，该框架整合了大型语言模型（LLM）的推理能力与开放集VFM的感知能力，可支持术中视频流中手术器械和解剖结构的实时分割、标记与跟踪。该框架的核心组件是协作感知智能体，它能生成VFM分割结果的最佳候选，并结合临床医生的直观语音反馈，以自然的人机协作模式指导手术器械的分割。随后，器械本身可作为交互式指针，用于标记手术场景的其他元素。我们在公开的Cataract1k数据集子集和内部离体颅底数据集上对所提框架进行了评估，验证了其实现手术场景实时分割与跟踪的潜力。此外，我们通过实时模拟离体实验展示了其动态性能。这种人机协作模式为开发适用于动态手术室环境的自适应、免手动、以外科医生为中心的工具提供了巨大潜力。

> Accurate segmentation and tracking of relevant elements of the surgical scene is crucial to enable context-aware intraoperative assistance and decision making. Current solutions remain tethered to domain-specific, supervised models that rely on labeled data and required domain-specific data to adapt to new surgical scenarios and beyond predefined label categories. Recent advances in prompt-driven vision foundation models (VFM) have enabled open-set, zero-shot segmentation across heterogeneous medical images. However, dependence of these models on manual visual or textual cues restricts their deployment in introperative surgical settings. We introduce a speech-guided collaborative perception (SCOPE) framework that integrates reasoning capabilities of large language model (LLM) with perception capabilities of open-set VFMs to support on-the-fly segmentation, labeling and tracking of surgical instruments and anatomy in intraoperative video streams. A key component of this framework is a collaborative perception agent, which generates top candidates of VFM-generated segmentation and incorporates intuitive speech feedback from clinicians to guide the segmentation of surgical instruments in a natural human-machine collaboration paradigm. Afterwards, instruments themselves serve as interactive pointers to label additional elements of the surgical scene. We evaluated our proposed framework on a subset of publicly available Cataract1k dataset and an in-house ex-vivo skull-base dataset to demonstrate its potential to generate on-the-fly segmentation and tracking of surgical scene. Furthermore, we demonstrate its dynamic capabilities through a live mock ex-vivo experiment. This human-AI collaboration paradigm showcase the potential of developing adaptable, hands-free, surgeon-centric tools for dynamic operating-room environments.

[Arxiv](https://arxiv.org/abs/2509.10748)