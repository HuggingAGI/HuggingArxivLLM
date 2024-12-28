# 确保图像内翻译的一致性

发布时间：2024年12月23日

`LLM应用` `机器翻译` `图像翻译`

> Ensuring Consistency for In-Image Translation

# 摘要

> 图像内机器翻译任务是对嵌入图像中的文本进行翻译，翻译结果以图像形式呈现。尽管此任务在诸如电影海报翻译、日常场景图像翻译等众多场景中有着广泛应用，然而现有方法在整个流程中常常忽视一致性这一方面。我们认为在该任务中需维持两种一致性：翻译一致性与图像生成一致性。前者意味着在翻译时融入图像信息，后者则是要保持文本图像的风格与原始图像一致，保证背景完整。为满足这些一致性要求，我们引入了一个新颖的两阶段框架，名为 HCIIT（高一致性图像内翻译）。第一阶段利用多模态多语言大型语言模型进行文本图像翻译，第二阶段使用扩散模型进行图像回填。第一阶段通过思维链学习增强模型在翻译中利用图像信息的能力。接着，为生成风格一致的文本图像而训练的扩散模型确保了图像内文本风格的统一，并保留了背景细节。我们整理了一个包含 40 万对风格一致的伪文本图像对的数据集用于模型训练。在整理的测试集和真实图像测试集上取得的结果证实了我们的框架在保证一致性和生成高质量翻译图像方面的有效性。

> The in-image machine translation task involves translating text embedded within images, with the translated results presented in image format. While this task has numerous applications in various scenarios such as film poster translation and everyday scene image translation, existing methods frequently neglect the aspect of consistency throughout this process. We propose the need to uphold two types of consistency in this task: translation consistency and image generation consistency. The former entails incorporating image information during translation, while the latter involves maintaining consistency between the style of the text-image and the original image, ensuring background integrity. To address these consistency requirements, we introduce a novel two-stage framework named HCIIT (High-Consistency In-Image Translation) which involves text-image translation using a multimodal multilingual large language model in the first stage and image backfilling with a diffusion model in the second stage. Chain of thought learning is utilized in the first stage to enhance the model's ability to leverage image information during translation. Subsequently, a diffusion model trained for style-consistent text-image generation ensures uniformity in text style within images and preserves background details. A dataset comprising 400,000 style-consistent pseudo text-image pairs is curated for model training. Results obtained on both curated test sets and authentic image test sets validate the effectiveness of our framework in ensuring consistency and producing high-quality translated images.

[Arxiv](https://arxiv.org/abs/2412.18139)