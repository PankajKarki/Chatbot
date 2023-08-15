
# Streamlit Chatbot with OpenAI GPT-3 Integration

This is a Streamlit app that demonstrates a chatbot powered by OpenAI's GPT-3.5 Turbo model. The chatbot engages in conversations with users, providing information about product titles and descriptions based on uploaded images.

## Features

- Upload an image to initiate a conversation about the product.
- Chat with the AI assistant and get responses powered by GPT-3.5 Turbo.
- Maintain conversation history and user inputs.
- Dynamically generate initial messages based on the uploaded image.

## Prerequisites

- Python 3.6 or higher
- Streamlit
- OpenAI Python SDK
- Streamlit Chat (if used)

## Setup

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install the required Python packages:

   ```bash
   pip install streamlit openai streamlit-chat  # If using Streamlit Chat
   ```

3. Set up your OpenAI API key by replacing `'YOUR_OPENAI_API_KEY'` with your actual OpenAI API key in the `openai.api_key` assignment.

4. Run the Streamlit app:

   ```bash
   streamlit run your_app_name.py
   ```

Replace `your_app_name.py` with the actual filename of your Streamlit app.

## Usage

1. Open the Streamlit app using the provided URL in your browser.
2. Upload an image of a product to start a conversation.
3. The AI assistant will respond with information about the product title and description.
4. You can interact with the chatbot by typing your messages in the input box.
5. The conversation history will be displayed along with AI responses.


## Disclaimer

Please keep in mind that this is a sample project and may require further customization for production use. Additionally, usage of the OpenAI API might involve costs depending on your OpenAI subscription.

---

Feel free to customize this README template according to your project's specifics and add any additional details that might be relevant.
