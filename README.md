# text-summarization-tool

A text summarization tool built using Hugging Face Transformers and Gradio. This tool generates concise summaries of long texts using state-of-the-art NLP models like BART and T5. The project is implemented in a Google Colab notebook for easy experimentation and deployment.

### Features
**Abstractive Summarization**: Generates new sentences that capture the essence of the original text.

**Customizable Summary Length**: Adjust the max_length and min_length parameters to control the summary size.

**User-Friendly Interface**: Built with Gradio for easy interaction.

**Pre-trained Models**: Uses Hugging Face's facebook/bart-large-cnn model for high-quality summaries.

### How to Use
**1. Open the Colab Notebook**

Click the button below to open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zanxibar/text-summarization-tool/blob/main/Text_Summarization_Tool_with_facebook_bart_large_cnn.ipynb)

**2. Run the Notebook**
Open the Notebook: Click the "Open in Colab" button above.

Run All Cells: Execute all cells in the notebook by clicking Runtime > Run all.

Interact with the Tool: Use the Gradio interface to input text and generate summaries.

### Code Overview
The Colab notebook contains the following sections:

**Install Dependencies**: Installs required libraries like transformers and gradio.

**Load Summarization Model**: Loads the facebook/bart-large-cnn model from Hugging Face.

**Define Summarization Function**: A function to generate summaries based on input text.

**Create Gradio Interface**: A user-friendly interface for interacting with the summarization tool.

**Launch the App**: Deploys the app directly in Colab or generates a public link.

### Deployment

**Run in Colab**
The Gradio app can be run directly in Colab. After running the notebook, you’ll see a Gradio interface embedded in the notebook or a public link to access the app.
