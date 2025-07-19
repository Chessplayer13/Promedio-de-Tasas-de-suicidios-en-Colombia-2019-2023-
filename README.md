# Tasas de Suicidio en Colombia (2019-2023)

> Análisis descriptivo y visualización espacial de las tasas de suicidio en Colombia durante el periodo 2019-2023.

## 🔹 Descripción del Proyecto

Este repositorio presenta un análisis de las tasas de suicidio por departamento en Colombia, calculadas a partir de los microdatos de defunciones del DANE (Estadísticas Vitales, EEVV). El objetivo es visibilizar las diferencias territoriales y apoyar procesos de sensibilización a partir de los datos.

Se incluyen:

* Mapas coropléticos con tasas por cada 100.000 habitantes.
* Código Python para el preprocesamiento, cálculo de tasas y visualización.


---

## 📊 Datos

* **Fuente:** DANE, Estadísticas Vitales (EEVV) - Microdatos de defunciones (2019-2023)
* **Variables clave:** Departamento, sexo, edad, año, causa de muerte, población estimada.

Tasa de suicidio:

```math
\text{Tasa} = \left( \frac{\text{Suicidios}}{\text{Poblacion}} \right) \times 100.000
```

---

## 📚 Estructura del Repositorio

```
.
├── data/                # Archivos de datos procesados o intermedios
├── maps/                # Mapas exportados (PNG, PDF)
├── notebooks/           # Jupyter Notebooks con el código de análisis y visualización
├── src/                 # Scripts auxiliares (opcional)
├── tasa_suicidio_map.py # Script principal de generación del mapa
└── README.md            # Este archivo
```

---

## 👩‍💼 Uso

1. Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/suicidio-colombia-map.git
```

2. Instalar dependencias (opcional):

```bash
pip install -r requirements.txt
```

3. Ejecutar el notebook principal en `notebooks/` o el script en `src/` para generar el mapa.

---

## 🎨 Visualizaciones

El mapa muestra tasas promedio de suicidio en cada departamento durante el periodo 2019-2023.

* Se utiliza una escala de colores perceptible (como `OrRd`).
* Los intervalos de tasas fueron definidos manualmente para mayor claridad.
* Se incluyen etiquetas numéricas con dos decimales.
* La leyenda está posicionada fuera del área geográfica (cerca de Amazonas).

---

## 📄 Pie de página

**Elaboración propia.** La tasa de suicidio se calculó con base en los microdatos de Estadísticas Vitales del DANE (2019-2023). El cálculo de tasas está basado en la siguiente fórmula: `(número de suicidios / población total) x 100.000`.

---

## 📢 Narrativa para Difusión (Ejemplo)

> ¿Sabías que Santander registró una tasa promedio de 6.02 suicidios por cada 100.000 habitantes entre 2019 y 2023? Eso equivale a casi 2 vidas al mes. Si conoces a alguien que esté pasando por un momento difícil, escúchalo.

> ¿Y tú, en qué departamento vives?

---

## 📖 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y compartirlo con fines educativos o sociales, dando el debido crédito.
