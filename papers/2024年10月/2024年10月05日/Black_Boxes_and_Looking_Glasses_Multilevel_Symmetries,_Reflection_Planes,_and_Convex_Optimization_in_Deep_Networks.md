# 黑箱与窥镜：深度网络中的多层次对称、反射平面与凸优化

发布时间：2024年10月05日

`LLM理论` `机器学习` `神经网络`

> Black Boxes and Looking Glasses: Multilevel Symmetries, Reflection Planes, and Convex Optimization in Deep Networks

# 摘要

> 我们发现，训练具有绝对值激活和任意输入维度的深度神经网络（DNN）可以转化为等价的凸 Lasso 问题，并利用几何代数表达的新特征。这一转化揭示了神经网络中编码对称性的几何结构。通过这种等价形式，我们证明了深度网络与浅层网络的根本差异：深度网络更倾向于在其拟合函数中包含对称结构，且网络越深，对称性层次越丰富，即对称性嵌套。此外，Lasso 特征反映了训练点到超平面的距离，这些超平面由训练数据生成，并与最优权重向量正交。数值实验不仅验证了理论，还展示了使用大型语言模型生成嵌入训练网络时，理论预测的特征。

> We show that training deep neural networks (DNNs) with absolute value activation and arbitrary input dimension can be formulated as equivalent convex Lasso problems with novel features expressed using geometric algebra. This formulation reveals geometric structures encoding symmetry in neural networks. Using the equivalent Lasso form of DNNs, we formally prove a fundamental distinction between deep and shallow networks: deep networks inherently favor symmetric structures in their fitted functions, with greater depth enabling multilevel symmetries, i.e., symmetries within symmetries. Moreover, Lasso features represent distances to hyperplanes that are reflected across training points. These reflection hyperplanes are spanned by training data and are orthogonal to optimal weight vectors. Numerical experiments support theory and demonstrate theoretically predicted features when training networks using embeddings generated by Large Language Models.

[Arxiv](https://arxiv.org/abs/2410.04279)