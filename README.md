# For Egune Task

## Introduction

I (Duke) made this project to finetune TTS and STT models on a Mongolian Dataset.

## Features

- Fine-tunes model for Mongolian speech synthesis.
- Uses Hugging Face for dataset import and export.
- Evaluates with Word Error Rate (WER).
- Push trained model to Hugging Face Hub.

## Installation

### Step 1. Clone the repo:

```bash
git clone https://github.com/dgduksict/tts-egune.git
cd tts-egune
```

### Step 2. Create a virtual environment:

If on Linux or MacOS:

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### Step 3. Install dependencies:

```bash
pip install -r requirements.txt
```

### Step 4. Log in to Hugging Face Hub:

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
