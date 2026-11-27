# Quiz Quick

Quiz Quick is a browser-based quiz application for **Electronic Devices and Circuits**. It presents randomized questions, modes, hints, explanations, score tracking, streaks, and a final results review.

## Features

- 30-minute timed quiz, 20-question quiz, or 10-minute rapid round
- Hint and answer explanations
- Keyboard controls
- Current score, streak, and personal best
- Dark and light themes
- Confetti and responsive layout
- Final score summary with missed-question review

## Run locally

Open `index.html` directly in a browser, or serve the project locally:

```powershell
py -m http.server 8000
```

Then visit `http://localhost:8000`.

## Quiz modes

| Mode | Duration | Questions |
| --- | ---: | ---: |
| Focus | 30 minutes | 20 |
| Standard | 30 minutes | 30 |
| Blitz | 10 minutes | 20 |

## Controls

- Use **A**, **S**, **D**, or **F** to select answer options.
- Use **H** to reveal a hint.
- Use **Enter** or **N** to continue after answering.
- Use the theme button to switch between dark and light modes.

## Project structure

- `index.html` - Complete application, styles, quiz data, and JavaScript
- `README.md` - Project documentation

## Author

**Avinash Singh Paviya**  
B.Tech EACE student, Centre for IoT, Madhav Institute of Technology & Science (MITS-DU), Gwalior.
