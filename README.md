# Fine-Tuning Large Language Model with LoRA and 8-bit Qunatization
This repository demonstrates how to fine-tune a large language model (LLM) using the PEFT library, 8-bit quantization with bitsandbytes, and LoRA for parameter efficiency. This example is for educational purposes and may require adjustments for specific tasks.

## Key Features:
- Utilizes the pre-trained facebook/opt-6.7b LLM.
- Achieves significant memory savings with 8-bit quantization.
- Improves parameter efficiency through LoRA, a low-rank adaptation technique.
- Fine-tunes the model on the english_quotes dataset.

## Requirements:
1. Python 3.7+
2. transformers
3. bitsandbytes
4. lora
5. datasets
6. accelerate
7. loralib

## Further Resources:
PEFT Library: https://github.com/huggingface/peft <br>
LoRA: https://arxiv.org/abs/2204.00943  <br>
Hugging Face Transformers: https://huggingface.co/transformers/
