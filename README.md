# SMS Text Classification with Gradio

This project demonstrates an SMS text classification system using a Gradio-based user interface. It allows users to input text messages and receive predictions on whether the message is spam or not spam.

## Overview

The system is designed to classify SMS messages into two categories: **Spam** and **Not Spam**. This project integrates a trained machine learning model and provides an interactive web-based interface through Gradio. It is user-friendly, allowing both predefined and custom user inputs.

### Example Messages for Testing

Here are some example messages you can use to test the application:

1. You are a lucky winner of $5000!
2. You won 2 free tickets to the Super Bowl.
3. You won 2 free tickets to the Super Bowl. Text us to claim your prize.
4. Thanks for registering. Text 4343 to receive free updates on Medicare.

## Features

- **Gradio Interface**: Provides a simple and interactive web UI to input text messages.
- **Spam Detection**: Utilizes a machine learning model to determine if a message is spam or not.
- **Custom Input Support**: Users can type, paste, or enter custom text into the input box for classification.
- **Live Prediction**: The model provides instant predictions upon submission.

## Requirements

To run this project, you need the following:

- **Python Version**: 3.8 or higher
- **Required Libraries**:
  - Gradio: For creating the web-based interface.
  - Scikit-learn: For the machine learning model (or the specific library used to train your model).
  - Pandas: For data processing.
  - NumPy: For numerical operations.

## How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python gradio_sms_text_classification.py
   ```

4. Access the Gradio interface:
   - Once the script is running, a local URL will be generated (e.g., `http://127.0.0.1:7860`).
   - Open the URL in your browser to use the interface.

## How It Works

1. **Input Message**: The user inputs an SMS message into the Gradio interface.
2. **Model Prediction**: The system processes the message using a trained machine learning model.
3. **Output**: The application displays the classification result (Spam or Not Spam) instantly.

### Example Workflow:

1. Open the Gradio interface in your browser.
2. Enter the text: `You are a lucky winner of $5000!`.
3. Click "Submit" to receive the prediction.
4. The result will indicate whether the message is **Spam** or **Not Spam**.

## Author

**Brian Hansen-Turton**

If you have any questions, suggestions, or feedback, feel free to reach out.


