# latex-preambles
Customized and categorized preamble files for LaTeX documents

## LaTeX
To add preambles to your project:
- Download the files
- Use `\input` to add files to the document

### Example
Assuming `mathematics.tex` is located in 'preambles/mathematics.tex' folder with respect to main document `main.tex`, A minimal working example is: 

content of `main.tex`
```
\documentclass{minimal}
\input{preambles/mathematics}

\begin{document}
    $$A := \setdef{\x = (x_1,\,x_2) \in \RR^2}{\| \x\| = 1}$$
\end{document}
```

## Overleaf
You can include these preambles in your project via:
- Project > New File > From External URL

### URLs
- `mathematics.tex`: https://raw.githubusercontent.com/siamakfaal/latex-preambles/main/mathematics.tex
- `graphics.tex`: https://raw.githubusercontent.com/siamakfaal/latex-preambles/main/graphics.tex
