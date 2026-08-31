# DynamicShop3 - Fix de compatibilidad para 1.21.3+ / Paper 26.x

Este repositorio es una copia del proyecto original
[7sat/DynamicShop3](https://github.com/7sat/DynamicShop3) (marcado como
"[Discontinued]" en SpigotMC), con el fix de compatibilidad propuesto en el
[Pull Request #100](https://github.com/7sat/DynamicShop3/pull/100) por
[Telesphoreo](https://github.com/Telesphoreo/DynamicShop3) aplicado, ya que
el autor original nunca lo fusionó.

## Por qué existe este repo

El plugin dejó de recibir actualizaciones desde octubre de 2024. A partir de
Minecraft 1.21.3, cambios en la API de eventos de inventario de Spigot/Paper
rompieron parte de la GUI del plugin (crasheaba con `NullPointerException`
al hacer click en ciertas pantallas). El PR #100 corrige esto en 5 archivos,
pero nunca se fusionó al repositorio principal ni se publicó una nueva
versión en SpigotMC.

## Créditos

- Plugin original: [eftc91c / 7sat](https://github.com/7sat/DynamicShop3)
- Fix de compatibilidad: [Telesphoreo](https://github.com/Telesphoreo/DynamicShop3)

Todo el crédito del plugin en sí es de sus autores originales. Este repo
solo combina ambas cosas y automatiza la compilación.

## Cómo descargar el .jar compilado

1. Ve a la pestaña **Actions** de este repositorio.
2. Abre el run más reciente (✅ verde).
3. Descarga el artefacto **DynamicShop3-plugin**.
4. Extrae el `.jar` y súbelo a tu carpeta `plugins/`.

## Requisitos

Este plugin requiere [Vault](https://www.spigotmc.org/resources/vault.34315/)
y un plugin de economía compatible.
