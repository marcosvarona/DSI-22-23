# PlantUML

Herramienta que permite generar diagramas usando una descripción de texto simple, con un formato sencillo, directamente legible y encargándose el servicio de generar los gráficos.

> PlantUML utiliza algoritmos de diseño inteligentes para organizar los elementos de sus diagramas de una manera clara y fácil de entender, ahorrándole el tiempo y el esfuerzo de posicionar y alinear manualmente los elementos individuales.


En esta repo, todos los gráficos están [en su correspondiente carpeta](/out/puml.source/), en formato SVG (que entre otras cosas permite ampliarlos sin perder calidad, sin pixelarse), y su código fuente en la carpeta equivalente [puml.source](/puml.source/)

## Ejemplo

[Imagen](/out/puml.source/empresaEstrategiaPlanificacion2/empresaEstrategiaPlanificacion2.svg)|[Código fuente PlanUML](/puml.source/empresaEstrategiaPlanificacion2.puml)
-|-
|![](/out/puml.source/empresaEstrategiaPlanificacion2/empresaEstrategiaPlanificacion2.svg)|<pre>Estrategia -u- Empresa:> clara<br />Planificación -u- Empresa:> adecuada<br /><br />Estrategia .r.> Planificación: Guía a<br />Planificación ...> Estrategia: Ayuda a que se cumpla<br /><br />hide class circle<br />hide empty member|

## Más información

- [Página de PlanUML](https://plantuml.com/es/)
- [Servicio online demo](https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000)