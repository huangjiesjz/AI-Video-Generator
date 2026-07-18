# AI Video Generator - v9.00719 Batch Stable Edition

<p align="center">
  <strong>Free Batch AI Video Generation Tool</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Free-100%25%20Free-brightgreen" alt="Free">
  <img src="https://img.shields.io/badge/Resolution-720P-blue" alt="720P">
  <img src="https://img.shields.io/badge/Batch-Supported-orange" alt="Batch">
  <img src="https://img.shields.io/badge/AI-Auto%20Expand%20Prompts-purple" alt="AI Prompts">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-lightgrey" alt="Windows">
</p>

---

AI Video Generator is a **free**, easy-to-use desktop application that leverages the [Agnes AI V2.0](https://agnes-ai.com/) model to generate 720P HD videos from text prompts. No subscription required -- just register and start creating.

## Version: v9.00719 (Batch Stable Edition)

- Complete single/batch video generation workflow
- Material management with upload, replace, and enlarged preview
- History records with task status and direct output folder access
- Keyboard shortcuts: Ctrl+G (single submit), Ctrl+B (batch submit), Ctrl+S (save settings)
- Persistent output directory bar at the top

## Key Features

| Feature | Description |
|---------|-------------|
| 🆓 **Completely Free** | Register on Agnes AI for free. No paid subscription needed. |
| 🎬 **720P Video Generation** | Powered by Agnes AI V2.0 large model for high-quality 720P output. |
| 📦 **Batch Generation** | Submit multiple tasks at once and generate videos in batch. |
| 🤖 **AI Auto-Expand Prompts** | Enter a simple description and AI automatically expands it into a professional prompt. |
| 🖥️ **Desktop Application** | Native Windows WPF app, lightweight and fast. |

## 🚀 Quick Start

### 1. Download

Download the latest release from [Releases](https://github.com/huangjiesjz/AI-Video-Generator/releases) or [Gitee Releases](https://gitee.com/arksoft2026/ai-video-generator-batch/releases) page and extract the ZIP file.

### 2. Run

Double-click `VideoGenerator.Wpf.exe` to launch the application.

### 3. Configure API Key

On first launch, a guide page will appear:

1. Click the link to open [Agnes AI](https://agnes-ai.com/) and register (free, no subscription)
2. After logging in, go to the API platform to create and copy your API Key
3. Paste the API Key into the global settings in the application

> **API Key only needs to be configured once.** It will be saved and auto-loaded on future launches.

## 💡 How to Use

### Single Video Generation
1. Enter your video description (simple or detailed)
2. AI will auto-expand your prompt if needed
3. Click generate and wait for the output

### Batch Video Generation
1. Prepare a list of prompts (or use the batch template `batch_prompts_template.txt`)
2. Load them into the batch workflow
3. Submit all tasks at once and monitor progress

## 📝 Batch Prompt Tips (Important!)

For **batch prompt generation**, we recommend using **Agnes Code** to let the AI agent help you generate **pure English prompts**. 

### Recommended Format:
- Each prompt should be written in **English only** for maximum accuracy
- Separate different prompts with `---` on a blank line

### Example:

```
A cinematic shot of a futuristic city skyline at sunset, golden light reflecting off glass towers, drones flying between buildings, ultra detailed, 720P.

---

A close-up of a hand holding a glowing smartphone, holographic interface floating above the screen, dark background with bokeh lights, tech commercial style.

---

Time-lapse of a flower blooming in a garden, morning dew drops visible, soft sunlight, macro photography style, nature documentary feel.
```

### Why English Prompts?
- Agnes AI models are optimized for English prompt understanding
- English prompts produce more accurate and higher quality video outputs
- Technical terms and scene descriptions translate more precisely

### Using Agnes Code:
1. Open Agnes Code and activate the AI agent
2. Describe the videos you want to generate
3. The agent will generate professional English prompts
4. Copy the prompts into the batch input (separated by `---`)
5. Submit for batch generation

## 📋 System Requirements

- **OS**: Windows 10 / 11 (x64)
- **Network**: Internet connection required (access to Agnes AI API)
- **RAM**: 4GB minimum recommended
- **Storage**: ~500MB for the application

## 🔒 License

This project is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgements

- [Agnes AI](https://agnes-ai.com/) - AI model provider
- Built with .NET 8 WPF
