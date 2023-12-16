# Phi 2 Inference

This code snippet demonstrates the use of the `microsoft/phi-2` model for text generation based on a given prompt. It utilizes the Hugging Face `transformers` library to access the model and tokenizer.

### Objective
The primary goal of this code is to generate text based on a specific prompt using the Phi 2 language model.

### Installation
Ensure you have the required dependencies installed by running:
```bash
pip install transformers sentencepiece accelerate bitsandbytes einops
```

### Usage
- Clone or download the repository containing this code.
- Open and run the provided Jupyter notebook file (Phi 2 Inference.ipynb) in an environment compatible with Jupyter notebooks.
- Ensure the code cell that installs necessary packages is executed to install required dependencies.
- Modify the prompt variable to specify your desired input prompt for text generation.
- Execute the code cell containing the text generation logic.
  
### Code Overview
- Tokenizer and Model Prep:
  This section initializes the tokenizer and model from the microsoft/phi-2 pretrained model using the AutoTokenizer and AutoModelForCausalLM classes from the transformers library.
- Text Generation:
The code generates text based on the provided prompt using the initialized model and tokenizer. It encodes the prompt, generates new tokens, and decodes the output to provide the generated text.

### Additional Notes
This code snippet relies on specific models and libraries from the Hugging Face transformers ecosystem. Ensure internet connectivity to access the pretrained model.
Adjusting parameters like max_new_tokens and temperature can influence the generated text's length and diversity.

### References
Original file located at Colab Notebook
Model used: microsoft/phi-2 from Hugging Face model hub
