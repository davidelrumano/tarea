# CrystalDiskMark - Mini Guía

## Introducción
CrystalDiskMark es una herramienta de benchmarking para discos duros y SSD que mide la velocidad de lectura y escritura secuencial y aleatoria. Es útil para evaluar el rendimiento del almacenamiento en diferentes escenarios de uso.

![CrystalDiskMark Logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStpW0m1bHiqC-erzOrYDmAIXZOqa0r4WrOjA&s)

---

## Descarga e Instalación
1. Visita el sitio oficial de **CrystalDiskMark** en [https://crystalmark.info/en/software/crystaldiskmark/](https://crystalmark.info/en/software/crystaldiskmark/).
2. Descarga la versión adecuada (instalable o portable).
3. Si elegiste la versión instalable:
   - Ejecuta el instalador y sigue las instrucciones.
   - Acepta los términos y condiciones.
   - Completa la instalación y abre el programa.
4. Si elegiste la versión portable, simplemente extrae el archivo y ejecuta **DiskMark.exe**.


---

## Uso Básico
1. Abre **CrystalDiskMark**.
2. Selecciona:
   - **Unidad de disco** que deseas probar.
   - **Número de pruebas** (por defecto 5, puede reducirse para pruebas rápidas).
   - **Tamaño de archivo de prueba** (generalmente 1GB es suficiente).
3. Haz clic en **All** para iniciar todas las pruebas.
4. Una vez finalizada la prueba, observa los resultados:
   - **SEQ1M Q8T1**: Velocidad secuencial con múltiples hilos y profundidad de cola.
   - **SEQ1M Q1T1**: Velocidad secuencial en un solo hilo.
   - **RND4K Q32T16**: Lectura y escritura aleatoria 4K con hilos múltiples.
   - **RND4K Q1T1**: Lectura y escritura aleatoria 4K con un solo hilo.

![CrystalDiskMark Benchmark](https://davemateer.com/assets/2020-04-19/3.jpg)

### Interpretación de resultados:
- Velocidades altas indican buen rendimiento del almacenamiento.
- Comparar con especificaciones del fabricante ayuda a detectar posibles fallos.

---
