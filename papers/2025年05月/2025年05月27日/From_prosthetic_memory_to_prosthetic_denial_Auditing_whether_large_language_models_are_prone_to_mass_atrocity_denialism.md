# 从义体记忆到义体否认：探究大型语言模型是否易陷于大规模暴行否认倾向

发布时间：2025年05月27日

`LLM应用`

> From prosthetic memory to prosthetic denial: Auditing whether large language models are prone to mass atrocity denialism

# 摘要

> 大型语言模型 (LLMs) 的普及正在改变历史记忆的传播方式。本研究探讨了 LLMs 对大规模暴行记忆表述的影响，重点关注它们是否有助于形成"辅助记忆"（即通过技术中介的历史体验），或者是否会导致"辅助性否认"（即通过 AI 技术对历史创伤记忆的歪曲或消解）。我们发现，LLMs 作为中介工具，既可能成为记忆传递的桥梁，也可能成为否认历史真相的推手，尤其当其输出与某些争议性叙述相吻合时。

为了验证这些风险，我们对 Claude、GPT、Llama、Mixtral 和 Gemini 五种 LLM 进行了深入测试，选取了四个具有代表性的历史案例：大饥荒、大屠杀、柬埔寨种族灭绝以及卢旺达图西人大屠杀。针对每个案例，我们分别用英语和相关语言（乌克兰语、德语、高棉语、法语）向模型提问，涵盖常见的历史否认论调。研究发现，LLMs 对有充分历史记录的事件（如大屠杀）通常能提供准确的回应，但对于较为边缘化的案例（如柬埔寨种族灭绝），则表现出明显的不一致性和对否认主义叙述的倾向性。这些差异反映了训练数据的局限性和 LLM 响应的随机性对历史记忆完整性的潜在威胁。

研究结论表明，虽然 LLMs 为历史记忆的传播提供了新的可能性，但其无约束的使用可能加剧历史否认主义，引发与数字记忆保存相关的伦理问题，并可能削弱技术在维护历史真相方面的积极作用。

> The proliferation of large language models (LLMs) can influence how historical narratives are disseminated and perceived. This study explores the implications of LLMs' responses on the representation of mass atrocity memory, examining whether generative AI systems contribute to prosthetic memory, i.e., mediated experiences of historical events, or to what we term "prosthetic denial," the AI-mediated erasure or distortion of atrocity memories. We argue that LLMs function as interfaces that can elicit prosthetic memories and, therefore, act as experiential sites for memory transmission, but also introduce risks of denialism, particularly when their outputs align with contested or revisionist narratives. To empirically assess these risks, we conducted a comparative audit of five LLMs (Claude, GPT, Llama, Mixtral, and Gemini) across four historical case studies: the Holodomor, the Holocaust, the Cambodian Genocide, and the genocide against the Tutsis in Rwanda. Each model was prompted with questions addressing common denialist claims in English and an alternative language relevant to each case (Ukrainian, German, Khmer, and French). Our findings reveal that while LLMs generally produce accurate responses for widely documented events like the Holocaust, significant inconsistencies and susceptibility to denialist framings are observed for more underrepresented cases like the Cambodian Genocide. The disparities highlight the influence of training data availability and the probabilistic nature of LLM responses on memory integrity. We conclude that while LLMs extend the concept of prosthetic memory, their unmoderated use risks reinforcing historical denialism, raising ethical concerns for (digital) memory preservation, and potentially challenging the advantageous role of technology associated with the original values of prosthetic memory.

[Arxiv](https://arxiv.org/abs/2505.21753)