# Collection of `markdown -> Beamer` Templates for Pandoc

## compile

### manually from markdown file
```bash
pandoc -t beamer --template themes/ponde.tex -s -o sample/sample.tex sample/sample.md
$TEX sample/sample.tex
```

### a workflow to compile from ipynb

```bash
./release --notebook /path/to/ipynb
```

## samples

see `sample/*.pdf`

## templates list

- Ponde
- Beamer-Theme-Execushares
    - The original style file is [FuzzyWuzzie/Beamer-Theme-Execushares](https://github.com/FuzzyWuzzie/Beamer-Theme-Execushares).
- Ponde2
    - color scheme is Execushares (partially)
    - not dependent as possible as on tikz
- Pondering
- novel
- Beamer-Theme-Metropolis

# LICENSE

MIT LICENSE

