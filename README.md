# For Egune Task

I (Duke) made this project to finetune TTS and STT models on a Mongolian Dataset.

## Features

- Fine-tunes model for Mongolian speech synthesis.
- Uses Hugging Face for dataset import and export.
- Evaluates with Word Error Rate (WER).
- Push trained model to Hugging Face Hub.

## Installation

1. Clone the repo:

```bash
git clone https://github.com/dgduksict/tts-egune.git
cd tts-egune
```

2. Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Log in to Hugging Face Hub:

```bash
huggingface-cli login
```

## Usage

Run the following script

```bash
python setup.py
```

```bash
python finetune.py
```

The script will fine-tune the model on the Mongolian speech dataset and evaluate the model's performance. /NOT YET IMPLEMENTED/
