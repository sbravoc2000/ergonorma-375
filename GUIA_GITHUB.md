# ErgoNorma 375 · versión GitHub

Desarrollado por Sergio Bravo con Astra.

## Publicar en GitHub Pages

En este repositorio, abrir Settings → Pages. En Build and deployment elegir Deploy from a branch. Seleccionar main y /(root), y guardar. La interfaz mostrará el enlace cuando termine la publicación. URL esperada (no confirmada hasta activación): https://sbravoc2000.github.io/ergonorma-375/

## Uso

Abrir index.html localmente o visitar Pages. No requiere instalación, claves ni servidores. Los archivos calculos.js, pro.js y pro.css deben permanecer junto a index.html. No hay dependencias de CDN. La ficha no se guarda al cerrar/recargar; imprimir o copiar antes. La integración con ChatGPT consiste en preparar texto para envío manual, no una API.

## Secciones

- Carga manual, ruido, WBGT, iluminación y tamizaje parcial.
- Práctica guiada de 90 minutos, casos A–D y clave docente visible.
- Extras: fuerza de empuje/tracción, vibración, humedad, velocidad del aire, producto de factores NIOSH y planificación de digitación.
- Ficha de equipo imprimible y preparación de infografía.

## Alcance y fuentes

Base documental: copia suministrada de la Norma Básica de Ergonomía y de Procedimiento de Evaluación de Riesgo Disergonómico, RM 375-2008-TR. No se afirma una verificación de vigencia jurídica integral. Los numerales se indican en cada resultado. No se incluyen límites de agentes químicos ni radiaciones: el anexo remite a otras fuentes.

La dosis usa la ecuación del n. 24, no interpolación de la tabla redondeada. LAeq se calcula por promedio energético de los tramos ingresados. Fuerza: la tabla que dice kg se interpreta como kgf; 1 kgf = 9,80665 N. Vibración: se adopta la banda más protectora en 1, 2 y 4 horas por solapamiento de intervalos; cuerpo entero solo compara 8 horas. La velocidad de aire es comparación descriptiva sin inventar tolerancias. NIOSH no incluye tablas de factores: deben ser determinados con el método completo. Los colores no son escalas oficiales ni certifican cumplimiento integral.

## Verificación

Con Node instalado: `node test.cjs`. Se prueban valores modelo, límites, campos vacíos y combinaciones sin valor tabulado. No se realizó prueba automatizada en navegador. Revisar el funcionamiento en los celulares del aula antes de la sesión.
