
# Análisis de Datos sobre la Migración Venezolana en Perú (2021-2022)

## Introducción
Este proyecto implica el análisis de los perfiles socioeconómicos de los migrantes venezolanos que residen en Perú. El objetivo principal es entender su integración en la economía peruana a través de técnicas de minería de datos, lo que permitirá a los responsables de políticas públicas optimizar las acciones dirigidas a esta población vulnerable.

## Tabla de Contenidos
- [Introducción](#introducción)
- [Descripción del Proyecto](#descripción-del-proyecto)
- [Conjuntos de Datos](#conjuntos-de-datos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Características](#características)
- [Configuración](#configuración)
- [Dependencias](#dependencias)
- [Documentación](#documentación)
- [Ejemplos](#ejemplos)
- [Solución de Problemas](#solución-de-problemas)
- [Contribuyentes](#contribuyentes)

## Descripción del Proyecto
El proyecto se basa en la **II Encuesta Dirigida a la Población Venezolana Residente en el Perú (ENPOVE 2022)**. Utilizando este conjunto de datos, el equipo aplicó técnicas de minería de datos para clasificar a los migrantes venezolanos en perfiles socioeconómicos. Estos conocimientos permitirán comprender mejor su integración en el mercado laboral, con énfasis en desafíos como el empleo informal y la vulnerabilidad social.

### Objetivos Clave:
- Clasificar los perfiles socioeconómicos de los migrantes venezolanos.
- Identificar los desafíos que enfrentan los distintos perfiles de migrantes.
- Proporcionar información basada en datos para mejorar las políticas públicas.

## Conjuntos de Datos
El proyecto utiliza los siguientes conjuntos de datos:
1. **Características de los residentes del hogar**  
   - **Descripción:** Información demográfica sobre las personas que viven en los hogares.
   - **Columnas:** [género, edad, estado civil, relación con el jefe del hogar, estado migratorio, etc.]

2. **Características de la vivienda y del hogar**  
   - **Descripción:** Detalles sobre las condiciones de la vivienda y los recursos del hogar.
   - **Columnas:** [tipo de vivienda, materiales de construcción, acceso a servicios básicos, electrodomésticos, etc.]

3. **Salud**  
   - **Descripción:** Condiciones de salud de los residentes, incluyendo enfermedades crónicas y acceso a servicios médicos.
   - **Columnas:** [enfermedades crónicas, seguro, tratamiento, etc.]

4. **Empleo**  
   - **Descripción:** Características del empleo, como tipo de ocupación, horas trabajadas y estabilidad laboral.
   - **Columnas:** [ocupación, sector, salario, tipo de empleo, etc.]

### Diccionario de Datos
El **Diccionario de Variables ENPOVE 2022** proporciona metadatos detallados para todas las variables de los conjuntos de datos. Este documento es esencial para comprender el formato, tipo y valores válidos de cada campo.

## Instalación
Para configurar este proyecto, necesitas los siguientes requisitos:
1. **Python 3.8+**
2. **Jupyter Notebook**

Puedes instalar las bibliotecas necesarias ejecutando:
```bash
pip install -r requirements.txt
```

## Uso
Una vez que el entorno esté configurado, puedes explorar los datos utilizando el cuaderno de Jupyter proporcionado. El cuaderno demuestra la limpieza, exploración y análisis de los datos utilizando técnicas de minería de datos como el clustering y los árboles de decisión.

1. Clona el repositorio:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```
2. Ejecuta el cuaderno:
   ```bash
   jupyter notebook Grupo1_TA_Parcial_Codigo.ipynb
   ```

## Características
- **Limpieza y Preprocesamiento de Datos:** Manejo de datos faltantes y categorización de variables socioeconómicas.
- **Técnicas de Minería de Datos:** Aplicación de análisis de clusters y árboles de decisión para segmentar la población migrante.
- **Visualizaciones:** Gráficos para entender las tendencias de empleo, condiciones de vivienda y estado de salud.

## Configuración
La configuración incluye la especificación de las rutas para los conjuntos de datos:
- `Características de los residentes del hogar.csv`
- `Características de la vivienda y del hogar.csv`
- `Salud.csv`
- `Empleo.csv`

Estos archivos deben colocarse en el directorio `data/` dentro de la estructura del proyecto.

## Dependencias
- **pandas**
- **numpy**
- **scikit-learn**
- **matplotlib**
- **seaborn**

Todas las dependencias pueden ser instaladas utilizando el archivo `requirements.txt`.

## Documentación
- **Metodología:** La metodología sigue el proceso de Descubrimiento de Conocimiento en Bases de Datos (KDD), centrándose en la preparación, análisis e interpretación de datos socioeconómicos.
- **Fuentes de Datos:** Los conjuntos de datos fueron obtenidos del Instituto Nacional de Estadística e Informática de Perú (INEI) y la encuesta ENPOVE 2022.

## Ejemplos
En el cuaderno de Jupyter se muestran varios ejemplos que clasifican a los migrantes venezolanos según el tipo de empleo y el estado de salud. Estos ejemplos utilizan datos reales de la encuesta y aplican varias técnicas de minería de datos.

## Solución de Problemas
- **Datos no se cargan:** Asegúrate de que los archivos CSV estén colocados en el directorio correcto y que las rutas estén correctamente especificadas en el cuaderno.
- **Dependencias faltantes:** Ejecuta `pip install -r requirements.txt` para instalar todas las bibliotecas necesarias.

## Contribuyentes
- **Carlos Felipe Mariños Ore**  
  [cf.marinoso@alum.up.edu.pe](mailto:cf.marinoso@alum.up.edu.pe)
- **Cynthia Zhou Chun Miao Zhou Lin**  
  [cz.zhoul@alum.up.edu.pe](mailto:cz.zhoul@alum.up.edu.pe)
- **Fabrizio Hernan Montalvo Pascal**  
  [fh.montalvop@alum.up.edu.pe](mailto:fh.montalvop@alum.up.edu.pe)
- **Paolo Cesar Salazar Patricio**  
  [pc.salazarp@alum.up.edu.pe](mailto:pc.salazarp@alum.up.edu.pe)
