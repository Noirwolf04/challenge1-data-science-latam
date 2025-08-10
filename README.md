# Challenge 1 Data Science Latam - AluraStore

Análisis exhaustivo de datos de ventas de cuatro tiendas de AluraStore para determinar la mejor oportunidad de inversión.

## Objetivo del Proyecto

Analizar el desempeño de cuatro tiendas de AluraStore Latam para recomendar cuál representa la mejor oportunidad de inversión para el Sr. Juan, considerando factores como facturación, satisfacción del cliente, popularidad de productos y eficiencia operacional.

## Análisis Realizados

El proyecto aborda **5 dimensiones clave** de análisis:

### 1. Facturación Total
- Análisis de ingresos por tienda
- Identificación de la tienda líder en ventas
- Comparación de diferencias porcentuales

### 2. Popularidad de Categorías
- Análisis de categorías más vendidas por tienda
- Identificación de patrones de consumo
- Comparación cross-tienda de preferencias

### 3. Calificación Promedio
- Evaluación de satisfacción del cliente
- Análisis de distribución de calificaciones
- Ranking de tiendas por satisfacción

### 4. Productos Estrella y Rezagados
- Identificación de productos más vendidos
- Análisis de productos con bajo rendimiento
- Oportunidades de mejora por tienda

### 5. Costos de Envío
- Análisis de eficiencia logística
- Comparación de costos operacionales
- Identificación de oportunidades de optimización

## Metodología

1. **Preparación de Datos**: Carga y combinación de datasets de 4 tiendas
2. **Análisis Exploratorio**: Investigación de estructura y calidad de datos
3. **Análisis Cuantitativo**: Cálculos estadísticos por dimensión
4. **Visualización**: Gráficos interactivos para cada análisis
5. **Síntesis**: Informe ejecutivo con recomendación fundamentada

## Resultados Principales

### Recomendación: **TIENDA_3** - "La Inversión Inteligente"

**Justificación:**
- **Mejor satisfacción del cliente**: 4.05/5
- **Facturación sólida**: $1,098M COP
- **Costos competitivos**: $24,806 COP promedio de envío
- **Líder en categoría principal**: 499 ventas en Muebles
- **Menor riesgo de inversión**: Base operacional estable

## Tecnologías Utilizadas

- **Python 3.11+**
- **Pandas**: Manipulación y análisis de datos
- **Matplotlib**: Visualización de datos
- **NumPy**: Operaciones numéricas
- **Jupyter Notebook**: Desarrollo interactivo

## Estructura del Proyecto

```
challenge1-data-science-latam/
│
├── AluraStoreLatam.ipynb          # Notebook principal con análisis
├── README.md                      # Documentación del proyecto
├── .gitignore                     # Archivos ignorados por Git
├── pyproject.toml                 # Configuración de dependencias
├── poetry.lock                    # Lock file de dependencias
└── base-de-datos-challenge1-latam/
    ├── tienda_1.csv              # Datos de la tienda 1
    ├── tienda_2.csv              # Datos de la tienda 2
    ├── tienda_3.csv              # Datos de la tienda 3
    └── tienda_4.csv              # Datos de la tienda 4
```

## Cómo Ejecutar el Proyecto

### Prerrequisitos
- Python 3.11 o superior
- Poetry (recomendado para gestión de dependencias)

### Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/alura-es-cursos/challenge1-data-science-latam.git
cd challenge1-data-science-latam
```

2. **Instalar dependencias**
```bash
poetry install
```

3. **Activar entorno virtual**
```bash
poetry shell
```

4. **Ejecutar Jupyter Notebook**
```bash
jupyter notebook AluraStoreLatam.ipynb
```

### Ejecución Alternativa (pip)

```bash
pip install pandas matplotlib numpy jupyter
jupyter notebook AluraStoreLatam.ipynb
```

## Visualizaciones Incluidas

- **Gráfico de barras**: Facturación total por tienda
- **Gráfico agrupado**: Top 3 categorías por tienda
- **Gráfico dual**: Calificaciones promedio y distribución
- **Gráficos horizontales**: Productos estrella por tienda (4 paneles)
- **Gráfico comparativo**: Costos de envío y rangos

## Insights Clave

### Patrones del Mercado
- **Muebles** es la categoría #1 en todas las tiendas
- **Electrónicos** mantiene consistentemente el 2° lugar
- **Juguetes** ocupa el 3er puesto en todas las tiendas

### Oportunidades Identificadas
- Optimización de costos de envío en tienda_1
- Potencial de crecimiento en facturación para tienda_3
- Estrategias de marketing para productos rezagados

## Licencia

Este proyecto es parte del Challenge 1 Data Science Latam de Alura.

---
