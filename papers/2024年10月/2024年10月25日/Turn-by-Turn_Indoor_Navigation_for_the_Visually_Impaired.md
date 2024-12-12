# 视障人士的逐次转向室内导航

发布时间：2024年10月25日

`LLM应用` `室内导航` `视障辅助`

> Turn-by-Turn Indoor Navigation for the Visually Impaired

# 摘要

> 在室内环境中导航对视障人士而言颇具挑战，原因在于布局复杂且无 GPS 信号。本文引入了一个新颖的系统，仅凭借配备摄像头的智能手机就能在建筑物内实现逐向导航，借助了多模态模型、深度学习算法以及大型语言模型（LLMs）。智能手机的摄像头抓取周围环境的实时图像，接着传至附近能运行设备端 LLM 模型、多模态模型和深度学习算法的树莓派，用于检测和识别建筑特征、标识及障碍物。随后，由树莓派上运行的 LLM 将解读后的视觉数据转化为自然语言指令，回传给用户，通过音频提示提供直观且具备上下文感知的引导。该解决方案对用户设备的工作负载要求极低，避免其过载，且能兼容包括无法运行 AI 模型的各类设备。这种方式让客户端不但能够运行高级模型，还能保证训练数据及其他信息不离开建筑物。初步评估显示，该系统能有效准确地引导用户穿越复杂的室内空间，彰显了其广泛应用的潜力。

> Navigating indoor environments presents significant challenges for visually impaired individuals due to complex layouts and the absence of GPS signals. This paper introduces a novel system that provides turn-by-turn navigation inside buildings using only a smartphone equipped with a camera, leveraging multimodal models, deep learning algorithms, and large language models (LLMs). The smartphone's camera captures real-time images of the surroundings, which are then sent to a nearby Raspberry Pi capable of running on-device LLM models, multimodal models, and deep learning algorithms to detect and recognize architectural features, signage, and obstacles. The interpreted visual data is then translated into natural language instructions by an LLM running on the Raspberry Pi, which is sent back to the user, offering intuitive and context-aware guidance via audio prompts. This solution requires minimal workload on the user's device, preventing it from being overloaded and offering compatibility with all types of devices, including those incapable of running AI models. This approach enables the client to not only run advanced models but also ensure that the training data and other information do not leave the building. Preliminary evaluations demonstrate the system's effectiveness in accurately guiding users through complex indoor spaces, highlighting its potential for widespread application

[Arxiv](https://arxiv.org/abs/2410.19954)