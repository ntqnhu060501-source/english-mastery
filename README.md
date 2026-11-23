# ENGLISH MASTERY — MVP 0.1

Responsive web app for a 60-minute daily English learning routine.

## Deploy
- Static website; no build step required.
- Vercel: import this repository and use Framework Preset **Other**.
- Build command: leave empty.
- Output directory: `.`
- The app entry point is `index.html`.

## Included
- Dashboard and 60-minute daily plan
- 8-question placement screening (rough estimate, not a CEFR certificate)
- Vocabulary: word family, collocations, examples, active recall, personal word list
- Grammar and sentence-pattern exercise
- Paraphrasing exercise
- Listening, speaking, reading and writing practice prompts
- Mistake Bank and progress summary
- Local browser storage

## Current limitations
- No login or cloud sync yet.
- No AI tutor or automated pronunciation scoring yet.
- Listening exercises link to BBC Learning English; no audio library is bundled.
- Local progress is stored in the current browser/device. Clearing browser data may erase it.

## Roadmap
1. MVP foundation (current)
2. Learning engine: spaced repetition, word maps, richer content and mistake review
3. Four skills: leveled audio/reading library, speaking recordings and writing rubrics
4. AI tutor via a secure server-side integration (never expose API keys in browser code)
5. Supabase authentication/database and public deployment
