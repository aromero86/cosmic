# Configuración de PopOS 24 / Cosmic
Detalles, configuraciones y pasos a seguir para dejar `PopOS 24 / Cosmic` como un pincel

### Input remapper
La instalación desde el store de `input-remapper` funciona pero al ejecutarlo no hace nada. Para echarlo a andar, hay que hacer:

```
sudo apt install python3-cairo
```

Hecho esto, reemplazamos las combinaciones que queremos.

### Hacer Chrome por defecto
Para hacer esto, hay que:

``` 
# Deja la app default
xdg-settings set default-web-browser google-chrome.desktop

# Comprueba que se aplicó el cambio
xdg-settings get default-web-browser
``` 