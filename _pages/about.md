---
permalink: /
title: "Advancing AI Fairness, Safety, and Responsibility"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


I'm a third-year PhD student at the [McCombs School of Business](https://www.mccombs.utexas.edu/) Information, Risk, and Operations Management (IROM) Department. I'm fortunate to be advised by [Maria De-Arteaga](https://mariadearteaga.com/) and [Maytal Saar-Tsechansky](http://www.maytals.com/).

My research promotes fairness, safety, and responsibility in the development and use of artificial intelligence (AI) systems trained on human opinions and judgments. 

To address these challenges, I employ an interdisciplinary approach, integrating techniques from machine learning, natural language processing, social science, ethics, and network science. 


## Ethics of Automating Human Judgments

One promise of AI rests on its ability to automate decision-making tasks that have traditionally relied on human judgment, especially in areas where a clear-cut ground truth is often lacking (e.g., determining whether content is harmful). However, human judgments are inherently subject to biases, underscoring the importance of carefully analyzing which biases AI systems may reflect in their output. My work focuses on identifying and addressing the implications of such biases, particularly within the realm of AI-assisted fact-checking. 

In this domain, I have formulated ethical frameworks to evaluate potential harms arising from AI usage, assessed the fairness of models used to prioritize content for fact-checking in simulated social networks, and investigated the capacity of large language models (LLMs) to represent diverse viewpoints on contentious issues.

## AI Alignment and Governance Research

Additionally, I am interested in developing technical approaches for AI alignment with human values, as well as governance approaches to safely open-source advanced AI. 

In the technical domain, I plan to initiate research on "supervisor" models designed to detect deception in LLMs. These supervisor models could serve as a crucial layer of oversight, identifying and mitigating instances where LLMs might generate misleading, manipulative, or otherwise unsafe content. 

On the governance side, I am interested in crafting policies and technical standards that facilitate the safe sharing of advanced AI technologies, ensuring they cannot be used for nefarious purposes. For instance, I propose "locking" inference for models that have been additionally trained after initial distribution until red-teaming evaluations are passed.

## About Me

In my spare time, I like to run around Austin (currently training for an ultra-marathon!), watch movies at [AFS](https://www.austinfilm.org/), and experiment with my ever growing guitar pedal collection.

## Publications

### 2023

**Neumann, Terrence**, and Nicholas Wolczynski. "Does AI-Assisted Fact-Checking Disproportionately Benefit Majority Groups Online?." Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency. 2023. <a href="https://dl.acm.org/doi/pdf/10.1145/3593013.3594013" class="btn btn-xs btn-default">pdf</a>

Tanriverdi, Hüseyin, John-Patrick Akinyemi, and **Terrence Neumann**. "Mitigating Bias in Organizational Development and Use of Artificial Intelligence." Proceedings of the 2023 AIS International Conference on Information Systems. 2023. <a href="https://aisel.aisnet.org/icis2023/hti/hti/19/" class="btn btn-xs btn-default">pdf</a>

### 2022 

**Neumann, Terrence**, Maria De-Arteaga, and Sina Fazelpour. "Justice in misinformation detection systems: An analysis of algorithms, stakeholders, and potential harms." Proceedings of the 2022 ACM Conference on Fairness, Accountability, and Transparency. 2022. <a href="https://dl.acm.org/doi/pdf/10.1145/3531146.3533205" class="btn btn-xs btn-default">pdf</a>

## Working Papers

**Diverse, but Divisive: LLMs Can Exaggerate Differences in Opinion Related to Harms of Misinformation.** With Sooyong Lee, Maria De-Arteaga, Sina Fazelpour, and Matt Lease. <a href="https://arxiv.org/pdf/2401.16558.pdf" class="btn btn-xs btn-default">pdf</a>

Abstract: The pervasive spread of misinformation and disinformation poses a significant threat to society. Professional fact-checkers play a key role in addressing this threat, but the vast scale of the problem forces them to prioritize their limited resources. This prioritization may consider a range of factors, such as varying risks of harm posed to specific groups of people. In this work, we investigate potential implications of using a large language model (LLM) to facilitate such prioritization. Because fact-checking impacts a wide range of diverse segments of society, it is important that diverse views are represented in the claim prioritization process. This paper examines whether a LLM can reflect the views of various groups when assessing the harms of misinformation, focusing on gender as a primary variable. We pose two central questions: (1) To what extent do prompts with explicit gender references reflect gender differences in opinion in the United States on topics of social relevance? and (2) To what extent do gender-neutral prompts align with gendered viewpoints on those topics? To analyze these questions, we present the TopicMisinfo dataset, containing 160 fact-checked claims from diverse topics, supplemented by nearly 1600 human annotations with subjective perceptions and annotator demographics. Analyzing responses to gender-specific and neutral prompts, we find that GPT 3.5-Turbo reflects empirically observed gender differences in opinion but amplifies the extent of these differences. These findings illuminate AI's complex role in moderating online communication, with implications for fact-checkers, algorithm designers, and the use of crowd-workers as annotators. We also release the TopicMisinfo dataset to support continuing research in the community.


**How Can Artificial General Intelligence Be Open-Sourced Responsibly?** With Bryan Jones. 

In the spirit of the collaborative ethos that propelled the development of the internet, AI researchers and developers have traditionally embraced open-source practices, often sharing research, codebases, and models freely. However, as AI technologies edge closer to achieving "general intelligence" and become vastly more expensive to train, the ethical and practical implications of open-sourcing such powerful systems come into sharp focus. This paper delves into the intricacies of modern AI development, elucidating the substantial resources required to train state-of-the-art models and clarifying the concept of "open-source" within this context. We also survey the existing regulatory frameworks governing open-source AI technologies. Through critical analysis, we identify potential pitfalls in the unbridled release of advanced AI technologies and propose a framework for responsible open-sourcing, aimed at mitigating risks while fostering innovation and accessibility in the field.
