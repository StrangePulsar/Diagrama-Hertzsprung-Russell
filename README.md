# Diagrama de Hertzsprung-Russell

Este proyecto explora la clasificación espectral de las estrellas y su representación en el diagrama de Hertzsprung-Russell (HR). Utiliza datos de los catálogos astronómicos HIPPARCOS y GAIA para realizar análisis visuales que permiten comprender mejor las propiedades físicas de las estrellas y su evolución.

## Contexto

La clasificación espectral y los diagramas HR son herramientas fundamentales en la astrofísica:

- **Clasificación espectral**: Ordena las estrellas según sus características espectrales, como las líneas de absorción en sus espectros. Esta clasificación está vinculada con la temperatura de la fotosfera estelar.
  - Sistema Morgan-Keenan (MK): Clasifica las estrellas en tipos O, B, A, F, G, K y M (de más calientes a más frías).

- **Diagrama Hertzsprung-Russell**: Relaciona la luminosidad o magnitud absoluta de las estrellas con su temperatura o clasificación espectral, revelando su etapa evolutiva.

- **Evolución estelar**: Describe los cambios estructurales y de apariencia de las estrellas a lo largo de su vida, desde la secuencia principal hasta su destino final (enanas blancas, estrellas de neutrones o agujeros negros).

## Contenido del Notebook

El notebook incluye:

1. **Introducción a la clasificación espectral**: Explicación del sistema Morgan-Keenan y sus aplicaciones en astrofísica.
2. **Descripción del diagrama HR**: Contexto histórico y relevancia para el estudio de la evolución estelar.
3. **Análisis con datos del catálogo HIPPARCOS**:
   - Construcción de un diagrama HR para estrellas cercanas.
   - Exploración de relaciones entre magnitudes absolutas e índices de color.
4. **Análisis con datos del catálogo GAIA**:
   - Enfoque en estrellas con metalicidades similares a la del Sol.
5. **Visualizaciones**: Gráficos interactivos y estáticos que ilustran los resultados.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **Bibliotecas**:
  - `pandas` para manipulación de datos.
  - `matplotlib` y `seaborn` para visualización.
  - `numpy` para operaciones numéricas.
- **Datos**: Catálogos HIPPARCOS y GAIA.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/diagrama-hr.git
   ```

2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

3. Abre el notebook:
   ```bash
   jupyter notebook Diagrama\ de\ Hertzsprung-Russell.ipynb
   ```

4. Ejecuta las celdas para replicar el análisis.

## Resultados Esperados

- Un diagrama HR que muestra las relaciones fundamentales entre luminosidad y temperatura.
- Identificación de patrones en diferentes etapas evolutivas de las estrellas.
- Comprensión visual de cómo las propiedades estelares cambian con su composición y evolución.

## Referencias

- Catálogo HIPPARCOS: [Sitio oficial](https://www.cosmos.esa.int/web/hipparcos)
- Catálogo GAIA: [Sitio oficial](https://www.cosmos.esa.int/web/gaia)
- Hertzsprung-Russell Diagram: [Wikipedia](https://en.wikipedia.org/wiki/Hertzsprung%E2%80%93Russell_diagram)

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

