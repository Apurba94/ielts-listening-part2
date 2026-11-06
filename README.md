# Part 2 Talks

Listen to talks about everyday places and events, such as a museum tour or a sports club, and answer Part 2 style questions.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Part 2 Talks.exe` from the [latest release](https://github.com/Apurba94/ielts-listening-part2/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-listening-part2/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

In Listening Part 2 one speaker talks about a local place, service or event: a volunteer briefing, a library reopening, a festival or a castle tour. This app has eight original talks with 64 questions in the IELTS styles: multiple choice, note and table completion, and choose TWO from five.

Sections: Talks, Progress, About.

## How to use it

1. Choose whether to hear each talk once, as in the test.
2. Press **Start the next new set**, read the questions first, then press Play.
3. Questions follow the order of the talk. If you miss one, move on to the next.
4. After checking, read the transcript to find where each answer was.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
