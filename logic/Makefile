# requires Latex, Pandoc, and the Eisvogel template https://github.com/Wandmalfarbe/pandoc-latex-template

all: presentation1.pdf presentation2.pdf presentation3.pdf template.pdf

presentation1.pdf: presentation1.md
	pandoc presentation1.md --output presentation1.pdf --from markdown --to beamer --template "eisvogel.latex"

presentation2.pdf: presentation2.md
	pandoc presentation2.md --output presentation2.pdf --from markdown --to beamer --template "eisvogel.latex"

presentation3.pdf: presentation3.md
	pandoc presentation3.md --output presentation3.pdf --from markdown --to beamer --template "eisvogel.latex"

template.pdf: template.md
	pandoc template.md -o template.pdf