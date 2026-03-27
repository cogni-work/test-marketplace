---
name: translate
description: >-
  This skill should be used when the user asks to "translate this",
  "translate to a random language", "surprise me with a translation",
  "say this in another language", "translate and tell me about the country",
  "random translation", or mentions wanting a translation with cultural context.
  It also applies when the user provides text and asks for a fun or surprising
  language experience.
---

# Random Language Translator with Cultural Context

Translate user-provided text into a randomly chosen language and provide
interesting cultural and geographical context about a country where that
language is spoken.

## Workflow

### 1. Select a Random Language

Pick one language at random from a diverse pool. Aim for variety — include
widely spoken languages (Spanish, Mandarin, Arabic) as well as less common
ones (Icelandic, Swahili, Georgian, Welsh, Tagalog, Basque, Maori, Amharic,
Khmer, Latvian, Yoruba, Mongolian, Esperanto). Aim for variety by selecting
from the full pool rather than favoring common languages.

### 2. Translate the Text

Provide the translation of the user's input into the selected language.
Present it clearly:

```
**Original:** [user text]
**Language:** [language name]
**Translation:** [translated text]
```

If the text contains idioms or culturally specific phrases, note how the
meaning was adapted rather than translated literally.

### 3. Pronunciation Guide

Include a simple phonetic pronunciation guide for the translated text
so the user can attempt to say it aloud. Use intuitive English-based
phonetics rather than IPA notation.

### 4. Country & Cultural Context

After the translation, provide a short, engaging section about a country
where this language is primarily spoken. Cover:

- **Country name and location** — where it is on the map
- **Population and capital** — basic facts
- **Fun fact** — one surprising or little-known fact about the country
- **Cultural highlight** — a notable tradition, food, festival, or custom
- **Language fact** — something interesting about the language itself
  (e.g., number of speakers, unique grammar features, writing system)

Keep the cultural section concise — around 150-200 words. The tone should
be friendly and informative, like a knowledgeable travel companion.

## Output Format

Structure every response as:

1. Translation block (original, language, translation)
2. Pronunciation guide
3. Country & culture section with the subsections listed above

## Edge Cases

- If the user provides very short input (single word), still provide the
  full cultural context — the translation is a gateway to the culture.
- If the user specifies a language preference, note it but explain this
  skill picks randomly, then proceed with the random choice.
- For languages with non-Latin scripts (Arabic, Chinese, Georgian, etc.),
  provide both the native script and a romanized version.
