# Simple A/B Testing 🧪

This is a simple app for A/B testing that is **work-in-progress**. It's powered by Streamlit and Google Forms for gathering feedback.

The Streamlit app allows you to switch between two Text Classification models, BART and DistilBert, from the HuggingFace Hub for **sentiment detection**. 

Via Google Forms, you can gather feedback on the models' performance for detecting sentiments in text (e.g., for testing the models on challenging, sarcastic prompts if you wish). 

## How to make it your own!

1. Clone the code here and pip install the requirements (`pip install -r requirements.txt`)
2. Adjust the app with your own ML/AI models and [Google Form links](https://support.google.com/a/users/answer/9303071?hl=en).
3. To deploy your own Streamlit app, with a URL anyone can access publicly, check out [the Streamlit Community Cloud documentation](https://docs.streamlit.io/deploy/streamlit-community-cloud/deploy-your-app)

## What's next?
This is a simple prototype. Additional implementations, and incorporation of causal models, are coming soon!
