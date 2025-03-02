---
title: Style-Guided Purple Image Generator
emoji: 🎨
colorFrom: purple
colorTo: indigo
sdk: gradio
sdk_version: "3.50.2"
app_file: app.py
pinned: false
---

# Style-Guided Image Generation with Purple Enhancement

This Space demonstrates the use of various textual inversion style embeddings with Stable Diffusion, combined with a custom purple color enhancement technique.

## Features

- **Multiple Style Options**: Choose from 5 different artistic styles:
  - Glitch Core (`001glitch-core`)
  - Roth Style (`2814-roth`)
  - Night Style (`4tnght`)
  - 80s Anime (`80s-anime-ai`)
  - Anime AI Being (`80s-anime-ai-being`)

- **Purple Guidance**: Optional color enhancement that adds purple tones to the generated images
- **Customizable Parameters**:
  - Adjustable seed for reproducibility
  - Control over purple guidance strength
  - Custom prompt input

## How to Use

1. Enter your prompt in the text box
2. Select a style from the radio buttons
3. (Optional) Adjust the seed number for different variations
4. (Optional) Enable purple guidance and adjust its strength
5. Click "Submit" to generate the image

## Examples

The app includes several example combinations that you can try:
- Mountain landscape with glitch effect
- Magical forest in 80s anime style
- Cyberpunk city with night style

## Technical Details

This application uses:
- Stable Diffusion v1.4 as the base model
- Textual Inversion embeddings from the Hugging Face Hub
- Custom purple color guidance implementation
- Gradio for the user interface

## Credits

Style embeddings are from the [SD Concepts Library](https://huggingface.co/sd-concepts-library) on Hugging Face.

## License

This project is released under the MIT License. The used models and embeddings maintain their original licenses. 
