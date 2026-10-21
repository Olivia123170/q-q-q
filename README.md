# Thesis Reflections and Feedback — English Translation

English translation of the Chinese document《论文思考与意见反馈》.

## Contents

| File | Description |
|---|---|
| `Thesis_Reflections_and_Feedback_EN.md` | Markdown version of the translation |
| `Thesis_Reflections_and_Feedback_EN.pdf` | Formatted A4 PDF, single page |

## Version

**v1.0.0** — 2026-10-21 · Initial English translation, complete (title + summary paragraph + 6 comments).

Version numbers follow [Semantic Versioning](https://semver.org/):

- **MAJOR** — changes to the substance or structure of the source content
- **MINOR** — new sections, added notes or a bilingual edition
- **PATCH** — wording fixes and layout corrections

## Build notes

The PDF is generated from an HTML layout file with headless Chrome. The layout file is kept outside this repository so that the repo holds only the deliverables:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless --no-sandbox --disable-gpu --disable-software-rasterizer \
  --no-pdf-header-footer \
  --print-to-pdf=Thesis_Reflections_and_Feedback_EN.pdf \
  thesis_feedback_en.layout.html
```

`--no-sandbox` is required on this machine; without it Chrome fails to initialise its sandbox and crashes on the GPU process.

## Source document

8 paragraphs: one title, one general appraisal, and six numbered comments. Translator's notes on three choices:

- Comment 3, “不能算作翻译补偿的策略运用” → *cannot be counted as the application of translation compensation strategies* — the original's dismissive force is kept.
- Comment 5, “博士论文” → *doctoral dissertations*, pairing with *master's theses* earlier in the same sentence.
- Comment 6, “有基于此” → italicised *“you ji yu ci”* with the Chinese in parentheses, because the original cites it as the very example of non-standard usage; a bare English rendering would hide the point.

## Changelog

### v1.0.0 — 2026-10-21
- Initial release.
