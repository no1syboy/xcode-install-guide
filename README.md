# xcode-install-guide

### MacOS Sierra

### Xcode esta instalado?

1. Utilisaremos la applicacion `Terminal` o `iTerm` para encontrarlas es sensillo con ayuda de **Spotlight** con el shortcut: `command + space`:


![](src/gif/open-iterm.gif)

Verificar si tenemos la version completa de Xcode package instalada:

```
$ xcode-select -p
```

Si vemos la siguiente linea en terminal:
```
/Applications/Xcode.app/Contents/Developer
```
![](src/img/xcode-select.png?raw=true)

Ya tenemos en code instalado. Si no es el caso lo intalamos ejecutandio lo siguiente:
```
$ xcode-select --install
```
