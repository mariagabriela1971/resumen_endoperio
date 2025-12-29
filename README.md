# Resumen de Endoperio

Este es mi primer resumen en LaTeX de endoperio.

## Compilacion

En el directorio `resumen_endoperio` ejecutar

```sh
lualatex main.tex
biber main
lualatex main.tex
lualatex main.tex
```

Para análisis ortográfico y gramatical usar el comando 
```sh
textidote --check es --output html *.tex > report.html
firefox report.html
```

Cuando ya se ha ejecutado y revisado hay que eliminar el reporte antiguo
```sh
rm report.html
```