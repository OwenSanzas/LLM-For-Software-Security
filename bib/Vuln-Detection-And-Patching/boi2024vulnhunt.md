@inproceedings{boi2024vulnhunt,
  title={VulnHunt-GPT: a Smart Contract vulnerabilities detector based on OpenAI chatGPT},
  author={Boi, Biagio and Esposito, Christian and Lee, Sokjoon},
  booktitle={Proceedings of the 39th ACM/SIGAPP Symposium on Applied Computing},
  pages={1517--1524},
  year={2024}
}


# Abstract:
Smart contracts are self-executing programs that can run on a blockchain. Due to the fact of being immutable after their deployment on blockchain, it is crucial to ensure their correctness. For this reason, various approaches for static analysis of smart contracts have been proposed, but they may be on the one hand imprecise or on the other hand difficult to train. In this paper, we propose a novel approach for detecting smart contract vulnerabilities using OpenAI’s Generative Pre-trained Transformer 3 (GPT-3) language model. Our approach, called VulntHunt-GPT, uses GPT-3 to examine Ethereum smart contracts in order to identify the most popular vulnerabilities according to OWASP. We train VulntHunt-GPT on a dataset of smart contract functions and vulnerabilities to improve its accuracy. Our experiments show that VulntHunt-GPT outperforms almost all the existing state-of-the-art approaches in detecting a variety of vulnerabilities, including reentrancy attacks, integer overflow, and uninitialized storage. In addition, we conduct a case study to demonstrate the effectiveness of VulntHunt-GPT in detecting real-world smart contract vulnerabilities. We show that VulntHunt-GPT can identify previously unknown vulnerabilities in popular smart contracts, highlighting its potential for improving smart contract security. Our approach provides a promising direction for using natural language processing techniques to improve smart contract security and reduce the risk of smart contract exploits.