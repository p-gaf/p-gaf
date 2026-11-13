## Hi, I'm Patrick

I evaluate voice AI for a living and build my own tools on the side. My background is audio: five-plus years as a composer, producer and recording engineer. These days I put that ear to work judging how AI voice models sound and behave in conversation.

📍 Los Angeles &nbsp;·&nbsp; [patrickgaffney.studio](https://patrickgaffney.studio) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/ptrgaffney)

---

### What I do

**Voice Knowledge Expert, Meta** (contract, May 2026 – present)

- Head-to-head preference testing of text-to-speech and speech-to-speech voice models, with every call tied to timestamped evidence
- Persona and conversation-quality analysis: naturalness, prosody, turn-taking, persona stability, engagement
- System-prompt adherence testing: which wording of an instruction actually produces the intended behavior
- Longitudinal memory evaluation across weeks of daily sessions
- QA audits of other evaluators' work, plus daily trend reports that turn individual calls into findings

**AI Subject Matter Expert, audio and video** (contract for a frontier AI lab, Nov 2025 – Apr 2026)<br>
Wrote multi-hour expert tasks in audio and post-production, graded model output against human work, and compared how efficiently different models reached a finished deliverable.

---

### Things I've built

I use Claude Code as my development environment. I design each tool, set its constraints and test it until it holds up. Most of these repos are private; I'm happy to walk through any of them.

| Project | What it does | Built with |
|---|---|---|
| **Evaluation task generator** | Generates and curates the opening prompts for conversational-AI evaluation. The rubric lives in the software: a category taxonomy defined by what a complete *response* has to contain, paired tasks that isolate a single variable, a human review queue, and a database split so model results can never influence which tasks get picked. | TypeScript, Next.js, React, Postgres (Supabase), Anthropic API |
| **midi-generator** | Generates MIDI clips with Claude from a text prompt, a reference MIDI file or a screenshot of a piano roll. Works from the command line today; an Ableton Live extension is in progress. | TypeScript, Node, Anthropic API |
| **Prediction-market reaction study** | Tested whether Kalshi overreacts when a team scores first, across 4,461 MLB games and 1,486 NFL touchdowns, against a Markov win-probability model calibrated to each game's pregame price. Result: the market prices it right, and there's no tradable edge after fees. | Python, pandas, scikit-learn, MLB Stats API, nflverse, Kalshi API |
| **Audio effects plugin** | A VST3/AU effects plugin built on a shared DSP library of its own: saturation, bus compression, echo, harmonizer, spectral reverb. Automated tests check latency, aliasing, clicks and CPU load, and builds are validated with pluginval at its strictest setting. | C++20, JUCE, CMake |
| **Chief of Staff** | A calendar and task list that writes a short morning brief of what actually matters. Runs locally on a Mac and works on a phone over home wifi, with no hosting or accounts. | TypeScript, Node, SQLite |
| **[patrickgaffney.studio](https://github.com/p-gaf/Website)** | My portfolio of music credits and photography. Hand-coded, with no framework and no build step. | HTML, CSS, JavaScript |

---

### Background

- **BS, Creative Technology and Design**, University of Colorado Boulder, College of Engineering (cum laude, 2022), with a certificate in music technology
- **Composer and producer** since 2020: scores for two award-winning short films and commercial spots that aired on ESPN and CBS
- **Studio internship** at Conway Recording Studios, Los Angeles
- **Photographer**: my photos of Altadena fire-relief efforts ran in Vogue
- Avid Certified Specialist (Pro Tools) · Salesforce Trailhead: CRM Fundamentals

### Tools I use

- **Building:** Claude Code, Anthropic API, Git, Supabase / Postgres, Vercel
- **Audio:** Pro Tools, Ableton Live, Logic Pro
- **Photo and video:** Capture One, Adobe Premiere Pro, Photoshop
