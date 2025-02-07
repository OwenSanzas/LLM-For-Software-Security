@inproceedings{guo2024outside,
  title={Outside the comfort zone: Analysing llm capabilities in software vulnerability detection},
  author={Guo, Yuejun and Patsakis, Constantinos and Hu, Qiang and Tang, Qiang and Casino, Fran},
  booktitle={European symposium on research in computer security},
  pages={271--289},
  year={2024},
  organization={Springer}
}


# Abstract:
The significant increase in software production driven by automation and faster development lifecycles has resulted in a corresponding surge in software vulnerabilities. In parallel, the evolving landscape of software vulnerability detection, highlighting the shift from traditional methods to machine learning and large language models (LLMs), provides massive opportunities at the cost of resource-demanding computations. This paper thoroughly analyses LLMs’ capabilities in detecting vulnerabilities within source code by testing models beyond their usual applications to study their potential in cybersecurity tasks. We evaluate the performance of six open-source models that are specifically trained for vulnerability detection against six general-purpose LLMs, three of which were further fine-tuned on a dataset that we compiled. Our dataset, alongside five state-of-the-art benchmark datasets, were used to create a pipeline to leverage a binary classification task, namely classifying code into vulnerable and non-vulnerable. The findings highlight significant variations in classification accuracy across benchmarks, revealing the critical influence of fine-tuning in enhancing the detection capabilities of small LLMs over their larger counterparts, yet only in the specific scenarios in which they were trained. Further experiments and analysis also underscore the issues with current benchmark datasets, particularly around mislabeling and their impact on model training and performance, which raises concerns about the current state of practice. We also discuss the road ahead in the field suggesting strategies for improved model training and dataset curation.