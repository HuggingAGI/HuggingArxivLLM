# 探究一种能同时处理离散和连续数据的新型广义扩散模型，其具备可学习的编解码结构，能够实现数据的高效生成、精确重建及有效表示。

发布时间：2024年02月29日

`LLM应用`

> Generating, Reconstructing, and Representing Discrete and Continuous Data: Generalized Diffusion with Learnable Encoding-Decoding

# 摘要

> 深度生成模型在多种应用场景下立足于三大基石：生成全新样本、重建输入信息和学习高效的数据表示方式，覆盖从离散文本和蛋白质序列到连续图像等多种数据形态。尽管VAEs、GANs、自回归模型和扩散模型等各有千秋，擅长特定场景下的某项能力，但往往在其他领域表现平平。为此，我们创新提出了一种带有可学习编码-解码器的通用扩散模型——DiLED，它巧妙地融合了三大核心能力，以提高普适性并优化性能。DiLED通过引入参数化编码-解码机制，对标准扩散模型中的高斯噪声去除过程进行了推广。重要的是，DiLED能与成熟的扩散模型目标函数及训练配方无缝对接，使得编码-解码器参数可以与扩散过程协同有效学习。只要选择合适的编码器/解码器（比如大型语言模型），DiLED就能自然而然地应用于各类数据形态。广泛的实验证据表明，在文本、蛋白质结构和图像等多个领域，DiLED均展现出灵活应对多元数据与任务的能力，并在诸多现有模型之上取得了显著的性能提升。

> The vast applications of deep generative models are anchored in three core capabilities -- generating new instances, reconstructing inputs, and learning compact representations -- across various data types, such as discrete text/protein sequences and continuous images. Existing model families, like Variational Autoencoders (VAEs), Generative Adversarial Networks (GANs), autoregressive models, and diffusion models, generally excel in specific capabilities and data types but fall short in others. We introduce generalized diffusion with learnable encoder-decoder (DiLED), that seamlessly integrates the core capabilities for broad applicability and enhanced performance. DiLED generalizes the Gaussian noising-denoising in standard diffusion by introducing parameterized encoding-decoding. Crucially, DiLED is compatible with the well-established diffusion model objective and training recipes, allowing effective learning of the encoder-decoder parameters jointly with diffusion. By choosing appropriate encoder/decoder (e.g., large language models), DiLED naturally applies to different data types. Extensive experiments on text, proteins, and images demonstrate DiLED's flexibility to handle diverse data and tasks and its strong improvement over various existing models.

[Arxiv](https://arxiv.org/abs/2402.19009)