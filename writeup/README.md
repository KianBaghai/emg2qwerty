# ECE C147/247 Final Project Writeup

## Compiling the writeup

1. **Get the NeurIPS 2024 style file** (required):
   - Download https://media.neurips.cc/Conferences/NeurIPS2024/Styles.zip
   - Extract `neurips_2024.sty` into this directory (same folder as `writeup.tex`), or into your LaTeX path.

2. **Compile** (from this directory):
   ```bash
   pdflatex writeup.tex
   pdflatex writeup.tex
   ```
   Or use your preferred LaTeX editor.

## Before submitting

- Replace `[Author names and UCLA emails]` and `\{emails\}` in the author block with your team’s names and emails.
- Fill in the **Abstract** with your actual main result and any extra experiments (data fraction, channels, etc.).
- Replace placeholder CER values in **Table 1** (and add any extra tables/figures) with your validation and test CER for:
  - TDS CNN (baseline)
  - CNN + LSTM
  - CNN + BiLSTM (if you ran it)
  - Transformer
- Complete the **Discussion** with your observations and interpretations (why some architectures did better or worse).
- Ensure the writeup does not exceed **7 pages** (references excluded), per project guidelines.

## Page limit

Baseline projects: max 7 pages (references not counted). Use the `[final]` option in `\usepackage[final]{neurips_2024}` to remove line numbers for submission.
