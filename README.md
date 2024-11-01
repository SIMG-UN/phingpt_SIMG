# PhinGPT: Open-Source Financial Large Language Model

[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![PyPI](https://img.shields.io/pypi/v/phingpt.svg)](https://pypi.org/project/phingpt/)
![License](https://img.shields.io/github/license/yourorg/phingpt.svg?color=brightgreen)
![Issues](https://img.shields.io/github/issues-raw/yourorg/phingpt?label=Issues)
![Open PRs](https://img.shields.io/github/issues-pr-raw/yourorg/phingpt?label=Open+PRs)

<div align="center">
  <img align="center" width="30%" alt="image" src="https://github.com/AI4Finance-Foundation/FinGPT/assets/31713746/e0371951-1ce1-488e-aa25-0992dafcc139">
</div>

## Overview

PhinGPT is an open-source, fine-tuned version of the Phi-3 language model, specifically tailored for the financial sector. It aims to provide a highly accessible, cost-effective solution for financial institutions and researchers seeking powerful language models without the hefty expenses typically associated with proprietary systems like BloombergGPT.

With PhinGPT, we bring advanced financial language modeling capabilities to the open-source community, enabling rapid adaptation to new financial data and democratizing access to cutting-edge AI technologies.

## Key Features

- **Fine-Tuned for Finance**: PhinGPT is fine-tuned on a rich corpus of financial data, offering unparalleled performance in tasks such as sentiment analysis, market forecasting, and financial news summarization.
  
- **Cost-Effective Adaptation**: Unlike large, proprietary models, PhinGPT can be fine-tuned at a fraction of the cost, making it feasible to update regularly with the latest market data.

- **Open-Source and Accessible**: PhinGPT is fully open-source, hosted on [Hugging Face](https://huggingface.co/phingpt), and comes with detailed documentation and examples to get you started quickly.


## Getting Started

To get started with PhinGPT, you can install it via pip:

```bash
pip install phingpt
```

Explore the [Hugging Face model page](https://huggingface.co/phingpt) for pre-trained models and example implementations.

## Usage Example

Here is a quick example of how to use PhinGPT for financial sentiment analysis:

```python
from phingpt import PhinGPT

model = PhinGPT.from_pretrained("phingpt/financial-sentiment")
input_text = "Apple Inc. shows promising growth in the last quarter."
output = model.generate(input_text)
print(output)
```

## Why PhinGPT?

1. **Timely Adaptation**: Financial markets are constantly evolving. PhinGPT allows for frequent, lightweight model updates, ensuring that the insights you derive are always up to date.
  
2. **Democratizing Financial AI**: By making advanced financial models accessible to everyone, PhinGPT levels the playing field in the finance industry.
  
3. **Customization**: With built-in RLHF, PhinGPT can be fine-tuned to meet specific needs, whether you're building a robo-advisor, automating financial reporting, or conducting high-frequency trading.

## Contributing

We welcome contributions from the community! Whether it's improving the model, adding new features, or fixing bugs, your input helps make PhinGPT better for everyone. Please check our [contributing guidelines](CONTRIBUTING.md) for more details.

## License

PhinGPT is released under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

PhinGPT is inspired by the work done on FinGPT and leverages the open-source community's collective knowledge to build robust financial AI tools.

---

For more detailed tutorials, updates, and discussions, join our [Discord community](https://discord.gg/phingpt).

---

### What's New

- **[Model Release] Sep 2024**: PhinGPT-Forecaster, a powerful tool for market predictions, is now available!
- **[Paper Acceptance] Aug 2024**: Our paper on PhinGPT's application in financial sentiment analysis has been accepted at the NeurIPS 2024 workshop!

--- 

Stay tuned for more updates as we continue to improve and expand the capabilities of PhinGPT!