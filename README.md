# 🗣️ Nigerian English TTS App – Team Submission

This project is a simple Text-to-Speech (TTS) web application that converts typed English text into audio using Nigerian-accented voices. The app uses the ElevenLabs API and Gradio for the interface.

---

## 🌍 Language Focus

The primary language focus of this project is **Nigerian English** — a local variety of English that reflects the pronunciation, rhythm, and expressions commonly used in Nigeria. It includes:

- Distinct intonation patterns and rhythm
- Phrasing that mirrors Nigerian speech (e.g. “He has removed them now”)
- Local word use and sentence structure

The goal was to make the generated speech feel relatable and authentic to Nigerian listeners while keeping it in English.

---

## 🎙️ Voice ID Used

I selected voice(s) from the ElevenLabs Voice Library that best matched Nigerian English tonality.

| Voice Name   | Voice Description           | Voice ID Used         |
|--------------|-----------------------------|------------------------|
| Kola (Male)  | Nigerian-accented male voice | `YOUR_VOICE_ID_1`     |
| Ada (Female) | Nigerian-accented female voice | `YOUR_VOICE_ID_2`     |

> Note: These voices were chosen based on clarity, tone, and how well they reflect Nigerian English pronunciation from the ElevenLabs voice library.

---

## 🧪 Pronunciation Handling

To ensure the app delivers speech that closely reflects Nigerian English:

- ✅ I selected voices that already had a Nigerian accent or could represent it convincingly.
- ✅ I **crafted input text** using phrases and sentence patterns commonly used in Nigeria.
  - Example: Instead of “Did they ignore it after removal?”, I used:  
    `"When he removed them now, did they ignore the removal?"`
- ✅ I **avoided phoneme-level customization** due to time constraints and free-tier API limitations, but i plan to:
  - Add IPA/phonetic support in future versions
  - Incorporate tone-sensitive enhancements for Nigerian languages like Yoruba or Igbo

---

## 🧠 Summary

This app was built as an introductory project for applying data science and AI to language technology. i aimed to create a realistic voice application for Nigerian audiences and demonstrate how TTS can adapt to local languages and accents.

---

✅ Built with:  
- ElevenLabs API (Text-to-Speech)  
- Gradio (Web Interface)  
- Python

---

