# HandsTalk

**HandsTalk** is an AI‑powered sign language translation platform designed to bridge communication between signers and non‑signers in real time. Whether you want to convert spoken or written text into sign language animations or translate live hand gestures into readable text (and speech), HandsTalk‑2.0 makes communication seamless and accessible.

✨ **Features**  
- **Text‑to‑Sign**: Type or paste any text and watch our 3D avatar render it in American Sign Language (ASL) (with plans to support BSL, ISL, etc.).  
- **Sign‑to‑Text**: Use your webcam to capture real‑time hand gestures and see them transcribed into written text.  
- **Speech Integration**: Speak into your microphone and have your words both transcribed and “signed” on screen.  
- **Audio Playback**: Have translated text read back to you using the browser’s Speech Synthesis API.  
- **Offline Ready**: Caches gesture‑recognition models so you can translate even without an internet connection.  
- **Responsive UI**: Optimized for desktop, tablet, and mobile – drop in on any device.  
- **PWA Support**: Install HandsTalk as a Progressive Web App for quick access from your home screen.

🛠️ **Tech Stack**  
Next.js · React · TensorFlow.js · MediaPipe Hands · Web Speech API · Tailwind CSS · Vercel

🔗 **Live Demo**  
[handstalk.vercel.app](https://handstalk.vercel.app)

---

## 🚀 Getting Started

### 1. Clone the repo  
```bash
git clone https://github.com/Vakyro/HandsTalk-2.0.git
cd HandsTalk-2.0
```
### 2. Install dependencies
```bash
npm install
# or
yarn install
```
### 3. Configure environment variables
Create a .env.local file in the project root:
```bash
NEXT_PUBLIC_SPEECH_TO_TEXT_KEY=your-google-cloud-speech-key
NEXT_PUBLIC_ELEVENLABS_API_KEY=your-elevenlabs-tts-key
NEXT_PUBLIC_API_URL=https://handstalk.vercel.app/api
```
**Note**: If you don’t have ElevenLabs credentials yet, you can omit that variable and rely on the browser’s native SpeechSynthesis.
### 4. Run in development
```bash
npm run dev
# or
yarn dev
```
Open http://localhost:3000 to explore.
### 5. Build for production
```bash
npm run build
npm start
```

🙌 **Contributing**
1. Fork the repository
2. Create a feature branch (git checkout -b feature/YourFeature)
3. Commit your changes (git commit -m "Add YourFeature")
4. Push to the branch (git push origin feature/YourFeature)
5. Open a Pull Request
Please make sure to follow the existing code style and include relevant tests.
