# MemTest86 - Mini Guía

## Introducción
MemTest86 es una herramienta de diagnóstico de memoria RAM que ayuda a detectar errores en los módulos de memoria. Se ejecuta desde un medio de arranque y es útil para identificar fallos de hardware.

![MemTest86 Descarga](https://www.memtest86.com/img/download.png)

---

## Descarga e Instalación
1. Visita el sitio oficial de **MemTest86** en [https://www.memtest86.com/](https://www.memtest86.com/).
2. Descarga la versión gratuita o de pago según tus necesidades.
3. Crea un medio de arranque:
   - Si usas Windows, ejecuta el instalador para USB y sigue las instrucciones.
   - Si usas Linux o macOS, usa `dd` para copiar la imagen al USB.
4. Reinicia tu PC y arranca desde el USB.



---

## Uso Básico
1. Arranca tu sistema desde el USB con MemTest86.
2. Automáticamente, comenzará el análisis de la memoria RAM.
3. Espera a que finalice el primer pase (puede tardar varias horas dependiendo de la RAM instalada).
4. Observa los resultados:
   - **Errores en rojo** indican fallos en la RAM.
   - **Sin errores** significa que la memoria es estable.

![MemTest86 Prueba](https://preview.redd.it/memtest86-results-bad-cpu-v0-7i2sz74ahaqb1.jpg?width=640&crop=smart&auto=webp&s=2e0036cc47de97c905759f17806153ee3c171964)

### Interpretación de resultados:
- Si se detectan errores, prueba módulos individuales para identificar el defectuoso.
- Si no hay errores tras múltiples pasadas, la RAM está en buen estado.

---
