# Top Investment Opportunities: Stock Market Web Scraper
Este proyecto implementa una herramienta avanzada de ingeniería de datos diseñada para identificar las 10 mejores oportunidades de inversión en el mercado de valores mediante técnicas de Web Scraping y filtrado financiero dinámico.

### -- Project Overview --
- Automatización de la extracción de datos financieros de casi 2,000 empresas con alto rendimiento en los últimos 3 años.
- Desarrollo de un motor de búsqueda que navega por perfiles corporativos para extraer métricas clave de rentabilidad.
- Implementación de un algoritmo de filtrado para seleccionar activos financieros basándose en criterios de estabilidad y crecimiento.

### -- Key Objectives --
- Desarrollar un scraper robusto capaz de manejar navegación dinámica y elementos asíncronos.
- Extraer indicadores financieros críticos: EPS (Earnings Per Share), PER (Price-to-Earnings Ratio), dividendos y año de fundación.
- Automatizar la generación de un ranking de inversión (Top 10) actualizado para el año 2024.

### -- Tech Stack --
- Language: Python.
- Web Automation: Selenium WebDriver (Chrome Headless mode).
- Data Manipulation: Pandas.
- Network & API: Requests y urllib.
- Environment: Jupyter Notebook / Google Colab.

### -- Methodology --
- Data Acquisition: Uso de Selenium para extraer una lista inicial de 481 empresas con mejor rendimiento histórico desde fuentes especializadas.
- Automated Profiling: Creación de funciones modulares (get_EPS, get_PER, get_dividend) que visitan automáticamente el perfil de cada empresa para recopilar datos específicos mediante rutas XPATH.
- Data Cleaning & Filtering: Procesamiento de fechas y formatos numéricos para normalizar la información y descartar empresas que no cumplen con los estándares de inversión.
- Ranking Logic: Aplicación de filtros lógicos sobre el DataFrame final para obtener una selección refinada de las 67 empresas más sólidas y, finalmente, las 10 mejores.

### -- Results --
- Extracción exitosa de datos detallados de cientos de empresas en tiempo real.
- Generación de un archivo top_10_invest_2024.csv listo para ser utilizado por analistas financieros o herramientas de visualización.
- Reducción drástica del tiempo de investigación de mercado, transformando horas de búsqueda manual en un proceso automatizado de pocos minutos.
