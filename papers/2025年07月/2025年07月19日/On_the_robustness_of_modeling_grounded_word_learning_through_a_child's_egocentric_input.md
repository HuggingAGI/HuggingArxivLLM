# 基于儿童自我中心视角输入的词语学习建模鲁棒性研究

发布时间：2025年07月19日

`LLM理论` `计算机视觉`

> On the robustness of modeling grounded word learning through a child's egocentric input

# 摘要

> 机器学习如何帮助我们理解人类语言习得？大型语言模型和多模态模型虽然能力出众，但它们依赖海量数据的特性与儿童仅通过有限输入就能掌握语言形成了鲜明对比。为了填补这一鸿沟，研究者开始尝试使用与儿童输入在量和质上相近的数据训练神经网络。Vong等人（2024）的研究将这一思路推向极致，他们证明仅用一名儿童成长过程中产生的61小时视觉与语言数据训练的多模态神经网络就能掌握词-指称映射。然而，这种成功是否仅限于单一儿童经验，还是能在多个儿童案例中保持一致的学习模式，这一问题仍待解答。在本文中，我们对覆盖三名儿童的500多小时SAYCam数据集进行了全自动语音转录处理。基于这些转录结果，我们构建了用于训练和评估的多模态视觉-语言数据集，并测试了多种神经网络配置，以探究模拟单词学习的稳健性。研究发现，基于每名儿童数据训练的网络能够在不同架构中掌握并泛化词-指称映射。这些发现不仅验证了多模态神经网络在基于经验的单词学习中的稳健性，同时也揭示了不同儿童成长经历对模型学习方式产生的独特影响。

> What insights can machine learning bring to understanding human language acquisition? Large language and multimodal models have achieved remarkable capabilities, but their reliance on massive training datasets creates a fundamental mismatch with children, who succeed in acquiring language from comparatively limited input. To help bridge this gap, researchers have increasingly trained neural networks using data similar in quantity and quality to children's input. Taking this approach to the limit, Vong et al. (2024) showed that a multimodal neural network trained on 61 hours of visual and linguistic input extracted from just one child's developmental experience could acquire word-referent mappings. However, whether this approach's success reflects the idiosyncrasies of a single child's experience, or whether it would show consistent and robust learning patterns across multiple children's experiences was not explored. In this article, we applied automated speech transcription methods to the entirety of the SAYCam dataset, consisting of over 500 hours of video data spread across all three children. Using these automated transcriptions, we generated multi-modal vision-and-language datasets for both training and evaluation, and explored a range of neural network configurations to examine the robustness of simulated word learning. Our findings demonstrate that networks trained on automatically transcribed data from each child can acquire and generalize word-referent mappings across multiple network architectures. These results validate the robustness of multimodal neural networks for grounded word learning, while highlighting the individual differences that emerge in how models learn when trained on each child's developmental experiences.

[Arxiv](https://arxiv.org/abs/2507.14749)