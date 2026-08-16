# PhysioSentinel AI v15.5.15

## Nueva función: exportación de vídeo del atractor

Se mantiene íntegra la v15.5.14 y se añade en la pestaña 4 la exportación del atractor 3D.

### Exportación
- MP4.
- GIF.
- Uno o varios atractores simultáneos.
- Colores diferenciados por registro.
- La pelota móvil conserva el color de su trayectoria.
- Sincronización 0–100 % cuando los registros tienen distinta longitud.
- Selección de FPS y número de frames.
- Trayectoria completa + punto móvil o trayectoria progresiva.
- Cámara configurable para el archivo: elevación, azimut y zoom.
- Botón de descarga dentro de Streamlit.

### Dependencias añadidas
- matplotlib
- imageio
- imageio-ffmpeg

### Sin cambios fisiológicos
No se modifican RRi, τ, embedding m, D2, Lyapunov, RQA, HRV, entropías,
Control autonómico, XGBoost, calibración ni predicción.
