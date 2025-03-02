# LunaAI Model

A customized LLM model for Ollama.

## Installation

1. **Install Ollama:**
   - Download from [ollama.ai](https://ollama.ai)
   - Follow the installation instructions for your operating system

2. **Download the Luna Modelfile:**
   - Download the `Modelfile` from the "Releases" section of this repository
   - Make sure to use the latest stable release version
   - Save it to a local directory on your computer

3. **Create the Luna model:**
   - Open Terminal/Command Prompt
   - Navigate to the directory containing the Modelfile
   - Run:
     ```
     ollama create luna -f Modelfile
     ```

## Running Luna

After installation, start using Luna with:

```
ollama run luna
```

## Troubleshooting

If you encounter any issues:

1. Make sure Ollama is properly installed
2. Verify the Modelfile is in your current directory
3. Check that you have enough disk space for the model

## Support

If you encounter any issues, please open an issue in this repository.
