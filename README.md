# In-Contextual Gender Bias Suppression for Large Language Models

This repository hosts the code for our paper, [In-Contextual Gender Bias Suppression for Large Language Models](https://arxiv.org/abs/2309.07251).
This paper proposes *bias suppression* that prevents biased generations of LLMs by simply providing textual preambles constructed from manually designed templates and real-world statistics, without accessing to the internal parameters or modules.

## Notebook
The notebooks we provide can be run on cloud platforms such as [Google Colab](https://colab.research.google.com/) or local machines. 
In addition, each must [apply](https://llama.meta.com/) to use Llama2 in order to execute code related to Llama2.

| Model              | Experiment       | Colab                                                                                                  | 
| ------------------ | ---------------- | ------------------------------------------------------------------------------------------------------ | 
| Llama2             | Bias Suppression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/LivNLP/prompt_bias_suppression/tree/main/notebook/exp_llama2.ipynb) | 
| Llama2             | Downstream Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/LivNLP/prompt_bias_suppression/tree/main/notebook/downstream_llama2.ipynb) | 
| OpenLlama          | Bias Suppression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/LivNLP/prompt_bias_suppression/tree/main/notebook/exp_openllama.ipynb) | 
| OpenLlama          | Downstream Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/LivNLP/prompt_bias_suppression/tree/main/notebook/downstream_openllama.ipynb) | 
| MPT                | Bias Suppression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/LivNLP/prompt_bias_suppression/tree/main/notebook/exp_mpt.ipynb) |
| MPT                | Downstream Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/LivNLP/prompt_bias_suppression/tree/main/notebook/downstream_mpt.ipynb) |

## Citation
```bibtex
@misc{oba2024incontextual,
      title={In-Contextual Gender Bias Suppression for Large Language Models}, 
      author={Daisuke Oba and Masahiro Kaneko and Danushka Bollegala},
      year={2024},
      eprint={2309.07251},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
