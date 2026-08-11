# Andalucía Fire Updates

Canal público de actualizaciones de Andalucía Fire.

Para publicar una actualización:

1. Incrementa `versionCode` y `versionName` en la aplicación.
2. Genera la APK utilizando siempre la misma firma.
3. Añade una copia con versión, por ejemplo `AndaluciaFire-0.2.3.apk`.
4. Sustituye también `AndaluciaFire.apk` por la última versión.
5. Actualiza `version`, `downloadUrl`, `notes` y `required` en `update.json`.
6. Publica primero la APK y después el manifiesto si usas commits separados.

`required: true` impide omitir la actualización. Normalmente debe mantenerse en
`false` para que una caída de GitHub no afecte al uso del mapa.

No añadas a este repositorio código fuente, claves API ni claves de firma.
