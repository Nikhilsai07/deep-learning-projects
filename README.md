# Deep Learning Projects

Neural-network examples, CIFAR-10 CNN, and a smile detector.

- `src/` — Python scripts
- `datasets/` — Credit CSV and happy/sad image dataset

## Setup
```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```
Run scripts from this folder. CIFAR-10 is obtained through Keras and may download on first run. Smile detector images are in `datasets/smiles_dataset/`.