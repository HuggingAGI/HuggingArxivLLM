# 视觉与位置信息融合：基于Transformer的医学伤口分析多模态深度学习框架

发布时间：2025年04月14日

`LLM应用` `伤口诊断`

> Integrating Vision and Location with Transformers: A Multimodal Deep Learning Framework for Medical Wound Analysis

# 摘要

> 准确识别急性难愈合伤口是伤口诊断中的关键步骤。本研究开发了一种基于深度学习的多模态分类器，利用伤口图像及其对应位置信息，将伤口分类为糖尿病溃疡、压力性溃疡、手术伤口和静脉溃疡等多种类型。此外，还创建了一个身体部位图谱，提供位置数据，这有助于伤口专科医生更高效地标注伤口位置。该模型采用视觉变换器从输入图像中提取层次化特征，通过离散小波变换（DWT）层捕获低频和高频成分，并使用变换器提取空间特征。模型的神经元数量和权重向量优化采用了三种基于群的优化技术（Monster Gorilla Toner (MGTO)、改进灰狼优化 (IGWO) 和狐狸优化算法）。评估结果显示，使用优化算法进行权重向量优化可以提高诊断准确率，使其成为一种非常有效的伤口检测方法。在使用原始身体部位图谱进行分类时，所提出的模型能够利用图像数据实现 0.8123 的准确率，结合图像数据和伤口位置信息则达到 0.8007 的准确率。此外，结合优化模型的分类准确率在 0.7801 到 0.8342 之间。

> Effective recognition of acute and difficult-to-heal wounds is a necessary step in wound diagnosis. An efficient classification model can help wound specialists classify wound types with less financial and time costs and also help in deciding on the optimal treatment method. Traditional machine learning models suffer from feature selection and are usually cumbersome models for accurate recognition. Recently, deep learning (DL) has emerged as a powerful tool in wound diagnosis. Although DL seems promising for wound type recognition, there is still a large scope for improving the efficiency and accuracy of the model. In this study, a DL-based multimodal classifier was developed using wound images and their corresponding locations to classify them into multiple classes, including diabetic, pressure, surgical, and venous ulcers. A body map was also created to provide location data, which can help wound specialists label wound locations more effectively. The model uses a Vision Transformer to extract hierarchical features from input images, a Discrete Wavelet Transform (DWT) layer to capture low and high frequency components, and a Transformer to extract spatial features. The number of neurons and weight vector optimization were performed using three swarm-based optimization techniques (Monster Gorilla Toner (MGTO), Improved Gray Wolf Optimization (IGWO), and Fox Optimization Algorithm). The evaluation results show that weight vector optimization using optimization algorithms can increase diagnostic accuracy and make it a very effective approach for wound detection. In the classification using the original body map, the proposed model was able to achieve an accuracy of 0.8123 using image data and an accuracy of 0.8007 using a combination of image data and wound location. Also, the accuracy of the model in combination with the optimization models varied from 0.7801 to 0.8342.

[Arxiv](https://arxiv.org/abs/2504.10452)