default: 

html:
	asciidoctor -r asciidoctor-multipage -b multipage_html5 -a stylesheet=style.css index.adoc -D html

pdf: 
	asciidoctor -r asciidoctor-pdf -b pdf index.adoc

graphviz-diagrams:
	mkdir -p images/diagrams/
	dot -Tpng graphviz-diagrams/drone-custodian-web-architecture.gv -o images/diagrams/drone-custodian-web-architecture.png -Nfontname=helvetica -Nlabelloc=b -Nlabeldistance=200 -Efontname=helvetica -Elabelfontsize=5

.PHONY: default html 

