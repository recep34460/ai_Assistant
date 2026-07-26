# Jarvis: AI Virtual Assistant

This is a Python-based virtual assistant inspired by "Jarvis". It operates using voice commands and can perform a variety of daily tasks, such as opening websites, fetching the latest news, reading Facebook messages, controlling the system power, taking notes, and more. 

## Features

* **Voice Recognition & Speech:** Converts your speech into text and responds to you using Text-to-Speech (TTS).
* **System Controls:** Can shut down, restart, or put your computer to sleep. It also checks battery percentage and identifies the current system user.
* **Web Navigation:** Opens websites like Google, YouTube, Facebook, and StackOverflow via voice commands.
* **Information Retrieval:** Fetches summaries from Wikipedia and solves queries or math problems using the WolframAlpha API.
* **Communication:** Reads unread messages from Facebook Messenger (using `fbchat`), sends WhatsApp messages, and sends automated Emails with file attachments.
* **Media & Entertainment:** Plays songs from your local directory, plays videos directly on YouTube, and tells jokes.
* **Utilities:** Sets alarms, checks current date and time, switches windows, opens notepad/command prompt, and accesses the webcam using OpenCV.

## Requirements and Installation

Make sure you have **Python 3.x** installed on your system. You can install all the required libraries by running the following command:

```bash
pip install -r requirements.txt
