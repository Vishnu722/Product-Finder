# Product-Finder

  Product Finder using Gemini AI API is a computer vision and AI-powered application designed to identify products using real-time webcam streams. The application utilizes the Gemini AI API to analyze captured frames, identify objects in the images, and provide relevant product details. It also integrates text-to-speech (TTS) for audible feedback and performs web searches for the identified products using a browser, enhancing user convenience.

Features
  Real-Time Object Detection: Captures frames from a live webcam feed.
  AI-Powered Identification: Utilizes Gemini AI API to recognize objects and return details.
  Web Search Integration: Opens a browser to search for identified products.
  Text-to-Speech Feedback: Provides audible product information.
  Easy-to-Use Interface: Interact using simple keypresses (s to capture, q to quit).
  
Installation
  Pre-Requisites
    Python 3.8 or higher.
  Required libraries:
    opencv-python
    google-generativeai
    pyttsx3
    urllib
  webbrowser
    An active Gemini AI API Key.
  Firefox browser (Ensure it's added to the system's PATH).

Setup Steps
  Clone the repository or download the source code.
    git clone https://github.com/your-repo/ProductFinder
    cd ProductFinder
  Install dependencies:
    pip install -r requirements.txt
  Replace the placeholder in the code with your Gemini AI API Key:
    genai.configure(api_key="YOUR_API_KEY")
  Set up your webcam or ESP32 Cam streaming URL.
  Run the application:
    python product_finder.py
