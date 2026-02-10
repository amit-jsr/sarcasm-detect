# Sarcasm Detection with BERT

Dissertation project — fine-tunes BERT (TensorFlow) for sarcasm detection on Reddit data.

## Structure

- `bert-bert/` — BERT- base model (notebook + script)
- `bert-lstm/` — BERT + LSTM variant
- `bert-sentiment/` — BERT + sentiment features variant
- `bert-finetune/` — BERT + base finetuning
- `data/` — dataset (`balanced_politics_subset.csv`)

## Quick start

1. Open the notebook in `bert-bert/` (or another variant) in **Google Colab**.
2. Update the dataset path to `data/balanced_politics_subset.csv` (or keep the Drive path if using Colab with mounted Drive).
3. Run all cells.

## Requirements

TensorFlow 2.x · `tf-models-official` · `tensorflow-hub` · `pandas` · `scikit-learn`

## Output

Model checkpoint: `my_keras_model.h5`

**Publication:** <https://dspace.isical.ac.in/jspui/bitstream/10263/7294/1/Amit%20Jaiswar-cs-19-21.pdf>


## Author
- Amit Jaiswar
