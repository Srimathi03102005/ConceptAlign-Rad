# ConceptAlign-Rad
Concept-Aligned Vision-Language Model for Explainable Automated Radiology Report Generation
# ConceptAlign-Rad

## Concept-Aligned Vision-Language Model for
## Explainable Automated Radiology Report Generation

### Project Overview

ConceptAlign-Rad is an AI-based framework for
automated radiology report generation from chest
X-ray images.

The system identifies important medical concepts
from the X-ray and uses these concepts to guide
the generation of clinically meaningful reports.

### Key Components

- Chest X-ray preprocessing
- Radiology report preprocessing
- Vision feature extraction
- Medical concept identification
- Concept alignment
- Qwen2.5-1.5B language model
- LoRA fine-tuning
- Automated evaluation

### Dataset

Dataset:
IU-Xray

The original dataset is not included in this
repository.

### Preprocessing

Image preprocessing:

- Grayscale conversion
- Intensity normalization
- Image resizing to 224 × 224

Text preprocessing:

- XML/tag removal
- Special-character removal
- Text normalization
- Whitespace cleaning
- Tokenization

### Model

Base Language Model:

Qwen2.5-1.5B

Fine-tuning:

LoRA

### Evaluation Metrics

- BLEU
- ROUGE
- BERTScore
- CheXbert F1
- RadGraph F1

### Development Environment

- Python
- PyTorch
- Hugging Face Transformers
- PEFT
- Kaggle Notebook
- GPU: NVIDIA Tesla T4
