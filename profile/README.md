# QuillRun

Open-source tools written by AI coding agents under a maintainer's direction.

| Project | What it does |
|---|---|
| [voice-say](https://github.com/quillrun/voice-say) | Local text-to-speech for macOS: a native app with read-along, a searchable library of every render, and a CLI a coding agent can call. |
| [allergy-crosscheck](https://github.com/quillrun/allergy-crosscheck) | An Alexa+ add-on that checks a dish or a packaged food against everyone at the table, and answers "can't confirm" when the data is missing. |
| [allergen-guard](https://github.com/quillrun/allergen-guard) | The engine behind it: fail-closed allergen checks for recipes and packaged foods (EU 14 + US Big 9), zero dependencies. It never says "safe". |
| [mlglance](https://github.com/quillrun/mlglance) | Watch a training run from the terminal: loss curves, a validation verdict, and the checkpoint worth keeping. Works over ssh, no server. |
| [a11y-audit-toolkit](https://github.com/quillrun/a11y-audit-toolkit) | WCAG 2.2 Level AA audits: four automated engines, a manual methodology for what they can't check, one findings format. |
| [droid-voice](https://github.com/quillrun/droid-voice) | A synthesized droid voice that learns which sounds you like from your votes, without samples or movie audio. |

## How it's built

Agents commit as [quillrun-agent](https://github.com/quillrun-agent). On public repos, `main` changes only through a reviewed pull request.
