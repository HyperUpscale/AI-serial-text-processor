# Serial API Processor 🚀

A simple yet powerful web application for processing text through AI language models sequentially. Perfect for batch processing text with consistent prompts.

**You can run int on the fly - without installing anything!** (the mimimum requirement is just a free Groq API key)

## Features ✨

- **Multiple AI Providers**
  - Local Ollama models
  - GROQ cloud API
  - Easy to extend for more providers

- **Smart Processing**
  - Process text items sequentially
  - Control number of items to process
  - Real-time progress tracking
  - Auto-save and resume capability

- **User-Friendly Interface**
  - Dark/Light theme
  - Real-time response preview
  - Markdown support
  - Export options (Markdown/Plain Text)

## Quick Start 🏃‍♂️

1. **Setup**
   - For Ollama: Install and run Ollama locally (port 11434)
   - For GROQ: Have your API key ready

2. **Run**
   - Open `single-html/creator.html` in your browser
   - Select your provider and model
   - Enter your API key if using GROQ

3. **Use**
   - Enter your prompt template
   - Add your text items (one per line)
   - Set number of items to process
   - Click Generate!

## Tips 💡

- Use `{{input}}` in your prompt to mark where each text item should go
- Watch the debug info in the top-right corner for timing stats
- Processing can be resumed if interrupted
- Your theme preference and API key are saved locally

## Requirements 🔧

- Modern web browser
- For Ollama: Local Ollama installation
- For GROQ: Valid API key

## Privacy 🔒

- API keys are stored in browser's localStorage
- No data is sent to external servers except the chosen AI provider
- All processing happens in your browser

## License 📄

MIT License - Feel free to use and modify!
