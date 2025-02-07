@inproceedings{liu2024exploration,
  title={Exploration On Prompting LLM With Code-Specific Information For Vulnerability Detection},
  author={Liu, Zhihong and Yang, Zezhou and Liao, Qing},
  booktitle={2024 IEEE International Conference on Software Services Engineering (SSE)},
  pages={273--281},
  year={2024},
  organization={IEEE}
}


# Abstract:
Software vulnerability detection is a software se- curity analysis technique that aims to recognize possible code vulnerabilities and weaknesses. The majority of previous research has primarily concentrated on deep learning models. Recently, with the rapid development of large language mod- els, researchers are exploring the use of G PT in the field of vulnerability detection. However, these works inadequately account for the features of vulnerability detection, lacking specific prompts and code-specific information. This paper primarily investigates the impact of prompts for GPT. We design the following prompts step by step: basic prompts, prompts with code-specific information, and chain-of-thought (CoT) prompts. Firstly, we explore the performance using basic prompts in the field of vulnerability detection. Subsequently, we incorporate code-specific information into basic prompts, focusing primarily on similar code and data flow graph (DFG). The similar code is obtained through our designed code search algorithm, which takes into account both code semantic and structural information. Finally, we further introduce CoT prompts to inspire GPT's ability for gradually detecting vulnerability. We also conduct experiments to explore the impact of the position of code- specific information in the prompts and the suitable temperature value for the vulnerability detection task. Our experiment results demonstrate that, combined with code-specific information and CoT, GPT can detect vulnerabilities more effectively.