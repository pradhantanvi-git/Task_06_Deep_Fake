# Task 06 — Deep Fake 
**Project:** IPL 2022 AI-Based Street Interview  

## 1) What this is
In prior periods, I used an LLM to create dataset narratives (e.g., summaries, stories, recommendations), please refer Task 05 Descriptive Analysis. I’m now transforming that narrative into an **AI-generated “street interview”**.  
My narrative is based on the **IPL 2022** analysis (Q1–Q8). The final artifact is a short audio-led interview where a Host asks questions and the IPL winning team captain answers with dataset-validated facts.

## 2) Deliverables (in this repo)
- `IPL 2022 Audio AI-Street Interview.mp4` (60–90s, audio-led)
- `script/interview_script_IPL2022.txt` (Host/Captain dialogues)
- `README.md` (this file) 

## 3) Ethical disclosure (used verbatim)
> **“This is IPL 2022 AI-based street interview. This is AI-generated synthetic media created for academic research. No real person’s voice was cloned.”**

Guardrails:
- No cloning of real voices/faces; generic TTS only
- Visible disclosure and “Synthetic Media” watermark
- Academic demonstration; not for impersonation or misinformation

## 4) Tools (free/student)
- **Clipchamp (web)** – Text-to-Speech and quick timeline edit  

## 5) My process 
1. **Convert narrative → script:** Turned IPL Q1–Q8 results into Q&A dialogue (Host/Captain).
2. **Generates two voices:** Clipchamp → *Record & Create → Text to speech*; Voice A = Host, Voice B = Captain.
3. **Assemble timeline:** Added clips in order (Disclosure → Q1 H/A → … → Q8 H/A → Closing); insert 0.5–1s gaps.
4. **Add disclosure/watermark:** Spoken at start; “Synthetic Media” text overlay.
5. **Exported:** 1080p MP4
6. **Document:** Captured steps, issues, and timing below.

## 6) Reproduce
1. Open Clipchamp → **Create new video**.  
2. **Text to speech** → paste **disclosure** → **Add to timeline**.  
3. Alternate Host/Captain lines from `script/interview_script_IPL2022.txt` using two distinct voices.  
4. Add small pauses; optional static image background.  
5. **Export 1080p MP4**.

## 7) Repo structure
Task_06_Deep_Fake/
├─ README.md
├─ interview_script_IPL2022.txt
├─ cover.webp
└─ IPL 2022 Audio AI-Street Interview.mp4
