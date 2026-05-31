# CSCA 5112: Introduction to Generative AI

CSCA 5112 · [Generative AI Specialization](https://github.com/cu-mscso/specialization-generative-ai) · CU Boulder MSCS via Coursera

**Instructor:** Dr. Bobby Hodgkinson · **Duration:** ~15 hours · **Level:** Introductory

## Overview

Introduces generative AI through hands-on exploration of text, image, and audio tools. Covers the theoretical foundations and practical mathematics behind key generative models — ChatGPT, Transformers, GANs, and Diffusion Models — while building skills in prompt engineering and responsible AI use.

## Modules

| Week | Title | Topics |
|------|-------|--------|
| 1 | Talking to a Machine like a Human | Language model basics, prompt engineering fundamentals, the role of context |
| 2 | Choosing the Right Tool for the Task | Embeddings, RAG, Transformers, Diffusion Models, GANs, VAEs, NotebookLM |
| 3 | Transformer | Attention mechanisms, context windows, tokenization, iterative prompt refinement |
| 4 | Know the Limits, Spot the Bias | Hallucinations, bias, training cutoffs, the Three R's (Responsibility, Red Flags, RAG) |
| 5 | Final Project | Capstone: reflection, application, and evaluation |

## Topics Covered

- Generative model architectures: Transformers, GANs, Diffusion Models, VAEs
- Prompt and context engineering
- Retrieval-Augmented Generation (RAG)
- Embeddings and similarity search
- AI limitations: hallucinations, bias, knowledge cutoffs
- Responsible AI principles

## Prerequisites

Basic to intermediate Linear Algebra (vectors, matrices, trigonometry). No prior AI/ML experience required.

## Setup

```shell
pyenv virtualenv 3.12 $(basename $PWD)
pyenv local $(basename $PWD)
pip install -r requirements.txt
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please reach out to [Abdul Mohammed](https://github.com/am368a) or open an issue on GitHub.
