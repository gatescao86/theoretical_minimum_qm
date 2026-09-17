# The Theoretical Minimum

Notes and solutions for Leonard Susskind’s *Theoretical Minimum* series, starting with *Quantum Mechanics* (with Art Friedman).

Problem statements stay in the book. This repo is for your own notes, restatements, and write-ups.

## Layout

```
quantum-mechanics/
  README.md                          progress + chapter index
  00-front-matter/notes.md
  01-systems-and-experiments/
    notes.md
    exercises/1.1.md
    exercises/1.2.md
  02-quantum-states/
  …
  10-the-harmonic-oscillator/
  appendix/notes.md
templates/                           copy these when a new file is needed
macros.md                            how to write bra-ket math
latex/macros.tex                     same macros for a future PDF
```

Each chapter has a `notes.md` with the book’s section headings already sketched in, and one Markdown file per exercise.

Later volumes can sit next to `quantum-mechanics/`:

- `classical-mechanics/`
- `special-relativity-and-classical-field-theory/`
- `general-relativity/`

## Writing math

Use LaTeX inside Markdown. Open it with **Markdown: Open Preview to the Side** (`⌘K V`), not the Preview | Markdown toggle — that tab does not render `$...$` math.

Inline:

```md
The inner product satisfies $\langle B|A\rangle = \langle A|B\rangle^*$.
```

Display:

```md
$$
\begin{aligned}
\langle A+B|C\rangle
&= \langle C|A+B\rangle^* \\
&= \langle A|C\rangle + \langle B|C\rangle
\end{aligned}
$$
```

See [macros.md](macros.md) for bra-ket shortcuts (`\ket`, `\braket`, …). Those are defined in [`.vscode/settings.json`](.vscode/settings.json) so Preview can render them. Copy [templates/exercise.md](templates/exercise.md) when you add a problem that is not already stubbed.

## Conventions

- **Status** on each file is `Not started`, `In progress`, or `Done`.
- Restate the problem in your own words. Do not paste the book.
- Prefer a short check (normalization, hermiticity, a limiting case) after a derivation.
