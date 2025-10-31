# How the Machine Learning Sausage is Made: Evaluating Harmful Language Detection Models

This repository contains supplementary data and code for the paper "How the Machine Learning Sausage is Made: Evaluating Harmful Language Detection Models". It includes the implementation and evaluation of various machine learning models for detecting different types of harmful language on social media.

## Repository Structure

The repository contains models and datasets for five types of harmful language detection:

1. **Bullying Detection** (`/Bully/`)
2. **Hate Speech Detection** (`/Hate/`)
3. **Offensive Language Detection** (`/Offensive/`)
4. **Racism Detection** (`/Racism/`)
5. **Threat Detection** (`/Threat/`)

Each directory contains relevant models, notebooks, and datasets specific to that category of harmful language detection.

## Data Collection
All Twitter datasets were collected using [Apify.com](https://apify.com)'s Twitter scraping tools. The data collection process adhered to Twitter's terms of service and ethical guidelines for research data collection.

## Model Evaluation
Each model was evaluated using standard metrics including:
- Precision
- Recall
- F1 Score
- Accuracy
- ROC-AUC

Detailed evaluation metrics and analysis can be found in the respective notebook files within each model's directory.

## Usage
Each notebook is self-contained and includes:
- Data preprocessing steps
- Model implementation/loading
- Training procedures (where applicable)
- Evaluation metrics
- Results visualization

## Requirements
The models use various Python libraries including:
- PyTorch
- Transformers (Hugging Face)
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Citation
If you use this code or data in your research, please cite:

```bibtex
@article{yourpaper2025,
  title={How the Machine Learning Sausage is Made: Evaluating Harmful Language Detection Models},
  author={[Author Names]},
  journal={[Journal Name]},
  year={2025}
}
```

## License
This repository is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions about the code or data, please open an issue in this repository.

## Acknowledgments
We thank all the researchers and organizations who made their models and datasets publicly available for evaluation.
How the Machine Learning Sausage is Made:  Evaluating Harmful Language Detection Models
