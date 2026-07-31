# Easytier para Unraid

Un plugin que proporciona easytier (consulta https://github.com/EasyTier/EasyTier) en unraid para que puedas conectarte a la VPN antes de que el array se inicie.

Aún está en desarrollo y es mi primer plugin para unraid.

# Uso

## Inicio y Parada

```
/etc/rc.d/rc.easytier start
/etc/rc.d/rc.easytier stop
/etc/rc.d/rc.easytier restart
```

## Configuración

No tiene una interfaz gráfica (GUI), y simplemente utiliza un archivo de configuración para controlar easytier.

Puedes editar el archivo de configuración en:

```
/boot/config/plugins/easytier/config.toml
```

Después de completar la configuración, debes reiniciar easytier mediante rc como se indica en el capítulo anterior.

## CLI

Este plugin proporciona los comandos "easytier-core" y "easytier-cli", para más detalles consulta la documentación de easytier (https://www.easytier.top/guide/introduction.html)
