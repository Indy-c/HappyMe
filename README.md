# HappyMe Happiness Quiz

HappyMe is a responsive, accessible, one-minute self-reflection quiz that helps people discover their happiness style: Connection Seeker, Peace Finder, Creative Spark, or Little Explorer.

## Live demo

Open [`HappyMe_Happiness_Quiz.html`](./HappyMe_Happiness_Quiz.html) directly in your browser, or visit the GitHub Pages URL after Pages is enabled for this repository.

## Features

- Five quick, multiple-choice questions
- Four personalized happiness styles
- Progress tracking and Back navigation
- Replay and copy-result actions
- Responsive design for mobile and desktop
- Keyboard-visible focus states and reduced-motion support
- No accounts, tracking, database, or external dependencies

## Run locally

The quiz is a standalone HTML file and requires no build step or installation.

1. Clone the repository:

   ```bash
   git clone https://github.com/Indy-c/HappyMe.git
   cd HappyMe
   ```

2. Open `HappyMe_Happiness_Quiz.html` in a browser.

For a local web server, VS Code's Live Server extension or a command such as `python -m http.server 8080` can be used.

## Project structure

```text
.
├── HappyMe_Happiness_Quiz.html  # Complete application
├── docs/
│   ├── usage.md                 # User guide
│   ├── design.md                # Quiz and interface notes
│   └── privacy.md              # Data and privacy statement
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── LICENSE
```

## Documentation

- [Usage guide](docs/usage.md)
- [Design and scoring](docs/design.md)
- [Privacy statement](docs/privacy.md)
- [Contributing guidelines](CONTRIBUTING.md)

## Privacy

HappyMe runs entirely in the user's browser. Answers are held only in memory and are not submitted or persisted. The Copy Result button is the only feature that places result text on the device clipboard.

## Disclaimer

HappyMe is a fun self-reflection activity, not a medical or psychological assessment.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
