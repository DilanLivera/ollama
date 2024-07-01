# Ollama

Ollama is a lightweight, extensible framework for building and running language models on your local machine. It
provides a simple API for creating, running, and managing models and a library of pre-built models that you can easily
use in various applications. With Ollama, you can interact with different models(e.g. Llama 3, explore Mistral, or Gemma
2). You can even customize models by adjusting parameters like temperature for creativity or coherence. Plus, it
supports importing models from GGUF, PyTorch, and Safetensors.

- [Ollama](https://github.com/ollama/ollama)
- [Ollama API](https://github.com/ollama/ollama/blob/main/docs/api.md)

## Open WebUI

Open WebUI(formerly known as Ollama WebUI) is an extensible, feature-rich, and user-friendly self-hosted WebUI designed
to operate entirely offline. It supports various language model (LLM) runners, including Ollama and OpenAI-compatible
APIs.

- [Open WebUI](https://docs.openwebui.com/)
- [open-webui/open-webui: User-friendly WebUI for LLMs (Formerly Ollama WebUI) (github.com)](https://github.com/open-webui/open-webui)

## How To

### Run the Ollama and Open WebUI

- If Docker isn't running, start Docker.
- Open the terminal and change the directory to the directory of the compose file.
- Run `docker compose up`

### Chat using Open WebUI

- Open the browser and go to `http://localhost:8080`
- If you are visiting the Open WebUI for the first time, create an account using the _Sign up_ page.
- To chat, go to **New Chat**, select a model and send a question.

### Use Ollama API

TODO: Add steps for using Ollama API

## Models

### Phi-3 model

Phi-3 is a family of open AI models developed by Microsoft. These models are designed to be small language models (
SLMs). Key points about Phi-3:

The smallest member of the Phi-3 family, Phi-3-mini, is a 3.8B language model. It’s available on Microsoft Azure AI
Studio, Hugging Face, and Ollama. Phi-3-mini supports context lengths of up to 128K tokens, making it versatile for
different tasks. It’s instruction-tuned and optimized for ONNX Runtime, Windows DirectML, and NVIDIA GPUs1.

- [Welcome to the Phi-3 labs using C#.](https://github.com/microsoft/Phi-3CookBook/blob/main/md/07.Labs/Csharp/csharplabs.md?WT.mc_id=academic-00000-brunocapuano)
- [Using Phi-3 & C# with ONNX for text and vision samples](https://devblogs.microsoft.com/dotnet/using-phi3-csharp-with-onnx-for-text-and-vision-samples-md/)
- [Fine-Tuning Phi-3 with Unsloth for Superior Performance on Custom Data](https://medium.com/@mauryaanoop3/fine-tuning-phi-3-with-unsloth-for-superior-performance-on-custom-data-2c14b3c1e90b)
