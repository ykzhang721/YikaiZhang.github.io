---
title: "DetectBench: Can Large Language Model Detect and Piece Together Implicit Evidence?"
collection: publications
permalink: /publication/detectbench
excerpt: 'Evaluating the ability of LLMs in evidence detection.'
date: 2023-02-08
venue: 'Arxiv Preprint'
paperurl: 'https://arxiv.org/pdf/2406.12641'
# citation: '@article{zhang2024timearena,
#   title={Timearena: Shaping efficient multitasking language agents in a time-aware simulation},
#   author={Zhang, Yikai and Yuan, Siyu and Hu, Caiyu and Richardson, Kyle and Xiao, Yanghua and Chen, Jiangjie},
#   journal={arXiv preprint arXiv:2402.05733},
#   year={2024}
# }'
---

Detecting evidence within the context is a key step in the process of reasoning task. Evaluating and enhancing the capabilities of LLMs in evidence detection will strengthen context-based reasoning performance. This paper proposes a benchmark called DetectBench for verifying the ability to detect and piece together implicit evidence within a long context. DetectBench contains 3,928 multiple-choice questions, with an average of 994 tokens per question. Each question contains an average of 4.55 pieces of implicit evidence, and solving the problem typically requires 7.62 logical jumps to find the correct answer. To enhance the performance of LLMs in evidence detection, this paper proposes Detective Reasoning Prompt and Finetune. Experiments demonstrate that the existing LLMs' abilities to detect evidence in long contexts are far inferior to humans. However, the Detective Reasoning Prompt effectively enhances the capability of powerful LLMs in evidence detection, while the Finetuning method shows significant effects in enhancing the performance of weaker LLMs. Moreover, when the abilities of LLMs in evidence detection are improved, their final reasoning performance is also enhanced accordingly.



![figure](/assets/detectbench.jpg)
