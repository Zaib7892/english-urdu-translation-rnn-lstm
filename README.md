# English ↔ Urdu Translation with RNN and LSTM

This repository contains a notebook-based NLP project for sequence-to-sequence style machine translation experiments between English and Urdu using recurrent neural networks (RNN) and long short-term memory networks (LSTM).

## Project Contents

- `translater.ipynb` — main notebook for preprocessing, model building, training, and evaluation.
- `dataset.xlsx` — parallel English/Urdu dataset used by the notebook.
- `requirements.txt` — Python dependencies.
- `Report.docx` — project report/documentation.

## Objectives

- Prepare and clean bilingual sentence pairs for model training.
- Train and compare RNN and LSTM-based translation models.
- Evaluate translation quality (e.g., accuracy/BLEU-style comparison depending on notebook configuration).
- Highlight practical limitations of vanilla RNNs and improvements from LSTM.

## Setup

### 1) Clone the repository

```bash
git clone <your-repo-url>
cd english-urdu-translation-rnn-lstm
```

### 2) Create a virtual environment (recommended)

```bash
python -m venv .venv
source .venv/bin/activate   # Linux/macOS
# .venv\\Scripts\\activate   # Windows PowerShell
```

### 3) Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the notebook:

```bash
jupyter notebook translater.ipynb
```

Then execute cells in order to:
1. Load and preprocess dataset entries from `dataset.xlsx`.
2. Tokenize and encode English/Urdu sequences.
3. Train RNN and LSTM models.
4. Evaluate outputs and compare model behavior.

## Notes

- The project is currently notebook-centric, so configuration and training steps are defined inside `translater.ipynb`.
- If you change dataset paths or column names, update the relevant notebook cells.

## Potential Improvements

- Add attention mechanisms to improve long-sequence translation.
- Convert notebook workflow into reusable Python modules/scripts.
- Add reproducible experiment tracking and fixed random seeds.
- Extend evaluation with standardized BLEU/ROUGE reporting and qualitative examples.

## Contributing

Contributions are welcome. You can:
- open an issue for bugs or ideas,
- submit a pull request with improvements,
- share better preprocessing or model architectures.

## License

No license file is currently included. Add a `LICENSE` file if you plan to distribute or reuse this project publicly.
