# Validaciones funcionales de la máquina virtual
En esta sección se documentan las comprobaciones que validan el funcionamiento correcto del sistema operativo invitado, los recursos asignados y la ejecución fluida en VirtualBox.

## Validación del arranque y entorno gráfico
- Se verificó que la VM inicia correctamente sin errores.
- Se accedió al entorno gráfico de Linux Mint XFCE.

### Capturas de pantalla
- [linuxmint_inicio.png](./linuxmint_inicio.png) -> Entorno gráfico iniciado correctamente.
- [linuxmint_menu.png](./linuxmint_menu.png) -> Acceso al menú de aplicaciones.
  
## Verificación del sistema operativo y recursos
- Se utilizó `neofetch` para obtener detalles del sistema instalado.
- Instalación de `htop`
- Se comprobó el uso de CPU y memoria con `htop`.

### Capturas de pantalla

## Observaciones
La máquina virtual opera correctamente y responde bien con los recursos asignados (2 GB RAM, 2 núcleos CPU).
