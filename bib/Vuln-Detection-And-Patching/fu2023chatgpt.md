@inproceedings{fu2023chatgpt,
  title={Chatgpt for vulnerability detection, classification, and repair: How far are we?},
  author={Fu, Michael and Tantithamthavorn, Chakkrit Kla and Nguyen, Van and Le, Trung},
  booktitle={2023 30th Asia-Pacific Software Engineering Conference (APSEC)},
  pages={632--636},
  year={2023},
  organization={IEEE}
}

# Abstract:
Large language models (LLMs) like ChatGPT (i.e., gpt-3.5-turbo and gpt-4) exhibited remarkable advancement in a range of software engineering tasks associated with source code such as code review and code generation. In this paper, we undertake a comprehensive study by instructing ChatGPT for four prevalent vulnerability tasks: function and line-level vulnerability prediction, vulnerability classification, severity estimation, and vulnerability repair. We compare ChatGPT with state-of-the-art language models designed for software vulnerability purposes. Through an empirical assessment employing extensive real-world datasets featuring over 190,000 C/C++ functions, we found that ChatGPT achieves limited performance, trailing behind other language models in vulnerability contexts by a significant margin. The experimental outcomes highlight the challenging nature of vulnerability prediction tasks, requiring domain-specific expertise. Despite ChatGPT's substantial model scale, exceeding that of source code-pre-trained language models (e.g., CodeBERT) by a factor of 14,000, the process of fine-tuning remains imperative for ChatGPT to generalize for vulnerability prediction tasks. We publish the studied dataset, experimental prompts for ChatGPT, and experimental results at https://github.com/awsm-research/ChatGPT4Vul.