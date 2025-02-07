@article{shestov2024finetuning,
  title={Finetuning large language models for vulnerability detection},
  author={Shestov, Alexey and Cheshkov, Anton and Levichev, Rodion and Mussabayev, Ravil and Zadorozhny, Pavel and Maslov, Evgeny and Vadim, Chibirev and Bulychev, Egor},
  journal={arXiv preprint arXiv:2401.17010},
  year={2024}
}

# Abstract:
This paper presents the results of finetuning large language models (LLMs) for the task of detecting vulnerabilities in Java source code. We leverage WizardCoder, a recent improvement of the state-of-the-art LLM StarCoder, and adapt it for vulnerability detection through further finetuning. To accelerate training, we modify WizardCoder’s training procedure, also we investigate optimal training regimes. For the imbalanced dataset with many more negative examples than positive, we also explore different techniques to improve classification performance. The finetuned WizardCoder model achieves improvement in ROC AUC and F1 measures on balanced and imbalanced vulnerability datasets over CodeBERT-like model, demonstrating the effectiveness of adapting pretrained LLMs for vulnerability detection in source code. The key contributions are finetuning the state-ofthe-art code LLM, WizardCoder, increasing its training speed without the performance harm, optimizing the training procedure and regimes, handling class imbalance, and improving performance on difficult vulnerability detection datasets. This demonstrates the potential for transfer learning by finetuning large pretrained language models for specialized source code analysis tasks.