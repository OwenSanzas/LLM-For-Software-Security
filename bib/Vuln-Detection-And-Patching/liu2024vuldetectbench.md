@article{liu2024vuldetectbench,
  title={VulDetectBench: Evaluating the Deep Capability of Vulnerability Detection with Large Language Models},
  author={Liu, Yu and Gao, Lang and Yang, Mingxin and Xie, Yu and Chen, Ping and Zhang, Xiaojin and Chen, Wei},
  journal={arXiv preprint arXiv:2406.07595},
  year={2024}
}


# Abstract:
Large Language Models (LLMs) have training corpora containing large amounts of program code, greatly improving the model’s code comprehension and generation capabilities. However, sound comprehensive research on detecting program vulnerabilities, a more specific task related to code, and evaluating the performance of LLMs in this more specialized scenario is still lacking. To address common challenges in vulnerability analysis, our study introduces a new benchmark, VulDetectBench, specifically designed to assess the vulnerability detection capabilities of LLMs. The benchmark comprehensively evaluates LLM’s ability to identify, classify, and locate vulnerabilities through five tasks of increasing difficulty. We evaluate the performance of 17 models (both open- and closed-source) and find that while existing models can achieve over 80% accuracy on tasks related to vulnerability identification and classification, they still fall short on specific, more detailed vulnerability analysis tasks, with less than 30% accuracy, making it difficult to provide valuable auxiliary information for professional vulnerability mining. Our benchmark effectively evaluates the capabilities of various LLMs at different levels in the specific task of vulnerability detection, providing a foundation for future research and improvements in this critical area of code security. VulDetectBench is publicly available at https://github.com/Sweetaroo/VulDetectBench.