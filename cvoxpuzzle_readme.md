# 🧩 CVoxPuzzle: The AI Voice-Native CV Builder

![CVoxPuzzle Banner](https://via.placeholder.com/1200x400/0a0f1c/a855f7?text=CVoxPuzzle+-+Speak+Your+Career+Into+Existence)

**CVoxPuzzle** is a revolutionary voice-first productivity SaaS that transforms the painful process of writing a Resume/CV into a natural, engaging conversation. Built for the **AssemblyAI Voice Agent Hackathon**.

---

## 📖 The Creator's Journey: Art Meets Code
**"Can a Fine Arts researcher build a complex AI SaaS?"**
I am a Master's researcher in Fine Arts (Photography) with zero formal background in computer science. As a self-taught developer, I learned to code because I believe that the intersection of art and technology is where true magic happens. 

I built **CVoxPuzzle** entirely from scratch. My artistic background drove the intense focus on UX/UI, the seamless drag-and-drop interaction, and the visually polished output. This project proves that with passion, self-learning, and powerful APIs like AssemblyAI, the barrier between a creative idea and a fully functional software product no longer exists.

---

## 🚨 The Problem
Staring at a blank document to write a CV is intimidating. Millions of job seekers, fresh graduates, and professionals struggle with formatting, phrasing, and ATS (Applicant Tracking System) optimization. Existing AI tools just generate generic text walls, leaving users with messy documents that require heavy manual formatting.

## 💡 The Solution
**CVoxPuzzle** turns resume building into an interactive interview. 
You don't write; you speak. 
1. **The Interview:** An AssemblyAI-powered HR Voice Agent conducts a natural interview to learn about your career.
2. **The Extraction:** The agent extracts structured JSON data via Function Calling.
3. **The Puzzle:** The data dynamically spawns into modular, draggable UI blocks (Puzzle pieces).
4. **The Output:** Export a perfectly formatted, ATS-ready Word Document (`.doc`) or PDF with a single click.

---

## 🌟 Key Features

* 🎙️ **Full AI HR Interview:** Powered by AssemblyAI WebSockets. The agent listens patiently, asks adaptive questions, and extracts complete career data autonomously.
* 🧩 **Drag & Drop Canvas:** Reorder your experience, skills, and education blocks fluidly. 
* 🌍 **Instant Bilingual Support (EN ↔ AR):** One-click translation between English and Arabic, automatically swapping the document layout between LTR and RTL.
* 🪄 **Magic Wand & Live Dictation:** Want to edit a specific field? Use the Magic Wand to dictate casual speech and let AI format it into professional corporate jargon instantly.
* 📄 **Production-Ready Exports:** Unlike standard web apps, CVoxPuzzle generates a true Microsoft Word (`.doc`) file with embedded images and layout retention, plus PDF print support.
* 💾 **Local Profile Management:** Create multiple profiles, auto-save progress, and import/export your data as JSON.

---

## 💼 Business Value & TAM (Total Addressable Market)
While many AI agents target niche B2B technical problems, **CVoxPuzzle targets the mass market (B2C & B2B2C).**
Every university student, job seeker, and professional on Earth needs a CV. 
* **Target Audience:** Job seekers, University Career Centers, HR Agencies.
* **Monetization Potential:** Freemium SaaS model, premium ATS-optimized templates, or API licensing for recruitment platforms.

---

## ⚙️ How It Works (Under the Hood)

* **Frontend:** Built with vanilla HTML/CSS/JS for ultra-fast performance, zero-dependency rendering, and a completely custom Drag-and-Drop engine.
* **Voice Agent Layer:** AssemblyAI Realtime Voice Agent API.
* **Orchestration:** Custom `submit_cv_data` Tool/Function Call forces the LLM to return strict JSON arrays mapping to the CV architecture.
* **Audio Processing:** Browser `AudioContext` and `ScriptProcessorNode` capturing 24kHz PCM audio, streamed directly via WebSockets to AssemblyAI.

---

## 🏆 Why CVoxPuzzle Stands Out
1. **Tangible Output:** It doesn't just chat; it produces a real, downloadable `.doc` file that users can email to employers immediately.
2. **User in Control:** AI doesn't blindly override the document. It generates modular blocks that the user can accept, edit, or move.
3. **Accessibility:** Lowering the barrier to entry for non-technical users or those who struggle with typing. Just talk, and your career profile builds itself.

---

*Built with ❤️ and ☕ by a Fine Arts creative turned AI developer for the AssemblyAI Hackathon.*