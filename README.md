# Hi, I'm Sam 👋

**I build software and explore research questions through an iterative collaboration with AI.** My background is in operations and business systems, where checking records, investigating discrepancies and working through exceptions are part of the job. I bring that experience to how I question outputs and test results.

I start with ideas and goals, then work back and forth with AI systems as they propose approaches, write code and, in my research, draft mathematics. I have them challenge each other's reasoning. I also question them along the way and ask for explanations I can follow. I help steer the work through discussion and testing, and I'm learning Python so I can take on more implementation myself.

![AI-Collaborative](https://img.shields.io/badge/Method-AI--Collaborative_Development-blueviolet?style=for-the-badge)
![Learning Python](https://img.shields.io/badge/Currently_Learning-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Builds Hardware](https://img.shields.io/badge/Also-Builds_His_Own_Hardware-orange?style=for-the-badge)

---

## 🔬 Featured project: [rarita-schwinger-well-posedness](https://github.com/samderenzis/rarita-schwinger-well-posedness)

[![Paper](https://img.shields.io/badge/paper-PDF-informational?style=flat-square)](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/paper/main.pdf)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.24413648-blue?style=flat-square)](https://doi.org/10.5281/zenodo.24413648)
![Validator](https://img.shields.io/badge/validator_%2836_checks%29-COMPLETE__PASS-brightgreen?style=flat-square)
![Status](https://img.shields.io/badge/status-not_peer_reviewed-orange?style=flat-square)

**The question.** Are the equations for a **charged, massive spin-3/2 (Rarita–Schwinger) field** well-behaved? Physicists have worked on this since the Velo–Zwanziger problem of the 1960s.

**What the paper states.** It gives a theorem, with a written proof, for one explicit setting: a curved background with a steady magnetic field, at one exact parameter point. In that setting, the equations **cannot have existence, uniqueness and a loss-free energy bound all at once**. The obstruction is an exact, checkable algebraic structure: a Jordan block.

**How it was checked.**
- The work developed iteratively between me, Claude and ChatGPT. Their roles overlapped; for specific steps, one system audited the other's work.
- Key lemmas were tested by statement-only blind derivations, with hash-frozen records.
- The algebra was checked exactly, in three engines.
- Mutation tests confirm that the checks catch faults introduced on purpose.
- An AI review of the paper, code and archive reported no errors in the mathematics.
- `COMPLETE_PASS` is the validation suite's own reported status for its 36 checks. It is not a certification of the theorem.

**Check it yourself.**
- The exact witness can be checked with Python, with no third-party packages required.
- The full validator needs a few packages. It took about 3 minutes on my 12-core desktop.
- See the [paper](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/paper/main.pdf), the [repository](https://github.com/samderenzis/rarita-schwinger-well-posedness), the [archived releases on Zenodo](https://doi.org/10.5281/zenodo.24413648), and the [guide to running the validator](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/RUNNING_THE_VALIDATOR.md).

**Status.**
- Reviewed by AI systems only.
- **Not yet reviewed by a human expert, not independently replicated, and not formally machine-verified.**
- Narrow scope: one setting, one parameter point.
- It does not say which of the three properties fails, and no broader physical conclusion should be drawn from it.
- Feedback from specialists in hyperbolic PDE or higher-spin fields is very welcome.

🧭 **Follow-up:** two separate, exploratory repos ask whether the breakdown survives when the charge is varied on its own, off the "Pauli slice". [rarita-schwinger-off-slice](https://github.com/samderenzis/rarita-schwinger-off-slice) has AI-checked results along that direction (exact Jordan chains at the split crossings). [rarita-schwinger-off-slice-certificates](https://github.com/samderenzis/rarita-schwinger-off-slice-certificates) (release B6.6.1) adds exact-arithmetic certificates, an independent verifier, and planted-bug and mutation tests that check the verifier itself. It was reviewed by ChatGPT and Perplexity and is not yet reviewed by a human expert.

## 🔨 What I build (with AI)

| Area | What that looks like |
|---|---|
| 🔬 **Research verification** | Validation suites, exact-arithmetic checks, hash-pinned archives, mutation tests that confirm the checks catch introduced faults ([rarita-schwinger-well-posedness](https://github.com/samderenzis/rarita-schwinger-well-posedness), [rarita-schwinger-off-slice-certificates](https://github.com/samderenzis/rarita-schwinger-off-slice-certificates)) |
| 📄 **Document processing** | PDF parsing, form generation, data extraction pipelines (Python) |
| 🗂️ **Structured data** | JSON modeling, schema inference, CSV/flat-file processing |
| 📊 **Excel/VBA applications** | Config-driven rule tables, batch processing, a self-testing framework that checks its own behavior |

These projects use AI-written code, developed through the collaborative process described above. *More repos coming as I clean them up for sharing.*

## 🧭 How I work

- 🔎 For tasks I know firsthand, I use that experience to judge whether an automated result makes sense. In unfamiliar technical work, I ask for explanations and rely on tests and cross-checks, not a convincing answer.
- 📋 Write down the goal, clarify the rules, and refine the requirements as the work develops
- ✅ Tests over hope, including deliberately broken inputs that the tests must catch
- 🔁 Multiple AI systems used to challenge proposed solutions, surface disagreements and guide revisions
- 📓 Negative results and failed attempts stay on the record

## 📚 Currently learning

![Python](https://img.shields.io/badge/Python-fundamentals-3776AB?style=flat-square&logo=python&logoColor=white)
![Google IT Support](https://img.shields.io/badge/Google_IT_Support-Certificate_in_progress-4285F4?style=flat-square&logo=google&logoColor=white)
![College Coursework](https://img.shields.io/badge/College-transferable_coursework-green?style=flat-square)

## 🖥️ Hardware & systems toolbox

![Windows](https://img.shields.io/badge/Windows_11-diagnostics_%26_admin-0078D6?style=flat-square&logo=windows&logoColor=white)
![BIOS](https://img.shields.io/badge/BIOS%2FUEFI-flashing_%26_tuning-critical?style=flat-square)
![Sysinternals](https://img.shields.io/badge/Sysinternals-Process_Explorer-lightgrey?style=flat-square)
![Rufus](https://img.shields.io/badge/Rufus-boot_media-blue?style=flat-square)
![Ubuntu](https://img.shields.io/badge/Ubuntu-past_daily_driver-E95420?style=flat-square&logo=ubuntu&logoColor=white)

Hands-on: two custom AM5 builds (one runs my research validation on a Ryzen 9 9900X), BIOS-level recovery, Event Viewer root-cause diagnosis, manual driver/firmware management, disk sanitization.

## 🌱 Off the clock

Photography · Sci-fi · K-dramas · Music · Cats 🐈

## 📫 Connect

[![Email](https://img.shields.io/badge/Email-waitandhope123%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:waitandhope123@gmail.com)
[![Credly](https://img.shields.io/badge/Credly-verified_credentials-FF6B00?style=flat-square)](https://www.credly.com/users/sam-derenzis)

📍 Chicago area
