# 可查询三维场景表示：面向语义推理与机器人任务规划的多模态框架

发布时间：2025年09月24日

`Agent` `工业与制造`

> Queryable 3D Scene Representation: A Multi-Modal Framework for Semantic Reasoning and Robotic Task Planning

# 摘要

> 要让机器人理解人类高级指令并执行复杂任务，关键在于实现全面的场景理解——即如何有意义地解读和交互3D环境。这需要一种智能地图，将精确的几何结构与丰富的人类可理解语义融合一体。为此，我们提出3D可查询场景表示（3D QSR）——一种基于多媒体数据的新型框架，它统一了三种互补的3D表示：（1）全景重建生成的3D一致新视角渲染与分割；（2）3D点云提供的精确几何结构；（3）通过3D场景图实现的结构化、可扩展组织。该框架基于以对象为中心的设计，通过链接多模态对象嵌入，与大型视觉语言模型集成以实现语义可查询性，并支持对象级别的几何、视觉及语义信息检索。检索到的数据随后被加载到机器人任务规划器中，供下游执行使用。我们在Unity中进行模拟机器人任务规划场景实验，以抽象语言指令为指导，并使用室内公共数据集Replica，对该方法进行了评估。此外，我们还将其应用于真实湿实验室环境的数字复制品中，测试QSR支持的应急响应机器人任务规划。结果表明，该框架能够促进场景理解并整合空间与语义推理，在复杂3D环境中有效将人类高级指令转化为精确的机器人任务规划。

> To enable robots to comprehend high-level human instructions and perform complex tasks, a key challenge lies in achieving comprehensive scene understanding: interpreting and interacting with the 3D environment in a meaningful way. This requires a smart map that fuses accurate geometric structure with rich, human-understandable semantics. To address this, we introduce the 3D Queryable Scene Representation (3D QSR), a novel framework built on multimedia data that unifies three complementary 3D representations: (1) 3D-consistent novel view rendering and segmentation from panoptic reconstruction, (2) precise geometry from 3D point clouds, and (3) structured, scalable organization via 3D scene graphs. Built on an object-centric design, the framework integrates with large vision-language models to enable semantic queryability by linking multimodal object embeddings, and supporting object-level retrieval of geometric, visual, and semantic information. The retrieved data are then loaded into a robotic task planner for downstream execution. We evaluate our approach through simulated robotic task planning scenarios in Unity, guided by abstract language instructions and using the indoor public dataset Replica. Furthermore, we apply it in a digital duplicate of a real wet lab environment to test QSR-supported robotic task planning for emergency response. The results demonstrate the framework's ability to facilitate scene understanding and integrate spatial and semantic reasoning, effectively translating high-level human instructions into precise robotic task planning in complex 3D environments.

[Arxiv](https://arxiv.org/abs/2509.20077)