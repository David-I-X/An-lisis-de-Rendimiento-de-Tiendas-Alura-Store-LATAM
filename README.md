
---

# 🛍️ Análisis de Rendimiento de Tiendas – Alura Store LATAM

Este proyecto busca ayudar al Sr. Juan, propietario de la cadena **Alura Store**, a tomar una decisión informada sobre cuál de sus 4 tiendas debería vender para financiar un nuevo emprendimiento. A través del análisis de ventas, calificaciones, costos de envío y distribución geográfica, se identifica la tienda menos eficiente.

---

## 📁 Estructura del Proyecto

* `AluraStoreLatam.ipynb` – Notebook principal con todo el análisis y visualizaciones.
* Imágenes generadas durante el análisis (`heatmap`, `mapa interactivo`, gráficos comparativos).

> 🔧 **Nota sobre compatibilidad con GitHub:**
> Algunas secciones de código en el notebook (específicamente *Mapa Interactivo* y *Análisis Espacial Agregado*) se encuentran escritas como celdas de tipo Markdown en lugar de código, con el fin de asegurar una correcta visualización en la vista previa de GitHub.
> Para ejecutar estas secciones, simplemente cambia el tipo de celda de **Markdown** a **Code** dentro de Jupyter Notebook o JupyterLab.

---

## ⚙️ Instalación y Entorno

### 1. 🔧 Requisitos

Asegúrate de tener instalado:

* Python 3.8 o superior
* Jupyter Notebook o JupyterLab

### 2. 🧩 Dependencias

Puedes instalar las dependencias necesarias usando `pip`:

```bash
pip install pandas numpy matplotlib seaborn folium
```

Opcional (para entornos gestionados):

```bash
pip install jupyterlab
```

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio o descarga los archivos.
2. Abre el archivo `AluraStoreLatam.ipynb` con Jupyter Notebook o JupyterLab.
3. Ejecuta cada celda secuencialmente para cargar los datos, generar análisis y visualizar los mapas.

---

## 🗺️ Visualización Interactiva

* El mapa interactivo y el mapa de calor se generan directamente en el notebook sin necesidad de exportar archivos `.html`.
* Las visualizaciones comparativas (barras, heatmaps) también se despliegan automáticamente.

---

## ❗ Posibles Problemas y Soluciones

| Problema                                       | Solución                                                                 |
| ---------------------------------------------- | ------------------------------------------------------------------------ |
| `ModuleNotFoundError` al ejecutar alguna celda | Ejecuta `pip install` para instalar el módulo faltante                   |
| Mapas no se muestran correctamente en Jupyter  | Asegúrate de ejecutar todas las celdas y usar un entorno como JupyterLab |

---

## ✅ Resultado Final

**Conclusión del Análisis:**
La **Tienda 4** es la menos rentable y presenta menor eficiencia operativa. Se recomienda al Sr. Juan vender esta tienda y conservar la Tienda 1 como activo estratégico.

---

## 👨‍💼 Autor

Proyecto desarrollado como parte del estudio de análisis de datos para negocios.
**Contacto:** ([david.aguirreix@gmail.com](mailto:david.aguirreix@gmail.com))

---
