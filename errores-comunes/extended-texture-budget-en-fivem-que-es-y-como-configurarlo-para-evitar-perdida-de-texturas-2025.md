---
description: >-
  ¿Carreteras invisibles o edificios borrosos en FiveM? Aprende a configurar el
  "Extended Texture Budget" correctamente. Guía completa para optimizar tu VRAM
  y eliminar la pérdida de texturas sin lag.
---

# 🛣️ Extended Texture Budget en FiveM: Qué es y Cómo Configurarlo para Evitar Pérdida de Texturas (2025)

## Extended Texture Budget en FiveM: La clave para un juego fluido <a href="#extended-texture-budget-en-fivem-la-clave-para-un" id="extended-texture-budget-en-fivem-la-clave-para-un"></a>

Si eres un jugador habitual de servidores de roleplay, seguramente te has enfrentado al problema más molesto de FiveM: ir conduciendo a toda velocidad y ver cómo la carretera desaparece bajo tus ruedas, o entrar en una tienda y que las paredes sean invisibles. Este fenómeno, conocido como **"Texture Loss"** (pérdida de texturas), no siempre es culpa de tu tarjeta gráfica ni del servidor. A menudo, es una simple cuestión de configuración.

La solución se esconde en una barra deslizante llamada **Extended Texture Budget** (Presupuesto de Texturas Extendido). En este artículo, desglosaremos qué es exactamente, por qué es vital para servidores con mods y cómo ajustarlo perfectamente según tu PC.

### ¿Qué es el Extended Texture Budget? <a href="#qu-es-el-extended-texture-budget" id="qu-es-el-extended-texture-budget"></a>

Para entender esta configuración, primero debemos entender cómo funciona GTA V. El juego base tiene un límite de memoria de video (VRAM) asignado para cargar texturas. Sin embargo, FiveM no es el juego base; es una plataforma modificada donde los servidores añaden cientos de coches personalizados, ropa real y mapeados complejos.

El **Extended Texture Budget** es una herramienta que permite a FiveM "saltarse" el límite original de memoria de GTA V. Básicamente, le dice al motor del juego: _"Oye, reserva un espacio extra de mi tarjeta gráfica exclusivamente para cargar los mods de este servidor"_.

Sin esta reserva adicional, el juego intenta cargar los archivos personalizados (coches, ropa, mapas) usando el presupuesto original, que se queda corto rápidamente, provocando que el motor deje de dibujar el suelo o los edificios para no colapsar.

### Cómo configurar el Extended Texture Budget paso a paso <a href="#cmo-configurar-el-extended-texture-budget-paso-a-p" id="cmo-configurar-el-extended-texture-budget-paso-a-p"></a>

Ajustar esta opción es sencillo, pero encontrar el punto exacto requiere atención. Sigue estos pasos para acceder a la configuración:

1. Abre FiveM y conéctate a tu servidor favorito (o hazlo desde el menú principal).
2. Presiona `ESC` para abrir el menú de pausa.
3. Ve a la pestaña **Settings** (Configuración) y luego a **Graphics** (Gráficos).
4. Desplázate hacia abajo hasta encontrar la barra llamada **Extended Texture Budget**.

Verás una barra deslizante que puedes aumentar o disminuir. Justo encima, verás una barra de **Video Memory** que muestra cuánta VRAM de tu tarjeta gráfica se está consumiendo en tiempo real.

### El error más común: ¿Más es siempre mejor? <a href="#el-error-ms-comn-ms-es-siempre-mejor" id="el-error-ms-comn-ms-es-siempre-mejor"></a>

Aquí es donde el 90% de los jugadores se equivoca. Existe el mito de que **"subir la barra al máximo hará que se vea mejor"**. Esto es **falso** y puede ser contraproducente.

Si subes el Extended Texture Budget al máximo, obligas a tu gráfica a reservar casi toda su memoria para texturas, dejando muy poco espacio para otros procesos esenciales como el cálculo de sombras, iluminación o físicas. Esto provoca:

* **Stuttering:** Pequeños tirones o congelaciones de pantalla.
* **Lag de entrada:** Retraso entre que mueves el ratón y la cámara responde.
* **Crasheos:** El juego se cierra porque la gráfica se queda sin memoria operativa.

### La regla de oro para la configuración

El objetivo es encontrar el equilibrio. Sigue esta guía según tu tarjeta gráfica:

* **Tarjetas de 4GB VRAM:** Aumenta la barra solo unos pocos puntos (aprox. 20-30% de la barra). Es vital que bajes la "Calidad de Texturas" del juego base a "Normal" para liberar espacio.
* **Tarjetas de 6GB - 8GB VRAM:** Puedes subir la barra hasta la mitad (aprox. 40-50%). Esto suele ser suficiente para la mayoría de servidores optimizados.
* **Tarjetas de +10GB VRAM:** Puedes permitirte subir la barra más (60-75%), pero rara vez es necesario llegar al máximo a menos que juegues en 4K con gráficos ultra realistas (NVE, QuantV).

**Consejo Pro:** Mira la barra de consumo de memoria arriba del menú. Asegúrate de que, al subir el presupuesto, la barra de consumo total **nunca se ponga en rojo**. Lo ideal es mantenerla en verde o amarillo bajo.

### Síntomas de una mala configuración <a href="#sntomas-de-una-mala-configuracin" id="sntomas-de-una-mala-configuracin"></a>

Para diagnosticar si tu configuración actual es la culpable de tus problemas, fíjate en estas señales:

### Presupuesto demasiado BAJO

* El suelo desaparece (limbo gris).
* Los edificios parpadean o son invisibles.
* La ropa de otros jugadores se ve borrosa ("ropa de plastilina").

### Presupuesto demasiado ALTO

* El juego da tirones fuertes al conducir rápido.
* Caídas repentinas de FPS en zonas con mucha gente.
* Cierres inesperados con errores de "Out of Memory".

### Conclusión <a href="#conclusin" id="conclusin"></a>

El **Extended Texture Budget** es tu mejor aliado para estabilizar FiveM, pero debe usarse con inteligencia. No se trata de fuerza bruta, sino de gestión de recursos.

Si sufres de pérdida de texturas, no corras a comprar una gráfica nueva. Entra en los ajustes, baja la calidad de las texturas base a "Normal" y sube progresivamente el presupuesto extendido hasta que el suelo deje de desaparecer. Con este ajuste fino, disfrutarás de una experiencia de roleplay inmersiva y sin interrupciones visuales.
