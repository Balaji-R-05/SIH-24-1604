# Conversational Image Recognition Chatbot (SIH'24 1604)

![Project Banner](https://via.placeholder.com/800x200?text=Conversational+Image+Recognition+Chatbot) <!-- Add your banner image -->

A deep learning-powered chatbot that combines **computer vision** and **natural language processing** to analyze images and answer user questions about visual content.

---

## 📌 Project Overview

### Background
While AI-powered chatbots like Siri and Google Assistant excel at text-based interactions, integrating image understanding with natural conversation remains a challenge. This project addresses this gap by building a **multimodal chatbot** that can:
1. **Detect objects** in user-uploaded images
2. **Answer questions** about image content
3. **Generate grammatically correct responses** in natural language

### Expected Solution
- **Input**: Image + Text Query (e.g., "What is the dog playing with?")
- **Output**: Context-aware, lexically correct response (e.g., "The dog is playing with a red frisbee in the park.")

---

## 🗃️ Dataset

We use industry-standard datasets for robust model training:

| Dataset       | Purpose                          | Size          | Features                             |
|---------------|----------------------------------|---------------|--------------------------------------|
| **[COCO](https://cocodataset.org/)** | Primary Training Data | 330K+ images | Object detection + VQA annotations   |
| ImageNet      | Transfer Learning               | 14M+ images  | General object recognition           |
| VQA v2        | Question-Answer Pairs           | 1.1M QA pairs | Visual question answering            |

**Why COCO?**
- Provides bounding boxes, segmentation masks, and captions
- Includes pre-trained baselines for VQA tasks
- Industry standard for multimodal AI research

---

## 🛠️ Technical Approach

### Architecture
