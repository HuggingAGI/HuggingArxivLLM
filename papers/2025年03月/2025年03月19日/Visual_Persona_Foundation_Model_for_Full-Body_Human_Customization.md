# 视觉形象：全身人类定制的基础模型

发布时间：2025年03月19日

`LLM应用` `图像生成` `人物定制`

> Visual Persona: Foundation Model for Full-Body Human Customization

# 摘要

> 我们推出Visual Persona——一款全新的文本到图像全身人物定制基础模型。只需一张野外拍摄的人体照片，它就能根据你的文字描述，生成多种多样的个性化形象。与传统方法只关注面部特征不同，Visual Persona能捕捉全身细节，精准匹配你描述的体型和场景变化。为了训练这个模型，我们需要大量高质量的配对人体数据，这在现实中获取极为困难。为此，我们开发了一套数据整理流程，利用视觉语言模型评估全身外观一致性，成功构建了包含100,000个独特身份、580,000对高质量图像的Visual Persona-500K数据集。为了让定制更精准，我们设计了一种基于预训练文本到图像扩散模型的Transformer编码器-解码器架构。该架构能将输入图像分割成不同身体部位，提取局部外观特征，并独立映射到密集身份嵌入中，从而精准控制扩散模型，生成高度定制化的图像。经过大量实验验证，Visual Persona在从野外输入生成高质量定制图像方面表现卓越。我们还进行了全面的消融研究，证明了设计选择的合理性，并展示了其在各类下游任务中的广泛应用潜力。

> We introduce Visual Persona, a foundation model for text-to-image full-body human customization that, given a single in-the-wild human image, generates diverse images of the individual guided by text descriptions. Unlike prior methods that focus solely on preserving facial identity, our approach captures detailed full-body appearance, aligning with text descriptions for body structure and scene variations. Training this model requires large-scale paired human data, consisting of multiple images per individual with consistent full-body identities, which is notoriously difficult to obtain. To address this, we propose a data curation pipeline leveraging vision-language models to evaluate full-body appearance consistency, resulting in Visual Persona-500K, a dataset of 580k paired human images across 100k unique identities. For precise appearance transfer, we introduce a transformer encoder-decoder architecture adapted to a pre-trained text-to-image diffusion model, which augments the input image into distinct body regions, encodes these regions as local appearance features, and projects them into dense identity embeddings independently to condition the diffusion model for synthesizing customized images. Visual Persona consistently surpasses existing approaches, generating high-quality, customized images from in-the-wild inputs. Extensive ablation studies validate design choices, and we demonstrate the versatility of Visual Persona across various downstream tasks.

[Arxiv](https://arxiv.org/abs/2503.15406)