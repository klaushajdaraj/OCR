# OCR Application using Gemma-3

This project leverages Gemma-3 vision capabilities and Streamlit to create a 100% locally running computer vision app that can perform both OCR and extract structured text from the image.

## Installation and setup

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama pillow
   ```

**Setup Ollama**:
   ```bash
   # setup ollama on linux 
   curl -fsSL https://ollama.com/install.sh | sh
   ```

   ```bash
   # pull gemma-3 vision model
   ollama run gemma3:12b
   ```
---

Made with ❤️ using Gemma-3 Vision Model