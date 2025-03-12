# # 利用生成式AI进行事实核查：系统性跨主题考察LLMs检测政治信息真实性的能力

发布时间：2025年03月11日

`LLM应用` `事实核查`

> Fact-checking with Generative AI: A Systematic Cross-Topic Examination of LLMs Capacity to Detect Veracity of Political Information

# 摘要

> 本研究旨在探索大型语言模型（LLMs）在事实核查中的应用及其对自动真实性识别的潜在贡献。我们采用AI审计方法论，系统评估了ChatGPT 4、Llama 3 (70B)、Llama 3.1 (405B)、Claude 3.5 Sonnet和Google Gemini五个模型的表现，使用了由专业记者核实的16,513条陈述相关的提示。通过主题建模和回归分析，我们发现，尽管ChatGPT 4和Google Gemini的准确率较高，但整体表现仍有提升空间。值得注意的是，模型在识别虚假陈述尤其是涉及COVID-19、美国政治争议和社会问题等敏感话题时表现更佳，这可能为提升这些话题的准确性提供了保护措施的思路。我们的研究揭示了使用LLMs进行事实核查的挑战，包括不同模型性能差异和特定主题输出质量不均衡的问题，这些问题可能源于训练数据的不足。本研究不仅展示了LLMs在政治事实核查中的潜力，也指出了其局限性，并为未来改进保护措施和模型微调提供了方向。

> The purpose of this study is to assess how large language models (LLMs) can be used for fact-checking and contribute to the broader debate on the use of automated means for veracity identification. To achieve this purpose, we use AI auditing methodology that systematically evaluates performance of five LLMs (ChatGPT 4, Llama 3 (70B), Llama 3.1 (405B), Claude 3.5 Sonnet, and Google Gemini) using prompts regarding a large set of statements fact-checked by professional journalists (16,513). Specifically, we use topic modeling and regression analysis to investigate which factors (e.g. topic of the prompt or the LLM type) affect evaluations of true, false, and mixed statements. Our findings reveal that while ChatGPT 4 and Google Gemini achieved higher accuracy than other models, overall performance across models remains modest. Notably, the results indicate that models are better at identifying false statements, especially on sensitive topics such as COVID-19, American political controversies, and social issues, suggesting possible guardrails that may enhance accuracy on these topics. The major implication of our findings is that there are significant challenges for using LLMs for factchecking, including significant variation in performance across different LLMs and unequal quality of outputs for specific topics which can be attributed to deficits of training data. Our research highlights the potential and limitations of LLMs in political fact-checking, suggesting potential avenues for further improvements in guardrails as well as fine-tuning.

[Arxiv](https://arxiv.org/abs/2503.08404)