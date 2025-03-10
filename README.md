# Conversational Image Recognition Chatbot (SIH'24 1604)

A deep learning-powered chatbot that combines **computer vision** and **natural language processing** to analyze images and answer user questions about visual content.

---

## 📌 Project Overview
This project aims to build a **Conversational Image Recognition Chatbot** that combines **Natural Language Processing (NLP)** and **Computer Vision (CV)**. The chatbot will:
1. Recognize objects in an image uploaded by the user.
2. Understand user queries about the image.
3. Generate relevant and grammatically correct responses.

### Key Features
- **Image Recognition**: Detect objects in an image using a deep learning model.
- **Conversational Ability**: Understand user queries and generate responses using NLP.
- **Integration**: Combine image recognition and conversational capabilities into a single system.

---

## Project Requirements

### Functional Requirements
1. **Image Upload**: Users can upload an image to the chatbot.
2. **Object Detection**: The chatbot detects objects in the image.
3. **Query Handling**: Users can ask questions about the image (e.g., "What is in the image?").
4. **Response Generation**: The chatbot generates a response based on the detected objects and user query.

### Non-Functional Requirements
1. **Performance**: The chatbot should respond within a reasonable time (e.g., < 5 seconds).
2. **Scalability**: The system should handle multiple users simultaneously.
3. **Accuracy**: The chatbot should accurately detect objects and generate relevant responses.

---

## Tools and Technologies

### Programming Language
- **Python**: The primary language for AI/ML development.

### Libraries and Frameworks
1. **Computer Vision**:
   - **PyTorch** or **TensorFlow**: For building and training the image recognition model.
   - **OpenCV**: For image processing.
2. **Natural Language Processing**:
   - **Hugging Face Transformers**: For pre-trained language models like GPT-2 or T5.
   - **NLTK** or **spaCy**: For text preprocessing.
3. **Web Framework**:
   - **Flask** or **FastAPI**: For building the chatbot interface.

### Datasets
1. **Image Recognition**:
   - **COCO (Common Objects in Context)**: A large-scale dataset for object detection.
   - **ImageNet**: A dataset for image classification.
2. **Conversational Model**:
   - **Cornell Movie Dialogs Corpus**: A dataset for training conversational models.

## Development Environment Setup

### Prerequisites
1. **Python 3.8+**: Install Python from [python.org](https://www.python.org/).
2. **Git**: Install Git from [git-scm.com](https://git-scm.com/).
3. **Virtual Environment**: Use `venv` or `conda` to create an isolated environment.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/conversational-image-chatbot.git
   cd conversational-image-chatbot
