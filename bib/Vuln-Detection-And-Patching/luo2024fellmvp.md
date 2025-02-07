@inproceedings{luo2024fellmvp,
  title={FELLMVP: An Ensemble LLM Framework for Classifying Smart Contract Vulnerabilities},
  author={Luo, Yu and Xu, Weifeng and Andersson, Karl and Hossain, Mohammad Shahadat and Xu, Dianxiang},
  booktitle={2024 IEEE International Conference on Blockchain (Blockchain)},
  pages={89--96},
  year={2024},
  organization={IEEE}
}

# Abstract:
The rapid expansion of smart contracts on blockchain platforms has significantly advanced the automation of transactions and agreements. However, the growing reliance on smart contracts increases security risks due to their immutable nature and interactions with digital assets. Existing vulnerability detection methods often fail to adapt to new and complex attack vectors and struggle to accurately predict specific vulnerability types. This paper introduces FELLMVP 1, a novel framework that integrates ensemble learning with Large Language Models (LLMs) to classify vulnerabilities in smart contracts. FELLMVP starts with the parsing of Solidity files to construct call graphs and Contract-External Function-Call (CEC) files for contract analysis. It fine-tunes eight LLMs, each targeted at detecting specific types of vulnerabilities and culminates and deploys an ensemble model that leverages the collective predictive capabilities of these LLMs. FELLMVP was evaluated on 15,637 real-world smart contracts spanning eight types of vulnerabilities, demonstrating superior performance over existing methods with an accuracy of 98.8% and F1 scores of 88%. FELLMVP also outperforms other LLMs such as Llama2-7b, CodeLlama, and Falcon-7b by 5 % -12 % on F1 score. Additionally, a case study using ChatGPT-4 to locate vulnerable code in smart contracts reveals that FELLMVP's prediction of specific vulnerability types enhances the debugging process compared to binary outcomes.
