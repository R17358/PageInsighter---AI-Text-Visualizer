

# PageInsighter - AI Text Visualizer

Live: https://text-visualizer-deploy.onrender.com


## Overview

**PageInsighter** is a Python-based web application that helps users visualize textual content from images or PDFs by generating real-time AI-driven images based on context and meaning. Additionally, it provides text summarization, translation, and mathematical problem-solving capabilities. Future enhancements will include **AR/VR features** for an immersive experience.

## Features

- **OCR Text Extraction**: Extracts text from uploaded images and PDFs using **Pytesseract**.
- **AI-powered Summarization**: Uses **Gemini-1.5-Flash API** for text summarization.
- **Language Translation**: Converts extracted text into the user's preferred language.
- **AI Image Generation**: Generates images related to the extracted text using **GAN models**.
- **Mathematical Problem Solving**: Solves math-related queries and equations.
- **AI Chatbot**: Provides question-answering functionality similar to ChatGPT.
- **Future Enhancements**: Planned integration of **AR/VR** features for interactive visualization.

## Tech Stack

| Technology               | Usage                          |
| ------------------------ | ------------------------------ |
| **Python**               | Backend Processing             |
| **Streamlit**            | Web Application UI             |
| **Pytesseract**          | OCR for Text Extraction        |
| **Gemini-1.5-Flash API** | AI Summarization & Translation |
| **GAN Models**           | AI Image Generation            |
| **OpenCV**               | Image Processing               |
| **Flask**                | API Backend (Optional)         |

## Installation

### Prerequisites

Ensure you have the following installed:

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- Required Python libraries:
  ```sh
  pip install streamlit pytesseract google-generativeai opencv-python Flask numpy requests
  ```

### Setup

1. **Clone the Repository**

   ```sh
   git clone https://github.com/R17358/PageInsighter_AI-Text-Visualizer.git
   cd PageInsighter
   ```

2. **Configure Environment Variables**
   Create a `.env` file and add:

   ```env
    api_url=https://api-inference.huggingface.co/models/Salesforce/blip-image-captioning-large
    api_key=huggingface_api_key
    otherImg_url=https://api-inference.huggingface.co/models/black-forest-labs/FLUX.1-schnell
    otherImg_key=huggingface_api_key
    gemini_key=

   ```

3. **Run the Application**

   ```sh
   streamlit run main.py
   ```
   or

   ```sh
     python -m streamlit run main.py

5. **Access the Web App**
   Open your browser and go to:

   ```
   http://localhost:8501
   ```

## Usage

1. **Upload an Image or PDF**
2. **Extract Text** using OCR.
3. **Generate Summary & Translation** in your preferred language.
4. **View AI-Generated Images** related to the text.
5. **Solve Mathematical Problems** with AI assistance.
6. **Ask Questions** using the built-in chatbot.

## Future Scope

- **AR/VR Integration** for immersive text visualization.
- **Handwritten Text Recognition**.
- **Voice-based Interaction** for accessibility.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m "Added new feature"`
4. Push to branch: `git push origin feature-name`
5. Open a Pull Request.

## License

This project is licensed under the **MIT License**.

## Contact

For queries, reach out at **[karanstdio1234@gmail.com](mailto\:karanstdio1234@gmail.com)** or open an issue.

---

**Empowering text with AI-driven insights!** 🚀

Ritesh Pandit
