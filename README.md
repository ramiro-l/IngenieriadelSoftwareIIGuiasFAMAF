# Ingeniería del Software II - Guías FAMAF

## Estructura

```text
guia{n}/
    """ Cada guía tiene el enunciado (pdf), mi solución (lts) y a veces imágenes. """
    guia{n}.pdf
	index.lts
	images/
teórico/
    """ Algunos ejemplo que se dieron en el teórico. """
    *.lts
utilidades/
    """ Algunos ejemplo que son útiles para resolver los ejercicios. """
    *.lts
```

## LTSA

URL oficial:

https://www.doc.ic.ac.uk/~jnm/book/ltsa/download.html

Instalación en Linux:

```bash
sudo apt update
sudo apt install default-jre unzip
wget https://www.doc.ic.ac.uk/~jnm/book/ltsa/ltsatool.zip
unzip ltsatool.zip
cd ltsatool
java -Dswing.defaultlaf=javax.swing.plaf.metal.MetalLookAndFeel -Dswing.systemlaf=javax.swing.plaf.metal.MetalLookAndFeel -jar ltsa.jar
```
