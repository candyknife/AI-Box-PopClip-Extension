# AI-Box-PopClip-Extension

AI-Box is an on-the-go PopClip extension that brings the power of ChatGPT to your fingertips. It offers a suite of tools for translation, summarization, grammar correction, and text polishing, all leveraging the capabilities of the OpenAI API.

## Features

- **Translation**: Translate text into Chinese or English with accuracy and fluency.
- **Summarization**: Condense lengthy text into a concise summary.
- **Grammar Correction**: Refine text for grammatical correctness and clarity.
- **Text Polishing**: Enhance text for formal and professional presentation.

## Installation

1. **Download the Extension**: Clone or download this repository to your local machine.
2. **Install PopClip**: Ensure you have PopClip installed on your Mac. 
3. **Add the Extension**: Double-click the `.popcliptxt` extension file in Finder, PopClip will load the snippet from the file and install it.

## Configuration

Before using the extension, you need to configure the following options:

- **API Key**: Your OpenAI API key.
- **API Base Domain**: The base domain for the OpenAI API (default is `https://api.openai.com/v1`).
- **Model**: The GPT model to use (options include `gpt-4o-mini`, `gpt-4o`, `gpt-4-turbo`, `gpt-4`).
- **Custom Model**: Optionally specify a custom model.
- **Temperature**: Controls the randomness of the output (default is `1`).
- **Top P**: Nucleus sampling (default is `0.95`).

These options can be set within the PopClip preferences under the AI-Box extension settings.

## Usage

1. **Select Text**: Highlight the text you wish to process.
2. **Activate PopClip**: Click on the PopClip icon that appears above the selected text.
3. **Choose an Action**: Select one of the AI-Box actions (Translate-zh, Translate-en, Summarize, Grammar, Polish).
4. **Review Output**: The response will automatically appear in the Share-to-Note window by default. Alternatively, you can hold the Option key to append the response.

## License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the PopClip team for creating such a useful tool.
- Special thanks to OpenAI for providing the powerful GPT models.
- Idea inspired by [chatGPTBox](https://github.com/josStorer/chatGPTBox).
