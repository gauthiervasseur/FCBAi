# You are generating a Marp Markdown slide deck using the fcba theme.

**SOURCE OF TRUTH (MUST FOLLOW)**
- Use the exact slide patterns, backgroundImage paths, and classes shown in applied-template.md.
- The deck will be styled by FCBAi.css (theme: FCBAi), so do not invent new classes unless they already exist in the template.
- Keep slide titles as H1 (#). No emojis in slide titles.

**OUTPUT FORMAT (HARD RULES)**
1) Output ONLY the final Marp Markdown (no explanations).

2) Start with the Marp front matter:

   ---
   marp: true
   theme: FCBAi
   ---

3) Use `---` to separate slides.

4) Always include:
   - Title slide (class: title + Intro.png background)
   - Content slides that mix layouts (classic + inverted)
   - Chapter separators using the 3 header backgrounds:
     * Header1.png with #### Chapter
     * Header2.png with ##### Section
     * Header3.png with ###### Sub-Section
   - At least 2 intermediate callout/transition slides using intermediate.png
   - Final closer slide using Closer.png background

5) Use only these background templates (as in applied-template.md):
   - bkg/FCBAi/Intro.png
   - bkg/FCBAi/headers/Header1.png
   - bkg/FCBAi/headers/Header2.png
   - bkg/FCBAi/headers/Header3.png
   - bkg/FCBAi/content/classic/Content_Right_Classic.png
   - bkg/FCBAi/content/classic/Content_Left_Classic.png
   - bkg/FCBAi/content/classic/Content_Classic.png
   - bkg/FCBAi/content/classic/Content_2col_classic.png
   - bkg/FCBAi/content/classic/Content_3col_classic.png  (use with _class: small)
   - bkg/FCBAi/content/inverted/Content_right_inverted.png (use with _class: inverted)
   - bkg/FCBAi/content/inverted/Content_Left_inverted.png  (use with _class: inverted)
   - bkg/FCBAi/content/inverted/Content_inverted.png       (use with _class: inverted)
   - bkg/FCBAi/content/inverted/Content_2col_Inverted.png   (use with _class: inverted)
   - bkg/FCBAi/content/inverted/Content_3col_Inverted.png   (use with _class: small_inverted)
   - bkg/FCBAi/intermediate.png
   - bkg/FCBAi/Closer.png

**SLIDE DESIGN LOGIC (WHAT TO USE WHEN)**
- Title slide: deck title + subtitle (author) + date.
- Header1 slide: whenever you start a new major chapter (3–6 content slides per chapter).
- Header2 slide: for sections inside a chapter.
- Header3 slide: for a short sub-section (1–2 slides) or a “zoom-in” topic.
- Intermediate slide (intermediate.png): use for a punchy callout, transition, or “question to the room”.
- Content choices:
  - Use Content_Right_Classic / Content_Left_Classic when you have a strong image + 2 short “##” blocks.
  - Use Content_Classic when you want either:
      a) a single big image (use `![bg% h:400](...)`), OR
      b) a bullet list (4–6 bullets max).
  - Use 2col when comparing (pros/cons, now/next, options, tradeoffs). Use <div class="columns2"> exactly like the template.
  - Use 3col (small/small_inverted) for frameworks, triads, or “3 lenses”.
  - Use inverted variants for emphasis, contrast, or “serious” slides (risks, governance, warnings, decisions).
  - Include at least one table slide when you have metrics, a checklist, or a summary grid.

**CONTENT RULES**
- Keep text crisp: prefer short lines and high signal density.
- If you use bullets: avoid paragraphs inside bullets; keep each bullet to one idea.
- Favor “executive” language: decisions, implications, actions.
- When you include images:
  - Use Marp background-positioned images exactly like the template:
    `![bg left:25%](...)` or `![bg right:25%](...)`
  - If no real image is provided, insert a placeholder URL or a local placeholder path (do not leave empty).
- End with a closer slide (Closer.png). If you include text on the closer, keep it minimal (1–2 lines).

**INPUTS (I WILL PROVIDE THESE)**
- Topic:
- Audience:
- Deck title:
- Author name:
- Date:
- Desired length (approx slide count):
- Chapters (if any):
- Must-include points:
- Optional: image URLs (or say “use placeholders”):
- Optional: any metrics/data to tabulate:

**NOW GENERATE THE DECK**
- Create a coherent narrative from intro → chapters → wrap-up.
- Use a varied mix of classic/inverted, 1/2/3-column layouts, and intermediate transitions.
- Output the complete Marp Markdown only.
