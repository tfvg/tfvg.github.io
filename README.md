# tfvg.github.io
Il sito è contenuto qui. Si può usare Markdown o Html o un generatore di pagine come jekyll.

CNAME contiene il nome del dominio, va cambiato dai settings, non cancellare.
Ogni pochissimi minuti il bot ripubblica le pagine, quindi le modifiche non sono istantanee per i visitatori.

Esempio manuale con diff, modifica wrong.txt in fixed.txt:

diff -u wrong.txt fixed.txt --label orig --label fixed > patch.txt

edit patch.txt

patch -b -i patch.txt (file to patch)
