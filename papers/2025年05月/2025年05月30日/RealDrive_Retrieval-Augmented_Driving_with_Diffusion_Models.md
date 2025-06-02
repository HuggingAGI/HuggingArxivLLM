# RealDrive：利用扩散模型的增强驾驶检索

发布时间：2025年05月30日

`RAG` `自动驾驶`

> RealDrive: Retrieval-Augmented Driving with Diffusion Models

# 摘要

> 基于学习的规划器通过学习数据中的复杂交互，生成自然的类人驾驶行为，克服了传统规则规划器的僵化表现。然而，数据驱动方法在处理罕见安全场景时往往力不从心，且对轨迹控制力有限。为解决这一难题，我们提出了RealDrive——一个检索增强生成（RAG）框架。该框架通过从训练数据中检索最相关的专家演示，初始化基于扩散的规划策略。通过去噪过程将当前观测与检索案例进行融合，我们的方法能在多样化场景中实现精细控制和安全行为，充分借助检索场景提供的强先验优势。另一个重要发现是，采用基于规划目标训练的任务相关检索模型，相比任务无关检索器，能显著提升框架性能。实验结果表明，与传统学习型规划器相比，RealDrive在长尾事件上的泛化能力和轨迹多样性均有提升——在Waymo Open Motion数据集上，采用RAG后碰撞率降低了40%。

> Learning-based planners generate natural human-like driving behaviors by learning to reason about nuanced interactions from data, overcoming the rigid behaviors that arise from rule-based planners. Nonetheless, data-driven approaches often struggle with rare, safety-critical scenarios and offer limited controllability over the generated trajectories. To address these challenges, we propose RealDrive, a Retrieval-Augmented Generation (RAG) framework that initializes a diffusion-based planning policy by retrieving the most relevant expert demonstrations from the training dataset. By interpolating between current observations and retrieved examples through a denoising process, our approach enables fine-grained control and safe behavior across diverse scenarios, leveraging the strong prior provided by the retrieved scenario. Another key insight we produce is that a task-relevant retrieval model trained with planning-based objectives results in superior planning performance in our framework compared to a task-agnostic retriever. Experimental results demonstrate improved generalization to long-tail events and enhanced trajectory diversity compared to standard learning-based planners -- we observe a 40% reduction in collision rate on the Waymo Open Motion dataset with RAG.

[Arxiv](https://arxiv.org/abs/2505.24808)