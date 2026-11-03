# S-AI

Apna personal AI chat app — ek hi `index.html` me. Chat, image, video (Gemini Veo), code aur PPT; Gemini, OpenAI, Claude, Groq, DeepSeek, OpenRouter jaise providers ke saath.
10 UI themes (Glass, Liquid, Neumorph, Clay, Brutal, Neon, Terminal, Material, Solid, Flat), Day/Night mode aur wallpapers.

## GitHub par daalna
1. github.com par **New repository** banao (jaise `s-ai`), Public rakho.
2. **Add file → Upload files** se is folder ki saari files (`index.html`, `sw.js`, `manifest.webmanifest`, `` …) drag karke upload karo → **Commit changes**.
3. **Settings → Pages → Branch: `main` / root → Save**.
4. 1–2 minute baad link milega: `https://<tumhara-username>.github.io/s-ai/`

## Chrome se install karna (phone ya PC)
1. Upar wala GitHub Pages link Chrome me kholo (HTTPS zaroori hai, isliye Pages use karo).
2. Phone: **⋮ menu → Install app** (ya *Add to Home screen*). PC: address bar me **Install** icon.
3. Ab S-AI normal app ki tarah home screen / desktop se khulega.

## Zaroori baatein
- API keys sirf tumhare device ke browser (localStorage) me save hoti hain. **Keys ko kabhi GitHub par commit mat karo.**
- Update dene ke baad agar purana version dikhe, `sw.js` me `CACHE = 's-ai-v2'` ko `v3` kar do.
- Locally test: folder me `python -m http.server 8000` chalao aur `http://localhost:8000` kholo (`file://` par install nahi hota).
