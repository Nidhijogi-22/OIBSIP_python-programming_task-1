**🗣️ Voice Assistant using Python**

A beginner-friendly **voice-enabled assistant** built with Python that responds to voice commands to perform basic tasks like greetings, telling time/date, and searching the web.

**📁 Features Implemented**
- 👋 Responds to greetings like `"Hello"`
- 🕒 Tells the current time using the `datetime` module
- 📅 Announces the current date
- 🔍 Performs Google search using `pywhatkit`
- 🎤 Listens to voice input via `speech_recognition`
- 🔊 Responds with speech using `pyttsx3`

**🔧 Technologies & Libraries**

- `speech_recognition` – Convert voice to text
- `pyttsx3` – Convert text to speech
- `pywhatkit` – Perform web searches
- `datetime` – Get system time and date
- `pyaudio` – Required for microphone access

**🧠 Workflow**

1. Start the assistant script.
2. Assistant listens to your voice using a microphone.
3. Recognizes and processes commands like:
   - `"Hello"`
   - `"What time is it?"`
   - `"What's the date?"`
   - `"Search Python programming"`
   - `"Exit"`
4. Responds with speech and performs the requested action.
   
**📊 Output Examples**

- 🎤 User: `"Hello"`  
  💬 Assistant: `"Hi there! How can I assist you today?"`

- 🎤 User: `"What time is it?"`  
  💬 Assistant: `"The time is 04:23 PM"`

- 🎤 User: `"Search Python programming"`  
  🌐 Google Search window opens with relevant results

- 🎤 User: `"Exit"`  
  💬 Assistant: `"Goodbye!"` and the program ends
