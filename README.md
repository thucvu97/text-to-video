# 🚀 Text-to-AI Video

## 🛠️ Technologies Used

### Frontend (FE)
- **Next.js**: A React framework for building the user interface.
- **Clerk**: User authentication and management.

### Backend (BE)
- **NestJS**: A robust Node.js framework for building APIs.
- **MongoDB**: NoSQL database for storing data.
- **BullMQ**: Queue processing for handling video processing tasks.

### AI & Content Processing
- **Gemini & ChatGPT**: Generate video scripts from text input.
- **AWS Polly**: Convert text to speech (Text-to-Speech - TTS).
- **Kling & Gemini**: Generate and modify character outfits in videos.

### Storage & Distribution
- **Amazon S3**: Store generated videos and voice files.

### Proxy & API Bypass
- **Proxy Rotation**: Avoid API request limits when sending high-volume requests.

## 📌 Project Overview
This project enables users to generate AI-powered videos from text input by utilizing advanced AI models for script generation, voice synthesis, and character rendering. The generated videos are then stored in Amazon S3 and provided as shareable URLs.

## 🚀 How It Works
1. **User Input**: Users enter a text description or script.
2. **Script Generation**: AI (Gemini/ChatGPT) processes the input and generates a script.
3. **Voice Synthesis**: AWS Polly converts the script into a natural-sounding voice.
4. **Character & Outfit Customization**: Kling & Gemini generate AI-powered characters with custom outfits.
5. **Video Processing**: The generated voice and characters are combined into a video.
