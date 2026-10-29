# Changelog

Newest first. Each package's footer shows the version date it matches.

## 2026-10-28

- ELA SCAFFOLD keeps copyright lines from the original.
- ELA SCAFFOLD builds the model example on a quote and question that none of the real items asks for, so it doesn't use up an answer students need.
- ELA TRANSLATE: a Spanish gloss on a quoted phrase gives its plain meaning, not a word-for-word copy, and Spanish stays gender-neutral where the English doesn't state a person's gender (la persona amada for "the beloved").
- ELA SCAFFOLD writes the model example's answer out in full, without brackets around the part a student would fill in.
- Teacher check (ELA, History, Science): new line confirming no frame or hint gives away the answer.
- ELA SCAFFOLD leaves out the word bank when students write their own poem or story.
- ELA SCAFFOLD keeps the © symbol on copyright lines.
- TRANSLATE (ELA, History, Science): text that stays in English, such as a poem's lines, appears once instead of being repeated as its own Spanish line.
- FORMAT HTML (all four): numbered lists no longer print the number twice ("1. 1.").
- SCAFFOLD (ELA, History, Science): when no line fits the model example, or there is no reading, the model is written without quotes. It no longer prints "no supporting line found" on the student page.
- ELA SCAFFOLD keeps the original title, or names the task when there is none, and never labels the page "scaffolded."
- ELA SCAFFOLD, essays: the model example is one body-paragraph block, not a whole outline, and the thesis frame appears once, in the introduction.
- ELA SCAFFOLD keeps the original prompt and task text word for word, and adds no requirement the original doesn't set (such as a paragraph count).
- ELA SCAFFOLD: with no reading, the model example names no real book, author, or character and quotes nothing.
- FORMAT HTML (all four): directions, banks, and glossaries print before the model example and the questions.
- ELA SCAFFOLD, essays: every outline slot, including transitions, has a blank for the student's own words, never a finished sentence.
- ELA SCAFFOLD: a required transition word starts a frame, and the rest of that sentence is the student's blank. This fixes transitions and hooks printing as finished sentences.
- ELA TRANSLATE: body paragraph = párrafo de desarrollo.
- FORMAT HTML (all four): the page's HTML title is the worksheet's own title, so a printed header never says "scaffolded."
- ELA SCAFFOLD: the model example's quote comes from outside the word bank, so students keep every bank quote for their own answers.
- TRANSLATE (all four): in a glossary, the term stays on one line as English / Spanish, and the definition's Spanish goes on its own line beneath instead of running on after a slash.
- History SCAFFOLD trimmed from 766 to 740 words. It no longer tells Gemini to "say so" when the quote bank is short (that note could print on the page). The model example's quote comes from outside the quote bank, and a required transition word starts a frame with the rest of the sentence left blank, matching ELA.
- History SCAFFOLD: background facts only when the task asks for outside knowledge in words, so a DBQ that doesn't ask gets no background box.
- History SCAFFOLD: a data table printed as text gets no [VISUAL] marker, and "things to look for" name where to look (a label, an axis, a column), never what the visual shows.
- History SCAFFOLD: no labels explaining how a section was built (such as "based on an unused source quote").
- FORMAT HTML (all four): leftover Markdown is turned into HTML, so no asterisks print around glosses.
- History SCAFFOLD: never adds a requirement the original doesn't set, such as outside knowledge. A DBQ body block has a claim, two citations, and an explanation, nothing else. The model for a DBQ or essay is one body-paragraph block, never a thesis for the real prompt.
- TRANSLATE (all four): a glossary entry keeps its English definition, with the Spanish definition beneath it.
- History TRANSLATE: body paragraph = párrafo de desarrollo; tenement = casa de vecindad (not the regional "conventillo").
- Science SCAFFOLD trimmed from 787 to 747 words, with fixes carried over from ELA and History: no "say so" note when the word bank is short; "things to look for" in a visual name where to look, never the trend; the model's quote comes from outside the word bank; a required transition word starts a frame and the rest of the sentence is blank; no labels explaining how a section was built.
- Science SCAFFOLD: when an item asks students to name a term, the terms bank lists the term with no definition, so the bank can't be matched word for word to the questions. The model example is written out in full with no blanks. Every heading, overview, direction, and item number from the original is kept. Shorter wording elsewhere keeps the prompt at 746 words.
- Science CHECK: when the task uses a diagram or graph, CHECK lists every label the questions name and says whether each one is actually on it (or tells the teacher to check, if it can't read the image). It no longer prints "I cannot read" when it can read the labels.
- Science SCAFFOLD: the model example is described as a finished student answer with every blank already filled in (Gemini kept leaving the reasoning blank).
- FORMAT HTML (all four): a model or worked example prints complete, with no blanks and no writing lines after it.
- Science SCAFFOLD: every part of the model example, reasoning included, comes from the materials, and Gemini picks an item the materials fully answer. This removes the conflict with the no-outside-facts rule that kept leaving the model's reasoning blank. Simplified directions keep every requirement the original states (such as "your knowledge of science").
- FORMAT HTML (ELA, History, Science): a sentence frame replaces the original's answer line instead of printing both.
- Science SCAFFOLD: "things to look for" never name a label an item asks students to find. For a diagram, the model example identifies one label no item asks about, so it never needs reasoning the materials don't give.
- Step 1 instructions (all four): type question numbers by hand, because Word's automatic list numbering can disappear in the output.
- FORMAT HTML (all four): one writing line per header field, labeled once in both languages (Name / Nombre), instead of a second line for the Spanish label.
- FORMAT HTML (ELA, History, Science): the two writing lines at the end of each question print dark enough to see.

## 2026-10-26

- FORMAT HTML (all four): every blank and bracketed hint now becomes an empty writing line, with the hint's words in small gray type under the line instead of printed on it. Blanks stay inline in their sentences; in ELA, History, and Science each question ends with two full-width writing lines. Writing lines appear only in the English line of a frame, so students have one place to write.
- ELA SCAFFOLD stops and asks for the reading if it is missing, instead of building a scaffold without it.
- ELA SCAFFOLD, creative writing: frames go in a planning box, never on the poem or story lines, which stay empty as in the original.
- ELA SCAFFOLD keeps a checklist word for word, with no blanks added.
- ELA SCAFFOLD no longer prints a note on the page when the word bank is short.
- ELA FORMAT HTML prints a model example complete, never turned into blanks.
- ELA TRANSLATE uses standard poetry terms: la voz poética (speaker), verso (line), estrofa (stanza).
- Teacher check (ELA, History, Science): new line confirming every frame has room to write.

## 2026-10-20

- Download buttons for each package and a "Download all four" zip on the packages page.
- Saved copies now show a notice with their version date and a link to the latest version. The prompts did not change.

## 2026-10-19

- First release on GitHub: ELA, History, Science, and Math packages.
