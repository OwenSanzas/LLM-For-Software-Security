@inproceedings{mahyari2024harnessing,
  title={Harnessing the Power of LLMs in Source Code Vulnerability Detection},
  author={Mahyari, Andrew A},
  booktitle={MILCOM 2024-2024 IEEE Military Communications Conference (MILCOM)},
  pages={251--256},
  year={2024},
  organization={IEEE}
}


# Abstract:
Software vulnerabilities, caused by unintentional flaws in source code, are a primary root cause of cyberattacks. Static analysis of source code has been widely used to detect these unintentional defects introduced by software developers. Large Language Models (LLMs) have demonstrated human-like conversational abilities due to their capacity to capture complex patterns in sequential data, such as natural languages. In this paper, we harness LLMs’ capabilities to analyze source code and detect known vulnerabilities. To ensure the proposed vulnerability detection method is universal across multiple programming languages, we convert source code to LLVM IR and train LLMs on these intermediate representations. We conduct extensive experiments on various LLM architectures and compare their accuracy. Our comprehensive experiments on real-world and synthetic codes from NVD and SARD demonstrate high accuracy in identifying source code vulnerabilities.