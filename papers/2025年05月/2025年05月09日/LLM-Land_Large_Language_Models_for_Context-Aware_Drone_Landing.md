# LLM-Land：探索适用于情境感知无人机着陆的大型语言模型

发布时间：2025年05月09日

`LLM应用` `无人机行业` `无人机技术`

> LLM-Land: Large Language Models for Context-Aware Drone Landing

# 摘要

> 无人机自主降落在紧急配送、灾害响应及大规模任务中至关重要，它支持无人机持续运行并显著延长续航时间。传统方法在动态非结构化环境中表现有限，主要由于语义感知不足和固定安全裕度的依赖。为此，我们提出结合大型语言模型（LLMs）与模型预测控制（MPC）的混合框架。我们的方法从视觉语言编码器（如BLIP）开始，将实时图像转化为简洁的文字场景描述。轻量级LLM（如Qwen 2.5 1.5B或LLaMA 3.2 1B）配合检索增强生成（RAG），分类场景元素并推断上下文感知的安全缓冲区，例如行人3米，车辆5米。这些语义标志和危险区域输入MPC模块，实现实时轨迹重规划，避免碰撞同时保持高精度降落。在ROS-Gazebo模拟器中，我们的框架显著减少动态障碍物环境下的险情，同时在复杂环境中保持精确降落能力。

> Autonomous landing is essential for drones deployed in emergency deliveries, post-disaster response, and other large-scale missions. By enabling self-docking on charging platforms, it facilitates continuous operation and significantly extends mission endurance. However, traditional approaches often fall short in dynamic, unstructured environments due to limited semantic awareness and reliance on fixed, context-insensitive safety margins. To address these limitations, we propose a hybrid framework that integrates large language model (LLMs) with model predictive control (MPC). Our approach begins with a vision-language encoder (VLE) (e.g., BLIP), which transforms real-time images into concise textual scene descriptions. These descriptions are processed by a lightweight LLM (e.g., Qwen 2.5 1.5B or LLaMA 3.2 1B) equipped with retrieval-augmented generation (RAG) to classify scene elements and infer context-aware safety buffers, such as 3 meters for pedestrians and 5 meters for vehicles. The resulting semantic flags and unsafe regions are then fed into an MPC module, enabling real-time trajectory replanning that avoids collisions while maintaining high landing precision. We validate our framework in the ROS-Gazebo simulator, where it consistently outperforms conventional vision-based MPC baselines. Our results show a significant reduction in near-miss incidents with dynamic obstacles, while preserving accurate landings in cluttered environments.

[Arxiv](https://arxiv.org/abs/2505.06399)