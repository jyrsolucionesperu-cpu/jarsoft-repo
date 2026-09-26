# JARSOFT Repo

Repositorio oficial de paquetes del ecosistema JARSOFT OS.

## Uso

Añade este repositorio a tu \`/etc/pacman.conf\`:

\`\`\`
[jarsoft]
SigLevel = Optional TrustAll
Server = https://raw.githubusercontent.com/jyrsolucionesperu-cpu/jarsoft-repo/main
\`\`\`

Luego sincroniza:

\`\`\`bash
sudo pacman -Sy
\`\`\`

## Paquetes

Todos los paquetes del ecosistema JARSOFT OS:

- JARSOFT Files (gestor de archivos)
- JARCONSOLE (consola guiada)
- JARSOFT Music, Video, PDF, Notepad, Calculator
- JARSOFT Image, Capture Image
- JARSOFT Installer, Security, Quickly, Run
- JARGAME Gato, 2-Iguales
- Y todos los módulos del sistema JARSOFT

## Mantenimiento

El repositorio se regenera con:

\`\`\`bash
repo-add jarsoft.db.tar.gz *.pkg.tar.zst
\`\`\`
