## AI Agent for Complaint Handling Emails

This project builds an **Agentic AI system** that automates the process of categorizing customer complaints and drafting tailored email responses using a combination of fine-tuned and lightweight language models.

### 🔧 Key Features

- **Hybrid Model Architecture**: Combines a LoRA-tuned, quantized **BERT classifier** for complaint categorization with the **TinyLLaMA-1.1B** model to generate context-aware, human-like email replies.
- **High Accuracy Classification**: Achieved **84% accuracy and F1 score** on a dataset of over 10,000 labeled customer complaints.
- **Sentiment-Aware Responses**: Integrated **DistilBERT-based sentiment analysis** to adjust the tone and style of email responses based on the emotional content of the complaint.
- **Customizable Outputs**: Email templates are dynamically adjusted to match company communication styles and situational context, enabling smooth integration with existing customer support workflows.

### 🚀 Use Cases

- Automating customer support responses
- Assisting agents in drafting personalized replies
- Enhancing complaint triaging systems with LLMs
