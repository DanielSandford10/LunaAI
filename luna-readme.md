# Luna1 Model

A customized LLM model running on Ollama.

## Prerequisites

- [Ollama](https://ollama.ai/) installed on your system
- Compatible with macOS, Linux, and Windows WSL2

## Installation

1. First, install Ollama by following the instructions at [ollama.ai](https://ollama.ai)

2. Clone this repository:
```bash
git clone https://github.com/[your-username]/luna1
cd luna1
```

3. Create the Luna1 model using the provided Modelfile:
```bash
ollama create luna1 -f Modelfile
```

## Usage

Run the model with:
```bash
ollama run luna1
```

For API usage:
```bash
curl http://localhost:11434/api/generate -d '{
  "model": "luna1",
  "prompt": "Your prompt here"
}'
```

## Model Details

[Here you can add specific details about your model's capabilities, any custom parameters, or special features you've added]

## License

[Add your chosen license here]

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

