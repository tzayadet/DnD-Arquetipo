<p align="center">
  <img src="https://img.shields.io/badge/INTERACTIVE_QUIZ-D%26D_ARCHETYPE-101010?style=for-the-badge&labelColor=050805&color=00FF41" alt="D&D Archetype"/>
  <img src="https://img.shields.io/badge/WEB_APP-JAVASCRIPT-101010?style=for-the-badge&logo=javascript&logoColor=00FF41" alt="JavaScript"/>
</p>

# D&D Archetype

Interactive character assessment inspired by Dungeons & Dragons. The questionnaire maps answers across six dimensions and presents an archetype from thirteen possible classes.

<p align="center">
  <a href="https://tzayadet.github.io/DnD-Arquetipo/"><strong>LIVE DEMO ↗</strong></a> ·
  <a href="https://github.com/tzayadet/DnD-Arquetipo"><strong>SOURCE CODE</strong></a>
</p>

## Features

- 120-question assessment.
- 13 character classes.
- Six assessment dimensions.
- Downloadable results.
- Browser-based interactive experience.

## Use it

Open the [live demo](https://tzayadet.github.io/DnD-Arquetipo/) in a modern browser. The public site is a static browser experience.

## Backend experiment

The repository also contains a small Java assessment server experiment. To compile and run it:

```bash
javac Assessment.java
java Assessment 8080
```

The server listens locally on port 8080. The GitHub Pages demo is static and does not depend on this local server.

## Project structure

The interactive frontend and Java experiment are separate components. The published experience does not imply that the Java backend is hosted or connected.

## Scope

This is a recreational character-assessment project, not a validated psychological instrument or a clinical/personality assessment.

## Deployment

Static site published through GitHub Pages.

## License

See [LICENSE](LICENSE) for the repository's licensing terms.
