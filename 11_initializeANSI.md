# Codigo 11: AnsiColor

## ¿Que hace?
Implementar comando para visualizar la salida de texto modificada en colores

### **Anotaciones**
Al ejecutarlo no funciona, ya que he modificado mi terminal en archlinux para que sea mas util, estas utilidades no me permiten mostrar texto en algun otro color

```bash
#!/bin/bash

initializeANSI()
{
    esc='\033'

    #Foerground
    blackf="${esc}[30m";    redf="${esc}[31m";  greenf="${esc}[32m"
    yellowf="${esc}[33m";   bluef="${esc}[34m"; purplef="${esc}[35m"
    cyanf="${esc}[36m";     whitef="${esc}[37m"

    #Background
    blackb=="${esc}[40m";   redb="${esc}[41m";  greenb="${esc}[42m"
    yellowb="${esc}[43m";   blueb="${esc}[44m"; purpleb=="${esc}[45m"|
    cyanb="${esc}[46m";     whiteb="${esc}[47m"

    #Styles
    boldon="${esc}[1m";     boldoff="${esc}[22m"
    italicson="${esc}[3m";  italicsoff="${esc}[23m"
    ulon="${esc}[4m";       uloff="${esc}[24m"
    invon="${esc}[7m";      invoff="${esc}[27m"

    reset="${esc}[0m"
}
initializeANSI

```
**[Anterior](https://github.com/SPM-UPVictoria/test-git-itsHaydo)**
