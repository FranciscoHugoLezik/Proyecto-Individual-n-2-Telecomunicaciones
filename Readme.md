<h1 align='center'>
<b>Documentación del Proyecto Individual N°2 Telecomunicaciones</b>
</h1>
---

### Tabla de contenido
1. [Descripción](#descripción)
2. [Instalación y Requisitos](#instalación-y-requisitos)
3. [Estructura del Proyecto](#estructura-del-proyecto)
4. [Uso y Ejecución](#uso-y-ejecución)
5. [Datos y Fuentes](#datos-y-fuentes)
6. [Metodología](#metodología)
7. [Resultados y Conclusiones](#resultados-y-conclusiones)
8. [Contribución y Colaboración](#contribución-y-colaboración)
9. [Licencia](#licencia)

### Descripción

El objetivo de este proyecto es identificar las provincias que tienen mayor potencial del crecimiento del consumo de internet. Se utiliza el lenguaje Python para el análisis y la visualización de datos.

### Instalación y Requisitos
**Requisitos:**
- Python 3.11.9
- numpy
- pandas
- matplotlib
- seaborn
- fastparquet

**Pasos de instalación:**
1. Clonar el repositorio: `git clone https://github.com/FranciscoHugoLezik/Proyecto-Individual-n-2-Telecomunicaciones.git`
2. Crear un entorno virtual: `python -m venv venv`
3. Activar el entorno virtual:
   - Windows: `venv\Scripts\activate`
   - Windows con gitbash: `source venv/Scripts/activate`
   - macOS/Linux: `source venv/bin/activate`
4. Instalar las dependencias: `pip install -r requirements.txt`

### Estructura del Proyecto
```
├── data/
│   └── Internet.xlsx
├── reports/: Informes y visualizaciones.
│   ├── graficos/
│   └── reportes/
├── notebooks/: EDAs.
│   ├── analisis.py
│   ├── visualizacion.py
│   └── utils.py
├── main.py
├── requirements.txt
└── README.md: Documentación.
```

### Uso y Ejecución
1. Ejecutar `ventas_analisis.ipynb` en `notebooks/` para análisis.
2. Ejecutar `generate_report.py` en `src/` para generar un informe.

### Datos y Fuentes
Datos internos del consumo de Internet en Argentina extraidas de la página oficial del ENACOM.

### Metodología
Se aplicaron modelos de regresión y árboles de decisión para predecir ventas futuras, además de segmentación de clientes.

### Resultados y Conclusiones
- Las ventas aumentan durante verano y Navidad.
- Identificados productos más vendidos.
- El modelo predijo ventas con un 85% de precisión.

### Contribución y Colaboración
Haz un fork del repositorio.

Crea una nueva rama (git checkout -b feature/nueva-caracteristica).

Realiza tus cambios y haz commit (git commit -am 'Añadir nueva característica').

Envía tus cambios (git push origin feature/nueva-caracteristica).

Abre un Pull Request.

### Licencia
Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.

### Contacto
Si tienes preguntas o sugerencias, por favor contacta a franciscohugolezik@gmail.com.

### Autores
Francisco Hugo Lezik - Contacto: [LinkedIn](www.linkedin.com/in/francisco-hugo-lezik-7b4256220).
