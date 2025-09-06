# ShowCheck
ShowCheck informa sobre la performance de sesiones de Ableton Live. Pensado para ingenieros de playback: registra uso de CPU, memoria, disco, actividad de red y batería. 
ShowCheck reports on the performance of Ableton Live sessions. Built for playback engineers: records CPU, memory, disk, network activity, and battery usage.


# 🌟 Funciones
## Monitoreo en tiempo real
* Uso de CPU: CPU total del sistema y monitoreo específico del proceso de Ableton Live
* Consumo de memoria: Seguimiento de uso de RAM con alertas por umbrales críticos
* E/S de disco: Monitoreo de actividad de lectura/escritura y uso de almacenamiento
* Actividad de red: Monitoreo de tráfico de red
* Monitoreo de temperatura: Seguimiento de temperatura de CPU (cuando esté disponible)
* Gestión de batería: Análisis de consumo energético y descarga de batería
* Alertas de rendimiento: Notificaciones por picos y condiciones críticas

## Grabación automática de la sesión
* Integración OSC: Inicia/detiene el monitoreo automáticamente al presionar PLAY/STOP en Ableton Live
* Exportación inteligente: Genera informes completos al finalizar la sesión
* Múltiples formatos: Exporta datos como CSV, gráficos PNG, estadísticas JSON e informes HTML interactivos

## Informes interactivos
* Tema oscuro/claro: Informes HTML responsivos con cambio de tema
* Gráficos con zoom: Visualizaciones de series temporales con paneo y zoom
* Métricas completas: Tablero multipanel con todos los parámetros monitoreados
* Resumen de performance: Estadísticas clave

# 📋 Requisitos
## Requisitos del sistema
* Python 3.7+
* macOS (Corriendo en Macbook M1/M2/M3/M4)
* Ableton Live 11 o 12

# 🚀 Instalación
* Descarga el ShowCheck.app (macOS) más reciente desde Releases
* Arrastra ShowCheck.app a Aplicaciones antes de abrirla
* Abrir la carpeta Aplicaciones.
* Haz clic derecho en ShowCheck.app → Abrir.
* macOS mostrará "no se puede verificar el desarrollador" → Haz clic en Abrir.
* Si el botón "Abrir" no aparece:
  * Ve a "Ajustes del Sistema" → "Privacidad y seguridad".
  * Busca "Se bloqueó ShowCheck" en la parte inferior → Haz clic en "Abrir de todos modos" → Abrir.
  (Este paso se hace una sola vez. Luego podés abrirla normalmente (doble click))
* Instala el dispositivo Max for Live
* Descarga ShowCheck.amxd desde Releases
* En Ableton Live, arrastra el dispositivo a una pista MIDI
* El dispositivo enviará mensajes OSC a ShowCheck automáticamente cuando des play/stop

# 🎯 Uso
* Inicia ShowCheck
* Carga el dispositivo M4L en tu set de Ableton Live
* Presiona PLAY en Ableton: el monitoreo comienza automáticamente
* Presiona STOP en Ableton: se genera el informe de sesión automáticamente

# Archivos de salida
* Cuando finaliza una sesión, ShowCheck genera automáticamente:
 * session_YYYYMMDD_HHMMSS.csv - Datos crudos de monitoreo
 * session_YYYYMMDD_HHMMSS.png - Gráficos de rendimiento
 * session_YYYYMMDD_HHMMSS_stats.json - Resumen estadístico
 * session_YYYYMMDD_HHMMSS_report.html - Informe interactivo
* Los archivos se guardan en tu Escritorio por defecto.

# 🙏 Créditos
@patopretti
Contribución cyborg: 60% humano y 40% automatizado (aprox.) en co-agencia pacífica

# 📈 Historial de versiones
## v0.1 (Actual)
 * Lanzamiento inicial
 * Monitoreo en tiempo real con integración OSC
 * Informes HTML interactivos con temas claro/oscuro
 * Métricas completas del sistema
 * Detección automática de sesiones
 * Sistema de alertas de rendimiento
 * Monitoreo de batería y temperatura
 * Exportación en múltiples formatos (CSV, PNG, JSON, HTML)





