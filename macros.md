# Math macros

Write `$...$` for inline math and `$$...$$` for a displayed equation.

**Use the classic preview, not the Preview | Markdown toggle.** Cursor’s built-in Preview tab does not render KaTeX, so the source (`\langle`, `\rangle`, …) stays visible. From the text editor:

- `⇧⌘V` — Markdown: Open Preview
- `⌘K V` — Markdown: Open Preview to the Side

That webview is the one that uses KaTeX and [`.vscode/settings.json`](.vscode/settings.json).

Do **not** put `\newcommand` in a `$$` block. The classic preview treats that as a formula.

Bra-ket shortcuts in this workspace:

Then these work:

```md
$\ket{\psi}$
$\bra{\psi}$
$\braket{\phi}{\psi}$
$\ketbra{\psi}{\phi}$
$\expect{A}$
$\comm{X}{P}$
```

The same names live in [`latex/macros.tex`](latex/macros.tex) if you later compile a PDF. GitHub does not read the workspace macros, so on GitHub prefer the expanded form (`$\lvert \psi \rangle$`).

## Examples

Inner product (from Lecture 1):

$$\langle B|A\rangle = \langle A|B\rangle^*$$

A column-vector inner product:

$$
\langle B|A\rangle
= \begin{pmatrix} \beta_1^* & \beta_2^* & \beta_3^* \end{pmatrix}
\begin{pmatrix} \alpha_1 \\ \alpha_2 \\ \alpha_3 \end{pmatrix}
= \sum_i \beta_i^*\alpha_i
$$

A multi-line derivation:

$$
\begin{aligned}
\langle A+B|C\rangle
&= \langle C|A+B\rangle^* \\
&= \bigl(\langle C|A\rangle + \langle C|B\rangle\bigr)^* \\
&= \langle A|C\rangle + \langle B|C\rangle
\end{aligned}
$$

## Common notation in this book

| Meaning | Shortcut | Expanded form |
|---|---|---|
| Ket | `$\ket{\psi}$` | `$\lvert \psi \rangle$` |
| Bra | `$\bra{\psi}$` | `$\langle \psi \rvert$` |
| Inner product | `$\braket{\phi}{\psi}$` | `$\langle \phi | \psi \rangle$` |
| Outer product | `$\ketbra{\psi}{\phi}$` | `$\lvert \psi \rangle\langle \phi \rvert$` |
| Expectation | `$\expect{A}$` | `$\langle A \rangle$` |
| Commutator | `$\comm{A}{B}$` | `$[A,B]$` |
| Pauli matrices | | `$\sigma_x,\sigma_y,\sigma_z$` |
| Tensor product | | `$A \otimes B$` |
| Hbar | | `$\hbar$` |
| Hamiltonian | | `$\mathcal{H}$` |
