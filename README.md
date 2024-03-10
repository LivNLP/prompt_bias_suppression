# In-Contextual Gender Bias Suppression for Large Language Models

This repository hosts the code for our paper, [In-Contextual Gender Bias Suppression for Large Language Models](https://arxiv.org/abs/2309.07251).
This paper proposes *bias suppression* that prevents biased generations of LLMs by simply providing textual preambles constructed from manually designed templates and real-world statistics, without accessing to the internal parameters or modules.

## Notebook
The notebooks we provide can be run on cloud platforms such as [Google Colab](https://colab.research.google.com/) or local machines. 
Note that each must [apply](https://llama.meta.com/) to use Llama2 in order to execute code related to Llama2.

| Model              | Experiment       | Colab                                                                                                  | 
| ------------------ | ---------------- | ------------------------------------------------------------------------------------------------------ | 
| [meta-llama/Llama-2-7b-hf](https://huggingface.co/meta-llama/Llama-2-7b-hf)   | Bias Suppression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/LivNLP/prompt_bias_suppression/tree/main/notebook/exp_llama2.ipynb) | 
| [meta-llama/Llama-2-7b-hf](https://huggingface.co/meta-llama/Llama-2-7b-hf)  | Downstream Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/LivNLP/prompt_bias_suppression/tree/main/notebook/downstream_llama2.ipynb) | 
| [openlm-research/open_llama_7b_v2](https://huggingface.co/openlm-research/open_llama_7b_v2)  | Bias Suppression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/LivNLP/prompt_bias_suppression/tree/main/notebook/exp_openllama.ipynb) | 
| [openlm-research/open_llama_7b_v2](https://huggingface.co/openlm-research/open_llama_7b_v2)  | Downstream Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/LivNLP/prompt_bias_suppression/tree/main/notebook/downstream_openllama.ipynb) | 
| [mosaicml/mpt-7b](https://huggingface.co/mosaicml/mpt-7b)  | Bias Suppression | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/LivNLP/prompt_bias_suppression/tree/main/notebook/exp_mpt.ipynb) |
| [mosaicml/mpt-7b](https://huggingface.co/mosaicml/mpt-7b)  | Downstream Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/LivNLP/prompt_bias_suppression/tree/main/notebook/downstream_mpt.ipynb) |

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
