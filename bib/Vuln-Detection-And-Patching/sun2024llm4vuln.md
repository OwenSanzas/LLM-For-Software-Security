@article{sun2024llm4vuln,
  title={Llm4vuln: A unified evaluation framework for decoupling and enhancing llms' vulnerability reasoning},
  author={Sun, Yuqiang and Wu, Daoyuan and Xue, Yue and Liu, Han and Ma, Wei and Zhang, Lyuye and Liu, Yang and Li, Yingjiu},
  journal={arXiv preprint arXiv:2401.16185},
  year={2024}
}


# Abstract:
Large language models (LLMs) have demonstrated significant potential in various tasks, including those requiring human-level intelligence, such as vulnerability detection. However, recent efforts to use LLMs for vulnerability detection remain preliminary, as they lack a deep understanding of whether a subject LLM's vulnerability reasoning capability stems from the model itself or from external aids such as knowledge retrieval and tooling support.
In this paper, we aim to decouple LLMs' vulnerability reasoning from other capabilities, such as vulnerability knowledge adoption, context information retrieval, and advanced prompt schemes. We introduce LLM4Vuln, a unified evaluation framework that separates and assesses LLMs' vulnerability reasoning capabilities and examines improvements when combined with other enhancements.
We conduct controlled experiments using 147 ground-truth vulnerabilities and 147 non-vulnerable cases in Solidity, Java and C/C++, testing them in a total of 3,528 scenarios across four LLMs (GPT-3.5, GPT-4, Phi-3, and Llama 3). Our findings reveal the varying impacts of knowledge enhancement, context supplementation, and prompt schemes. We also identify 14 zero-day vulnerabilities in four pilot bug bounty programs, resulting in $3,576 in bounties.