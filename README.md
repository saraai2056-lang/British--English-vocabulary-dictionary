# 📖 Sid's British Vocabulary Dictionary

> A beautifully designed, audio-enabled British English vocabulary dictionary built from popular British films and TV shows — with formal, casual, and slang entries covering classic and modern usage.

🔗 **[Live Demo → View Dictionary](https://YOUR-USERNAME.github.io/british-vocabulary-dictionary/)**

---

## 🎬 Shows & Sources

| Source | Category |
|--------|----------|
| 🎬 Jimmy Savile: A British Horror Story (Netflix, 2022) | Documentary |
| 👑 The Crown (Netflix, 2016–2023) | Royal Drama |
| 💌 Wicked Little Letters (2024) | Period Comedy |
| 🎩 Peaky Blinders (BBC, 2013–2022) | Crime Drama |
| 📺 Cunk on Earth (BBC/Netflix, 2023) | Mockumentary |
| 🎓 British Formal English | Academic & Professional |
| 🗣️ British Casual & Slang | Everyday British Speech |

---

## ✨ Features

- **225+ vocabulary entries** from A to Z
- **🔊 Audio playback** — hear every word spoken in British English (en-GB)
- **Pronunciation guide** on every card using easy phonetic spelling (e.g. `AM-ih-kuh-bul`)
- **Part of speech** label for every word (noun, verb, adjective, etc.)
- **Word origin** — where the word comes from (Latin, French, Old English, etc.)
- **Real example sentences** — including actual quotes from the shows
- **Filter by source** — view only Crown words, only Peaky Blinders slang, etc.
- **Search bar** — instantly find any word
- **A–Z navigation** bar for fast jumping
- Colour-coded cards by source
- Works on **mobile and desktop**
- **No installation needed** — pure HTML, CSS, and JavaScript

---

## 📚 What's Inside

### 🎓 British Formal
Words used in professional, legal, political, and academic contexts:
`Acquiesce` · `Albeit` · `Bespoke` · `Corroborate` · `Eloquent` · `Exonerate` · `Formidable` · `Henceforth` · `Impeccable` · `Integrity` · `Paramount` · `Resolute` · `Scrutinise` · `Tenacious` · `Ubiquitous` · `Vehement` · and many more

### 🗣️ British Casual & Slang
Everyday British speech, from classic to modern:
`Ace` · `Banter` · `Blimey` · `Bloke` · `Brilliant` · `Cheeky` · `Cheers` · `Chuffed` · `Dodgy` · `Faffing` · `Fit` · `Fortnight` · `Gobsmacked` · `Gutted` · `Innit` · `Knackered` · `Mate` · `Peckish` · `Posh` · `Quid` · `Rubbish` · `Sorted` · `Stroppy` · `Take the mickey` · and many more

### 🎩 Peaky Blinders (Birmingham Dialect + Criminal Underworld)
`Bab` · `Blinder` · `Bostin'` · `Garrison` · `Machinations` · `Romani` · `Sardonic` · `Shell Shock` · `Subterfuge` · `Ta-ra` · `Vendetta` · and more

### 👑 The Crown (Royal & Political)
`Annus Horribilis` · `Egalitarian` · `Persona non grata` · `Preordained` · `Temerity` · `Tinderbox` · and more

### 📺 Cunk on Earth (History & Documentary)
`Anachronism` · `Bourgeoisie` · `Civilisation` · `Epoch` · `Feudal` · `Hegemony` · `Hubris` · `Paradox` · `Renaissance` · `Zeitgeist` · and more

---

## 🚀 How to Use

### Option 1 — View Online (GitHub Pages)
Just visit the live link at the top of this page. No setup needed.

### Option 2 — Run Locally
```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/british-vocabulary-dictionary.git

# Navigate into the folder
cd british-vocabulary-dictionary

# Open in your browser
open index.html
```
Or simply double-click `index.html` to open it in your browser.

### 🔊 For Audio to Work
- Open the file in **Google Chrome** or **Microsoft Edge**
- Make sure your **volume is turned up**
- Tap **▶ Hear it** on any card
- The word is spoken in **British English (en-GB)**

> **Note:** Audio uses Google TTS as primary source, with Web Speech API as fallback. Works best in Chrome and Edge.

---

## 🗂️ Project Structure

```
british-vocabulary-dictionary/
│
├── index.html        ← The complete dictionary (one file, no dependencies)
├── README.md         ← This file
└── LICENSE           ← MIT License
```

Everything is in a single `index.html` file — no frameworks, no build tools, no npm. Pure HTML, CSS and JavaScript.

---

## 🌐 Deploy to GitHub Pages (Free Hosting)

1. **Fork or clone** this repository
2. Go to your repo → **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your dictionary is live at `https://YOUR-USERNAME.github.io/british-vocabulary-dictionary/`

That's it! GitHub Pages hosts it for free. 🎉

---

## 🖼️ Screenshots

| Feature | Preview |
|---------|---------|
| A–Z navigation | Jump to any letter instantly |
| Filter by source | View only The Crown, or only Peaky Blinders, etc. |
| Audio button | Hear every word in British English |
| Pronunciation guide | Easy phonetic spelling on every card |
| Search | Find any word instantly |

---

## 🧑‍💻 How It Was Built

- **Pure HTML5 + CSS3 + Vanilla JavaScript** — no frameworks
- **Web Speech API** (`SpeechSynthesis`) for audio with `lang='en-GB'`
- **Google Translate TTS** as primary audio source
- **Google Fonts** — Playfair Display + EB Garamond for a classic British look
- All 225+ vocabulary entries stored as a JavaScript array and rendered dynamically
- Filter, search, and A–Z navigation all run client-side with no server

---

## 📝 Word Entry Format

Each word contains:
```
Word         → The vocabulary word
Part of Speech → noun, verb, adjective, etc.
Pronunciation  → AM-ih-kuh-bul (CAPITALS = stressed syllable)
Meaning      → Full definition in plain English
Origin       → Etymology — where the word comes from
Example      → A real sentence, often a quote from the show
Source       → Which show or category it comes from
```

---

## 🤝 Contributing

Want to add more words? Pull requests welcome!

To add a new word, open `index.html` and find the `VOCAB` array. Add a new entry following this format:

```javascript
{
  w: 'Your Word',
  pos: 'noun',
  pron: '<b>YOUR</b>-werd',
  meaning: 'The definition of the word.',
  origin: 'From Latin/French/Old English...',
  ex: '"An example sentence using the word."',
  src: 'bc'   // savile | crown | wll | pb | ce | bf | bc
}
```

---

## 📜 Vocabulary Sources

- *Jimmy Savile: A British Horror Story* — Netflix Documentary
- *The Crown* — Netflix Drama Series
- *Wicked Little Letters* — Film (StudioCanal, 2024)
- *Peaky Blinders* — BBC Crime Drama
- *Cunk on Earth* — BBC/Netflix Mockumentary
- British formal usage from legal, political and academic contexts
- British everyday slang — from Cockney to Brummie to Northern dialect

---

## 📄 License

MIT License — free to use, share, and modify.

See [LICENSE](LICENSE) for full details.

---

## 👩‍🎓 About

Built as a personal vocabulary learning project by **Sid** — a learner of British English through films and television.

> *"The best way to learn a language is through the stories told in it."*

---

⭐ **If this helped you, please give it a star on GitHub!**
