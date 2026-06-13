# ATS-Friendly Resumes: Getting Past the Software First

Most large employers read your resume with software before a person ever sees it. This guide covers how that software works and what formatting choices keep your resume readable — which matters whether you're applying for a working-student job in Munich or a graduate role in Milan.

## Contents

- [What an ATS is](#what-an-ats-is)
- [How to tell which one a company uses](#how-to-tell-which-one-a-company-uses)
- [Formatting rules that matter](#formatting-rules-that-matter)
- [Keywords](#keywords)
- [PDF or DOCX](#pdf-or-docx)
- [Check before you send](#check-before-you-send)
- [Myths](#myths)

## What an ATS is

An Applicant Tracking System is the software an employer uses to collect and manage applications. Before a recruiter opens your file, the ATS converts it to plain text and sorts that text into fields — name, contact details, employers, titles, dates, skills. Recruiters then search that database the way you'd use a search engine, by title, skill, and keyword.

A common myth is that the ATS scores and auto-rejects you. Most big systems don't work that way; they parse and store, and a human searches. The failure you actually need to avoid is being unsearchable because your text came out scrambled or your terms don't match what the recruiter typed.

## How to tell which one a company uses

You can usually identify the ATS from the careers or apply URL.

| If the apply URL contains… | The ATS is | Note |
| --- | --- | --- |
| `myworkdayjobs.com` | Workday | Common at large enterprises; long forms. |
| `boards.greenhouse.io` | Greenhouse | Common in tech; modern parser. |
| `jobs.lever.co` | Lever | Startups and scale-ups. |
| `jobs.ashbyhq.com` | Ashby | Newer; strong parsing. |
| `*.icims.com` | iCIMS | Older enterprise; keep layouts simple. |
| `*.taleo.net` | Taleo (Oracle) | Legacy; the strictest about formatting. |
| `*.successfactors.com` | SAP SuccessFactors | Common at large European firms. |
| `apply.workable.com` | Workable | SMBs and scale-ups. |

Legacy systems (Taleo, older iCIMS) are where conservative formatting pays off most. Modern ones (Greenhouse, Lever, Ashby, Workday) read a clean text-based PDF without complaint.

## Formatting rules that matter

Four things decide whether a parser files you correctly. Everything else is for the human who reads you afterward.

1. **The text must be real, selectable text** — not an image or vector shapes. If you can't highlight it in a PDF viewer, the parser can't read it.
2. **The reading order must be predictable.** Parsers read the content stream, not the visual layout. A two-column design is fine only if the underlying text still flows header → summary → experience in order.
3. **Headings should name the sections.** "Experience," "Education," and "Skills" map straight into ATS fields. Inventive labels get your history filed under "other."
4. **Fonts must export characters, not outlines.** Some display typefaces turn text into shapes on export; it looks identical and reads as nothing.

## Keywords

After parsing, your resume becomes rows in a database that recruiters query by literal terms. If the posting says "stakeholder communication" and your resume says "talking to clients," you won't surface for that search. Mirror the posting's exact vocabulary for skills, tools, and titles wherever it's true of you — and don't stuff terms you can't defend in an interview.

## PDF or DOCX

The old "never send a PDF" advice dates from parsers that genuinely choked on them. Modern systems read text-based PDFs fine. What still breaks applications is a PDF whose text doesn't extract — a scanned image, outlined text, or a multi-column layout that scrambles reading order. If a posting asks for DOCX, send DOCX; otherwise a clean, text-based PDF keeps your layout stable and parses well.

## Check before you send

The cheapest test: open your PDF, select all, copy, and paste into a plain text editor. If the result is scrambled, glued together, or missing chunks, an ATS sees the same mess.

For a fuller check, [Prezumi's free ATS resume checker](https://www.prezumi.com/tools/ats-resume-checker) runs real text extraction on your PDF and shows you exactly what a parser pulls out, plus a score for reading order, sections, and contact details. No signup. If you'd rather start from a layout that's already extraction-tested, the [ATS-friendly resume templates](https://www.prezumi.com/templates/resumes/ats-friendly) are built and checked for clean parsing, and the resume download is free.

Once the structure parses cleanly, the words matter. A [resume buzzword checker](https://www.prezumi.com/tools/resume-buzzword-checker) flags the empty filler — "results-driven", "team player", "synergy" — that recruiters skim past, so you can replace it with something concrete.

## Myths

- **"The ATS auto-rejects most resumes."** No. Most big systems parse and store; a recruiter searches. The widely cited figure is that around three-quarters of mid-size and large *employers use* ATS software, not that they auto-bin that share of resumes.
- **"Any design kills your resume."** No. Modern parsers handle clean, styled, single-flow PDFs. Text-as-image and scrambled columns break parsing — color and a sidebar don't.
- **"You need a different resume per ATS."** No. One clean, text-based, single-flow resume parses across all the major systems.
- **"Hidden white-text keywords beat the ATS."** They get you past nothing and flag you to the human, who sees hidden text the moment they select-all.
