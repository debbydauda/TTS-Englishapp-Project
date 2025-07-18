 # English_TTS_App 

This project is a simple Text-to-Speech (TTS) web application that converts typed English text into audio using Nigerian-accented voices. The app uses the ElevenLabs API and Gradio for the interface.


 # Language Focus
 this project focuses on Nigerian English, a local variety of English that reflects the pronunciation, rhythm, and expressions commonly used in Nigeria. 

The goal was to make the generated speech feel relatable and authentic to Nigerian listeners while keeping it in English.


 # Voice ID Used
 
 I selected voice(s) from the ElevenLabs Voice Library that best matched Nigerian English tonality.
Voice_ID Female:WjC4A2cTO3MVjWo1GIkW

 Note: These voices were chosen based on clarity, tone, and how well they reflect Nigerian English pronunciation from the ElevenLabs voice library.

 # Pronunciation Handling
 
 I used ElevenLabs' eleven_multilingual_v2 model for improved pronunciation of African dialects.
Adjusted stability and similarity_boost to slow down speech and enhance clarity.
Introduced a replacement dictionary in future versions to fix common mispronunciations.
I crafted input text using phrases and sentence patterns commonly used in Nigeria.(eg  Instead of “Did they ignore it after removal?”, we used: 
   `"When he removed them now, did they ignore the removal?" 
`Also slowed down speech slightly using:
Lower stability (0.5)
Slight punctuation spacing
Word breaks using commas and spaces

# Features

Text input for English
Voice dropdown
Generate audio with ElevenLabs
Audio playback
Download audio file
Clean UI with emojis

# Tech Stack

Python,
Gradio for UI,
ElevenLabs API for TTS

 # Summary

This app was built as an introductory project for applying data science and AI to language technology. We aimed to create a realistic voice application for Nigerian audiences and demonstrate how TTS can adapt to local languages and accents.
