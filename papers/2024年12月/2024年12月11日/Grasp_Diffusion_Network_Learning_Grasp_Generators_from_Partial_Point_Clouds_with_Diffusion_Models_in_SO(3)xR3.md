# Grasp Diffusion Network：借助 SO(3)×R3 中的扩散模型从部分点云学习抓取生成器

发布时间：2024年12月11日

`Agent` `机器人` `抓取技术`

> Grasp Diffusion Network: Learning Grasp Generators from Partial Point Clouds with Diffusion Models in SO(3)xR3

# 摘要

> 在众多机器人操作任务中，通过单目相机成功抓取物体极为关键。解决这一问题的办法之一是借助模拟创建大量的物体与抓取姿势配对的数据集，接着学习一个在部署时能迅速响应的条件生成模型。然而，由于抓取物体的方式多样，抓取姿势数据呈现高度多模态。所以在本研究中，我们利用扩散模型学习抓取生成模型，依据物体的部分点云来采样候选抓取姿势。我们方法的创新点在于考虑旋转流形空间中的扩散，并提出避免碰撞成本引导以提升推理时的抓取成功率。为加快抓取采样，我们运用扩散文献中的最新技术以实现更快速的推理时间。我们在模拟和真实世界的实验中表明，我们的方法能够从原始深度图像抓取多个物体，成功率达 90%，并与若干基线进行了对比。

> Grasping objects successfully from a single-view camera is crucial in many robot manipulation tasks. An approach to solve this problem is to leverage simulation to create large datasets of pairs of objects and grasp poses, and then learn a conditional generative model that can be prompted quickly during deployment. However, the grasp pose data is highly multimodal since there are several ways to grasp an object. Hence, in this work, we learn a grasp generative model with diffusion models to sample candidate grasp poses given a partial point cloud of an object. A novel aspect of our method is to consider diffusion in the manifold space of rotations and to propose a collision-avoidance cost guidance to improve the grasp success rate during inference. To accelerate grasp sampling we use recent techniques from the diffusion literature to achieve faster inference times. We show in simulation and real-world experiments that our approach can grasp several objects from raw depth images with $90\%$ success rate and benchmark it against several baselines.

[Arxiv](https://arxiv.org/abs/2412.08398)