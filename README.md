# EA1.AnalisisPIBDepartamental
Análisis del PIB Departamental en Colombia
Proyecto Integrado III — Ingeniería de Software

Descripción del Problema
Colombia presenta profundas disparidades económicas entre sus regiones. Mientras departamentos como Bogotá D.C. y Antioquia concentran gran parte de la actividad económica nacional, muchos otros presentan niveles de desarrollo significativamente menores. Esta brecha afecta la calidad de vida de los ciudadanos y la formulación de políticas públicas de desarrollo territorial.
Pregunta de Negocio

¿Cuáles son las desigualdades económicas entre los departamentos de Colombia y qué tendencia presenta el PIB departamental hacia el futuro, con el fin de identificar regiones que requieren mayor atención en política económica?

Fuente de Datos
AtributoDetalleNombrePIB Departamental con proyecciónFuenteDANE — Departamento Administrativo Nacional de EstadísticaPortalPortal de Datos Abiertos de ColombiaURLhttps://www.datos.gov.co/Econom-a-y-Finanzas/PIB-Departamental-con-proyecci-n/kgyi-qc7jFormatoCSVCobertura32 departamentos + Bogotá D.C.LicenciaDatos Abiertos — Libre uso
 Estructura del Repositorio
├── README.md
├── EA1_exploracion_pib_departamental.ipynb   # Notebook con código de exploración
├── pib_departamental.csv                 # Dataset (descargar del portal)
└── reporte_pib_departamental.html        # Reporte generado por ydata-profiling
Cómo ejecutar el notebook

Clona este repositorio:

bash   git clone <https://github.com/pipe21v/EA1.AnalisisPIBDepartamental>
   cd <EA1.AnalisisPIBDepartamental>

Instala las dependencias:

bash   pip install pandas ydata-profiling matplotlib seaborn

Descarga el dataset desde el portal de datos abiertos y guárdalo como pib_departamental.csv en la raíz del proyecto.
Abre el notebook:

bash   jupyter notebook exploracion_pib_departamental.ipynb
Tecnologías utilizadas

Python 
Pandas
ydata-profiling (Pandas Profiling)
Matplotlib
Seaborn
Jupyter Notebook

Autor

Estudiante: Luis Felipe Ladino Monsalve
Curso: Proyecto Integrado III
Programa: Ingeniería de Software y Datos
Institución: IU Digital de Antioquia
Año: 2026
