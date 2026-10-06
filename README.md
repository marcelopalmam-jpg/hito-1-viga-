# Hito 1 - Viga simplemente apoyada: carga-deflexión

**Autor:** Marcelo Palma Meléndez

**Trabajo del curso:** Herramientas computacionales 2

## Objetivo 
Establecer la comparación de una deflexión medida en el centro de una viga simplemente apoyada con la deflexión teórica de Euler-Bernoulli, y poder escribir los resultados en una nota técnica.

## Datos de partida
La viga tiene una longitud de 4 m entre apoyos, tiene una sección rectangular de ancho b = 0,2 m y altura h = 0,4 m. El módulo de elasticidad para este ejercicio es de 25 GPa. La viga tiene una carga puntual centrada. Los datos de deflexión son sintéticos y se entregan exclusivamente con fines docentes.

## Contenido del repositorio 
- data: archivos de entrada originales, sin modificar.
- analysis: planilla con todos los cálculos (pendiente).
- figures: figura de carga-deflexión de la viga (pendiente).
- report: nota técnica en LaTeX (pendiente).
- USO_IA.md: declaración del uso de la inteligencia artifical.

## Reproducción del análisis
1. Descargar o clonar este repositorio.
2. Abrir `analysis/analisis_viga.xlsx` en Excel.
3. En la hoja `Parametros` están los datos de la viga (b,h,L,E) con las unidades convertidas y las fórmulas correspondientes.
4. Los datos originales sin modificar están en `data/`.
5. La figura carga-deflexión está en `figures/carga_deflexion.png` y también dentro de la planilla Excel.
6. Para recompilar la nota técnica, abrir `report/main.tex` en Overleaf y subir junto con él `report/referencias.bib`, `figures/carga_deflexion.png` y `data/esquema_viga.png`.
Las verificaciones adicionales están en la hoja de cálculo.

## Versión entregada
- Commit final entregado:
- Nota técnica: `report/nota_tecnica_hito1.pdf`


