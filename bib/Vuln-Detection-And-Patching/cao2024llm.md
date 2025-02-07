@inproceedings{cao2024llm,
  title={LLM-CloudSec: Large Language Model Empowered Automatic and Deep Vulnerability Analysis for Intelligent Clouds},
  author={Cao, Daipeng and Jun, W},
  booktitle={IEEE INFOCOM 2024-IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS)},
  pages={1--6},
  year={2024},
  organization={IEEE}
}


# Abstract:
The advance of intelligent cloud applications has brought attention to potential security vulnerabilities. Vulnerability detection is a critical step in ensuring the security of cloud applications. However, traditional techniques for vulnerability detection, such as static and dynamic analysis, are challenging to apply in heterogeneous cloud environments. Using data-driven methods such as Machine Learning (ML) to automate vulnerability detection in cloud applications shows promise. However, current ML solutions are limited to coarse-grained vulnerability categorization and function-level analysis. Therefore, we propose LLM-CloudSec, an unsupervised approach to fine-grained vulnerability analysis based on the Large Language Model (LLM). LLM-CloudSec uses Retrieval Augmented Generation (RAG) and the Common Weakness Enumeration (CWE) as an external knowledge base to improve its ability to detect and analyze vulnerabilities. We conduct experiments on the Juliet C++ test suite, and the results show that LLM-CloudSec enables CWE-based vulnerability classification and line-level vulnerability analysis. Additionally, we applied LLM-CloudSec to the D2A dataset, which was collected from real-world scenarios. We obtained 1230 data entries labelled with CWE and detailed vulnerability analysis. To foster related research, we publish our work on https://github.com/DPCa0/LLM-CloudSec.

