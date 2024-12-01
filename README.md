## **Product-Finder Using Gemini AI API**
## **Description**
  Product Finder using Gemini AI API is a computer vision and AI-powered application designed to identify products using real-time webcam streams. The application utilizes the Gemini AI API to analyze captured frames, identify objects in the images, and provide relevant product details. It also integrates text-to-speech (TTS) for audible feedback and performs web searches for the identified products using a browser, enhancing user convenience.

## **Features:**
1. Real-Time Object Detection: Captures frames from a live webcam feed.
2. AI-Powered Identification: Utilizes Gemini AI API to recognize objects and return details.
3. Web Search Integration: Opens a browser to search for identified products.
4. Text-to-Speech Feedback: Provides audible product information.
5. Easy-to-Use Interface: Interact using simple keypresses (s to capture, q to quit).

## **Installation**
Pre-Requisites
. Python 3.8 or higher.
Required libraries:
 . OpenCV Python
 . google-generativeai
 . pyttsx3
 . urllib
 . webbrowser.

To install Project Title, follow these steps:

1. Clone the repository: **`git clone https://github.com/your-repo/ProductFinder`**
2. Navigate to the project directory: **`cd ProductFinder`**
3. Install dependencies: **`pip install -r requirements.txt`**
4. Replace the placeholder in the code with your Gemini AI API Key: **`genai.configure(api_key="YOUR_API_KEY")`**
5. Set up your webcam or ESP32 Cam streaming URL.
6. Run the application: **`python product_finder.py`**

## **File Structure**
ProductFinder/
│
├── product_finder.py   # Main script
├── requirements.txt    # Dependencies
└── README.md           # Documentation

## **Future Enhancements**Future Enhancements
1. Add support for additional AI models for broader product identification.
2. Enhance TTS with multilingual capabilities.
3. Integrate mobile notification features for identified products.
