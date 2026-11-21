# Hi, I'm Sam 👋

**I build real software and research through AI-collaborative work.**
I come up with the projects, design how they should work, write the requirements, and test everything myself, while AI writes the code (and, in my research, drafts the mathematics) under my direction. I'm not the programmer yet: I'm the architect, product owner, and QA. I think that split is the interesting part, so I'm honest about it.

![AI-Collaborative](https://img.shields.io/badge/Method-AI--Collaborative_Development-blueviolet?style=for-the-badge)
![Learning Python](https://img.shields.io/badge/Currently_Learning-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Builds Hardware](https://img.shields.io/badge/Also-Builds_His_Own_Hardware-orange?style=for-the-badge)

---

## 🔬 Featured project: [rarita-schwinger-well-posedness](https://github.com/samderenzis/rarita-schwinger-well-posedness)

[![Repo](https://img.shields.io/badge/GitHub-rarita--schwinger--well--posedness-181717?style=flat-square&logo=github)](https://github.com/samderenzis/rarita-schwinger-well-posedness)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.24413648-blue?style=flat-square)](https://doi.org/10.5281/zenodo.24413648)
![Validation](https://img.shields.io/badge/validation-COMPLETE__PASS-brightgreen?style=flat-square)
[![Paper](https://img.shields.io/badge/paper-v2_(PDF)-informational?style=flat-square)](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/paper/main.pdf)
![Status](https://img.shields.io/badge/status-not_peer_reviewed-orange?style=flat-square)

*AI-collaborative mathematical physics (internal programme name: BHMAP).*

A long-running research programme on whether the equations for a **charged, massive spin-3/2 (Rarita–Schwinger) field** are well-behaved, a question physicists have studied since the Velo–Zwanziger problem of the 1960s.

- **Result:** a theorem, with a written proof in the [paper](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/paper/main.pdf), that in one explicit setting (a curved background with a steady magnetic field, at an exact parameter point) the equations **cannot have existence, uniqueness and a loss-free energy bound all at once**. The breakdown is pinned to an exact, checkable algebraic "fingerprint" (a Jordan block).
- **How it was checked:** Claude and ChatGPT worked as implementer and auditor, with statement-only blind tests and hash-frozen records; I also use Perplexity for literature searches and physics cross-checks. The exact-check scripts were re-run by a second AI from the original files, and ChatGPT did a full review of the paper, code and archive, finding no error in the mathematics. A validation suite I designed (now 36 checks) passed completely (`COMPLETE_PASS`) on my own PC, on the full private archive and on the public repository: exact algebra in three engines, numerical stress tests, file integrity, self-tests that must catch deliberate faults, and every cited DOI and arXiv ID confirmed to exist online.
- **Check it yourself:** the repository has the paper and its LaTeX source, the exact witness (checkable with plain Python, no installs), the exact-check scripts, and the validator, with a [guide to running it](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/RUNNING_THE_VALIDATOR.md). About 3 minutes on a desktop.
- **Honest status:** reviewed by AI systems only. It is **not yet reviewed by a human expert, not independently replicated and not formally machine-verified**. Narrow scope: one setting, one parameter point. It doesn't say which of the three properties fails, and makes no physical claims. Feedback from specialists in hyperbolic PDE or higher-spin fields is very welcome.

📦 Repository and archived releases: [GitHub](https://github.com/samderenzis/rarita-schwinger-well-posedness) · [Zenodo](https://doi.org/10.5281/zenodo.24413648)  
📄 Paper: [version 2 (PDF, 27 pages)](https://github.com/samderenzis/rarita-schwinger-well-posedness/blob/main/paper/main.pdf), posted in release [v1.0.9](https://github.com/samderenzis/rarita-schwinger-well-posedness/releases/tag/v1.0.9) with its LaTeX source, after reviews by Perplexity and ChatGPT. Next step: independent review by a human expert.

## 🔨 What I build (AI-directed)

| Area | What that looks like |
|---|---|
| 🔬 **Research verification** | Validation suites, exact-arithmetic checks, hash-pinned archives, mutation tests that prove the checks can fail ([rarita-schwinger-well-posedness](https://github.com/samderenzis/rarita-schwinger-well-posedness)) |
| 📄 **Document processing** | PDF parsing, form generation, data extraction pipelines (Python) |
| 🗂️ **Structured data** | JSON modeling, schema inference, CSV/flat-file processing |
| 📊 **Excel/VBA applications** | Config-driven rule tables, batch processing, a self-testing framework that verifies its own code |

*More repos coming as I clean them up for sharing.*

## 🧭 How I work

> I don't trust automation until I've done the job manually and understand what the tool is deciding for me.

- 📋 Requirements written down **before** anything gets built
- 📏 Measure first, configure second
- ✅ Test frameworks over hope, including tests that are deliberately broken to prove they can fail
- 🔁 Separate re-checking: never let one AI grade its own work
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

Two custom AM5 builds (one runs my research validation on a Ryzen 9 9900X), BIOS-level recovery, Event Viewer root-cause diagnosis, manual driver/firmware management, disk sanitization.

## 🌱 Off the clock

Photography · Sci-fi · K-dramas · Music · Cats 🐈

## 📫 Connect

[![Email](https://img.shields.io/badge/Email-waitandhope123%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:waitandhope123@gmail.com)
[![Credly](https://img.shields.io/badge/Credly-verified_credentials-FF6B00?style=flat-square)](https://www.credly.com/users/sam-derenzis)

📍 Chicago area
