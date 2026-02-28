# new bspwm-parrot
## Configuración de Entorno para Parrot OS con bspwm

Este script de Bash automatiza la configuración de un entorno limpio y profesional para Parrot OS utilizando el gestor de ventanas bspwm.

### Descripción
El script realiza las siguientes acciones:

- Actualiza el sistema y lo mejora con parrot-upgrade.
- Instala las dependencias necesarias para el entorno bspwm, Polybar y Picom.
- Descarga y configura diversos repositorios necesarios.
- Instala paquetes adicionales y aplicaciones útiles para el pentesting.
- Configura temas y plugins para una experiencia de usuario mejorada.
- Limpia archivos temporales y realiza un reinicio opcional del sistema.

### Instalaciones
- kitty v0.35.1
- Neovim v0.10.0
- Visual Studio Code v1.90.0
- bspwm v0.9.10
- sxhkd v0.6.2
- polybar 3.7.1-11
- python2 v2.7.18
- python3 v3.11.2
- pip2 20.3.4
- Picom vgit-c4107
- zsh
- feh
- rofi
- imagemagick
- seclists
- powerlevel10k
- pwntools
- i3lock-fancy
- fzf

### Requisitos
- Parrot OS
- Acceso a internet
- Permisos de superusuario

### Uso
Para clonar este repositorio debe seguir esta instrucción: navegar al directorio del script luego ejecutarla.

```bash
git clone https://github.com/JulkTriad/new-bspwm-parrot.git
cd new-bspwm-parrot
```

Ejecute el script:

```bash
./install.sh
```
> Notas: Estar seguro de ejecutar el script como un usuario normal, no como root.

###
El script comentará la primera línea del archivo /etc/apt/sources.list si el archivo tiene solo dos líneas para evitar errores de actualización.
Durante la ejecución, el script le pedirá que reinicie el sistema al final del proceso de instalación.

## Entorno

```
Ya se ira subiendo las imagenes de como esta quedando el entorno, aun se sigue mejorando.
```

## Contribuciones

Si te apasiona la ciberseguridad, únete para seguir mejorando el entorno de hacking con bspwm.

Cómo puedes ayudar:

- Reporta bugs
- Propón mejoras
- Mejora la documentación
