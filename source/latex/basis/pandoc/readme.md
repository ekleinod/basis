# Versuche mit Pandoc

Scheitern derzeit daran, dass `pandoc` auf Ubuntu nicht aktuell ist, insbesondere keine Metadaten auswerten kann.
Diese wäre für eigene Templates aber wichtig.

Weiterhin ist mir unklar, wie man Templates am besten auf Win/Linux einsetzt, ohne allzusehr beim Aufruf Verzeichnisse setzen zu müssen.
LaTeX-Verzeichnisse kann man wohl eher nicht auswerten.

Aufruf derzeit:

	pandoc --to=latex --self-contained -o generiert.tex --template=template_test.latex -s pandoc_dokument.pandoc
	pandoc --to=html5 --self-contained -o generiert.html -s pandoc_dokument.pandoc

