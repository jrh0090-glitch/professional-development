# Bilingual Assignment Prompts

Jennifer Hess · ESOL Education · Huntsville City Schools

## What this is

These are copy-and-paste prompts for Gemini/NotebookLM that take assignments and create a bilingual English/Spanish version your multilingual learners can use, keeping the same standard. Spanish sits directly under each English line. For assignments where students explain, analyze, or write, the prompts also add supports: plain-English directions, word and term banks, a worked or model example on a different item, and sentence frames. Tests and quizzes are translated only, never scaffolded.

## Which file to download

Download only the file for your subject from the [packages page](https://jenniferhess.info/bilingual-packages/), or all four in [bilingual-packages.zip](bilingual-packages.zip). Each one is a single page with all five prompts, the steps, and the teacher check. These are not Word docs or files you edit in Google Drive. They are HTML files you download and open on your computer; each one opens in your web browser.

| File | Use it for |
| --- | --- |
| [ela.html](ela.html) | Reading responses, literary analysis, essays, vocabulary, ELA quizzes and tests |
| [history.html](history.html) | Source analysis, DBQs, cause-and-effect and compare charts, timelines, guided notes, history quizzes and tests |
| [science.html](science.html) | Labs and lab reports, CER conclusions, data and graph analysis, readings, science quizzes and tests |
| [math.html](math.html) | Word problems, practice sets, explain or justify items, error analysis, proofs, math quizzes and tests |

## Opening a file

1. Click Download for your subject on the packages page (or unzip the zip file).
2. Open your Downloads folder and double-click the file. It opens as a web page in your browser.
3. Each prompt has a Copy prompt button. Click it, then paste into Gemini.

A saved copy won't update. Each copy shows its version date; check the [changelog](CHANGELOG.md) for newer versions. If a Copy prompt button doesn't work, select the prompt text with your mouse and copy it by hand.

## The five steps

Every assignment goes through the same steps. CHECK decides whether you need SCAFFOLD; you never have to decide that yourself.

1. **Upload one assignment to Gemini**, with its reading or sources if it has them.
2. **Paste CHECK.** It tells you what the assignment is, what's missing, and which prompt to run next.
3. **Do what CHECK says.**
    - Students explain, analyze, write, or solve word problems: paste SCAFFOLD, then TRANSLATE.
    - Quiz, test, vocabulary, notes, or plain practice: paste TRANSLATE only.
4. **Paste FORMAT HTML** to get a styled, print-ready page. Save the code as an .html file, open it in Chrome, and press Ctrl+P (Cmd+P on a Mac) to print or save as PDF.
5. **Do the teacher check** on any assignment before you print it.

If the Spanish isn't in italics or runs into the English, paste FIX ITALICS once in the same chat.

## Rules that prevent most problems

- **Remove the answer key before uploading.** If one is still in the file, CHECK stops and asks you to remove it and upload again.
- **One assignment per run.** A worksheet with parts A, B, and C is one assignment. A unit packet with several separate worksheets is several runs.
- **Upload the original Doc or Word file when you have it.** Scanned PDFs can lose words, flatten exponents, and drop minus signs.
- **Use a fresh chat for long work.** Run SCAFFOLD, then copy its result into a new Gemini chat for TRANSLATE and FORMAT HTML. Long chats fail with "I seem to be encountering an error."
- **Upload blank assignments only.** No student names, grades, or student work.

## The teacher check is required

Gemini can change your assignment without telling you, so every page needs a two-minute check against your original before it's printed. The full checklist is at the bottom of each subject file. In testing, Gemini:

- dropped a minus sign from a number, twice, on the same worksheet
- reported a value as missing from the original when it had misread it
- quietly "corrected" a typo it thought it saw
- wrote a hint or a background fact that gave away an answer
- stopped partway through a long page, leaving the last question without its answer choices

None of these get flagged on their own. Compare every number, sign, and symbol to the original; read every hint and frame for anything that gives away an answer; and confirm the last item is complete. Anything marked [CHECK ORIGINAL] or [UNREADABLE] needs you to fix it by hand.

## Known Gemini quirks

Gemini gives slightly different results each time, and a few things go wrong often enough to plan for.

| What happens | What to do |
| --- | --- |
| "I seem to be encountering an error" | The chat got too long. Copy the last good result into a new chat and continue there. |
| Gemini gives you a file or opens a side panel instead of replying in the chat | That's still the result of the step you ran. Paste the next prompt as usual. |
| The HTML stops partway through | Type "continue" in the same chat, or run FORMAT HTML again in a new chat. |
| Gemini's copy button grabs the wrong message | Select the text you want with your mouse and copy it by hand. |
| Graphs, diagrams, and photos come out as dashed boxes | Gemini can't reproduce images. Paste the original image into the box, or hand out the original page with the worksheet. |
| A prompt refuses or asks for something | It's doing its job. Attach what it names and run it again. |

## What has been tested

All four subjects are ready to use with the teacher check. Some assignment types haven't been run yet; if you use one, your results help.

| Subject | Tested on | Not yet tested |
| --- | --- | --- |
| ELA | In use by an ELA teacher | |
| History | Iroquois Confederacy reading with questions, Iran-Contra reading with questions, Rockefeller and the robber barons, American Revolution timeline | DBQs |
| Science | A lab with a data table, a multiple-choice test, a matching set | A diagram students must interpret |
| Math | Equations and proportions, domain and range, composition of functions, a multiple-choice trig test (including the answer-key stop) | Geometry proofs |

## Questions and feedback

Contact Jennifer Hess, ESOL, at jennifer.hess@hsv-k12.org. When something goes wrong, send the original assignment and what Gemini gave you; that's how the prompts get fixed. The [packages page](https://jenniferhess.info/bilingual-packages/) always has the newest versions, so download again rather than reusing an old copy.
