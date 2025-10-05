# GPT-2 Text Generation Project

This project demonstrates how to fine-tune the pre-trained GPT-2 model from HuggingFace Transformers on a custom text dataset and generate coherent text samples based on user prompts.

## Features
- Loads GPT-2 model and tokenizer
- Fine-tunes GPT-2 on a sample custom dataset
- Generates text samples from user input prompts
- Saves generated samples to `generated_samples.txt`
- Runs on CPU or GPU

## Setup Instructions

### 1. Clone the repository
```
git clone https://github.com/dib008/gpt2-text-generation.git
cd gpt2-text-generation
```

### 2. Install dependencies
It is recommended to use a virtual environment:
```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### 3. Run the script
```
python gpt2_generation.py
```

## Usage
- The script will load the GPT-2 model and fine-tune it on a small sample dataset.
- Enter a prompt when asked to generate text.
- Generated text will be displayed and saved to `generated_samples.txt`.
- Type `exit` to quit the program.

## Fine-tuning Details
- The script uses a dummy dataset (`sample_dataset.txt`) for demonstration.
- Fine-tuning runs for 1 epoch for quick setup.
- You can replace `sample_dataset.txt` with your own text data for custom fine-tuning.

## Environment
- Works on Linux, macOS, and Windows
- Compatible with CPU and GPU (CUDA if available)

## Error Handling
- The script includes error handling for model loading, text generation, and file operations.

## Customization
- To use your own dataset, replace the contents of `sample_dataset.txt`.
- Adjust training parameters in `gpt2_generation.py` as needed.

## License
This project is for educational purposes.