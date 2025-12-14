<div align="center">

</div>

# Jarvis: Multimodal Live Assistant

A real-time, multimodal AI assistant built with React and the Google GenAI SDK. Jarvis integrates live audio and video streaming with advanced AI capabilities, including real-time conversation, internet search, and image generation, powered by Gemini 2.5 Flash and Nano Banana Pro (Gemini 3 Pro Image Preview).

[**Watch Demo Video**](https://www.linkedin.com/feed/update/urn:li:activity:7405299691761889280/)

**Try the app in AI Studio:** [https://aistudio.google.com/apps/drive/1wx874xhoXGo_RJn9IvnsyJmG-hhQK8wI?showPreview=true&showAssistant=true](https://aistudio.google.com/apps/drive/1wx874xhoXGo_RJn9IvnsyJmG-hhQK8wI?showPreview=true&showAssistant=true)  
*(Note: Requires a billing account for Nano Banana Pro usage)*

## Documentation

- **[Architecture](docs/ARCHITECTURE.md)**: Overview of the technical stack, core services (`LiveService`, `ToolService`), and data flow.
- **[API Keys & Configuration](docs/API_KEYS.md)**: Instructions for setting up the app with **Gemini Developer API** (AI Studio) or **Vertex AI** (Google Cloud).
- **[Prompt](docs/PROMPT.md)**: The original system prompt used to bootstrap the application.

## Resources
- [How to use Gemini Live API with Native Audio in Vertex AI](https://cloud.google.com/blog/topics/developers-practitioners/how-to-use-gemini-live-api-native-audio-in-vertex-ai?e=48754805)

## Usage / What can you say to Jarvis?

The app uses the Live API with Search grounding and image generation/reimagination capabilities. Here are some example prompts to try:

- "Hello Jarvis, can you tell me today's weather in San Francisco?"
- "Jarvis, can you create a photo of a futuristic city skyline at sunset?"
- "Jarvis, please take a photo of me and reimagine it as if I'm in a castle."

## Run Locally

**Prerequisites:** Node.js

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Configure Environment:**
   Set the `GEMINI_API_KEY` (or Vertex credentials) in `.env.local`. See [API Keys & Configuration](docs/API_KEYS.md) for details.

3. **Run the app:**
   ```bash
   npm run dev
   ```


