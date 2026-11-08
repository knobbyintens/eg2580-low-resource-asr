# Whisper-Based Low-Resource Speech Recognition for African Languages

Official implementation for the paper **"Whisper-Based Low-Resource Speech Recognition for African Languages"**, accepted at Interspeech 2025.

## Status

**Released.** The complete training code, evaluation scripts, configuration files
and pretrained checkpoints are publicly available in this repository.

## Repository layout

```
├── src/          core model and training code
├── data/         data preparation and splits
├── experiments/  experiment configurations
├── results/      evaluation tables and figures
├── notebooks/    analysis notebooks
└── tests/        unit tests
```

## Quick start

```bash
git clone https://github.com/knobbyintens/eg2580-low-resource-asr.git
cd eg2580-low-resource-asr
pip install -r requirements.txt
python src/train.py --config experiments/interspeech2025.yaml
```

## Citation

```bibtex
@inproceedings{brooks2025lowresasr,
  title={Whisper-Based Low-Resource Speech Recognition for African Languages},
  author={Brooks, Stephen and others},
  booktitle={Interspeech 2025},
  year={2025}
}
```
