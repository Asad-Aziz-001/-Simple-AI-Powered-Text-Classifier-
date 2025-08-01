 # **Simple AI-Powered Text Classifier**
 
This project demonstrates a simple yet effective way to perform sentiment analysis using the TextBlob library in Python, combined with Gradio to build an interactive user interface.

**🔍 Objective:**

To classify user-provided sentences as Positive, Negative, or Neutral based on their emotional tone (sentiment).

**⚙️ Tools Used:**

TextBlob: For natural language processing, specifically sentiment polarity analysis.

Gradio: To create a lightweight web interface for user interaction.

Python File I/O: To save user inputs and their classified sentiments for future reference.

**🧠 Core Functionality:**

Accepts text input from the user.

Uses TextBlob to calculate sentiment polarity:

> 0 → Positive

< 0 → Negative

= 0 → Neutral

Returns the sentiment result.

Appends the text and sentiment to a local file (sentiment_results.txt) for logging.

**🌐 User Interface:**

A simple textbox allows the user to enter text.

Upon submission, the sentiment is displayed on screen.

The interface is minimal, intuitive, and ideal for quick testing or educational purposes.

Running on public URL: https://1341e9b92437b5c18b.gradio.live

This share link expires in 1 week

**✅ Use Cases:**

Educational demos for NLP beginners.

Quick prototyping for feedback systems.

Small-scale text analysis apps.

📌 Conclusion:
This project is a basic implementation of sentiment analysis that highlights the ease of using TextBlob for NLP tasks and Gradio for creating interactive apps. It provides a great starting point for learners interested in exploring natural language processing and user interface development in Python.
