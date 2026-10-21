# Reel Studio

Topic -> script (Gemini) -> footage (Pixabay) -> optional voiceover (ElevenLabs) -> captioned vertical MP4.

Deploy on Render as a Docker web service. Environment variables:
- GEMINI_API_KEY (scripts, free at aistudio.google.com/apikey)
- PIXABAY_API_KEY (footage, free at pixabay.com/api/docs)
- APP_PASSWORD (protects your link)
- ELEVENLABS_API_KEY (optional voiceover)
