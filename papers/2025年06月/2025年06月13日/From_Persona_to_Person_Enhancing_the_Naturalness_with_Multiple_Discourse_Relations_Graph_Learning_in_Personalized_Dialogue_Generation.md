# 从角色到个体：基于多 discourse 关系图学习提升个性化对话生成的自然度

发布时间：2025年06月13日

`LLM应用` `人工智能`

> From Persona to Person: Enhancing the Naturalness with Multiple Discourse Relations Graph Learning in Personalized Dialogue Generation

# 摘要

> 对话生成中，自然的响应是实现高效人机交互的关键。而个性化响应生成更具挑战性，因为响应不仅要连贯，还要贴合用户的个人特质或人设描述。为此，我们提出了MUDI（$	extbf{Mu}$ltiple $	extbf{Di}$scourse Relations Graph Learning）模型，专注于个性化对话生成。我们借助大型语言模型进行话语关系标注，并将对话数据转化为结构化的对话图。在此基础上，我们提出的对话图注意力网络模型（DialogueGAT）能够捕捉隐含的话语关系，并结合人设描述。在生成个性化响应时，我们采用了新型的连贯性感知注意力策略，以提升解码器对话语关系的考量。实验结果表明，我们的方法显著提升了个性化响应的质量，使对话更趋近于人类之间的自然交流。

> In dialogue generation, the naturalness of responses is crucial for effective human-machine interaction. Personalized response generation poses even greater challenges, as the responses must remain coherent and consistent with the user's personal traits or persona descriptions. We propose MUDI ($\textbf{Mu}$ltiple $\textbf{Di}$scourse Relations Graph Learning) for personalized dialogue generation. We utilize a Large Language Model to assist in annotating discourse relations and to transform dialogue data into structured dialogue graphs. Our graph encoder, the proposed DialogueGAT model, then captures implicit discourse relations within this structure, along with persona descriptions. During the personalized response generation phase, novel coherence-aware attention strategies are implemented to enhance the decoder's consideration of discourse relations. Our experiments demonstrate significant improvements in the quality of personalized responses, thus resembling human-like dialogue exchanges.

[Arxiv](https://arxiv.org/abs/2506.11557)