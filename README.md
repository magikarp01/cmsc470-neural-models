# cmsc470-neural-models
Project For Neural Models for Text, testing LLaMA 3 for Question Generation

# Setup:
Get a Vast instance with the pytorch:latest Docker image. Tested all on python=3.10. You need an 80 GB model to train the LoRAs (I used A100), and a 24 GB model if you just want to run inference.

You might also need access to LLaMA 3: request here https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct

Run:
- pip install -r requirements.txt
- conda install -c anaconda ipykernel
- login with huggingface-cli login
