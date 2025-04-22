# Project Charter - Entendimiento del Negocio

## Nombre del Proyecto

**Pronóstico de la precipitación acumulada en Colombia, utilizando técnicas de aprendizaje automático.**

La importancia del pronóstico de la precipitación  radica en su capacidad para anticipar fenómenos meteorológicos extremos, como tormentas, inundaciones y sequías. Estas predicciones ayudan a las autoridades y comunidades a anticiparse a eventos climáticos adversos, facilitando la implementación de planes de contingencia y medidas preventivas que protejan vidas y propiedades. Además, son clave para la planificación de actividades económicas, reduciendo riesgos e impulsando decisiones más informadas.

## Objetivo del Proyecto

Desarrollar un modelo para el pronóstico de la precipitación acumulada en Colombia, utilizando técnicas de aprendizaje automático.

## Alcance del Proyecto

### Incluye:

- **Descripción de los datos disponibles**: Utilización de datos históricos de precipitación acumulada recopilados por estaciones del IDEAM desde el año 2000 hasta 2024. Los datos incluyen información geográfica (latitud, longitud, altitud) y temporal.

- **Descripción de los resultados esperados**: Desarrollo de un modelo predictivo que utilice aprendizaje automático para anticipar valores de precipitación en puntos geográficos específicos.

- **Criterios de éxito del proyecto**:
  - Entrega de los reportes de avance de cada una de las fases del proyecto.
  - Entrega de un reporte final que detallen la metodología y resultados obtenidos.

### Excluye:

- **Integración con sistemas existentes de los beneficiarios**: No se realizará la adaptación o integración del modelo en plataformas o sistemas actuales de los stakeholders.

- **Consideración de variables externas no incluidas en el dataset**: No se incorporarán datos adicionales como fenómenos climáticos globales o información satelital que no formen parte del conjunto de datos original.

## Metodología y Objetivos Específicos

Se adoptará una metodología estructurada que incluye:

1. **Entendimiento de los datos**: Seleccionar un conjunto de datos abiertos de precipitación acumulada en Colombia, verificando su acceso y calidad mediante algoritmos de análisis de datos.

2. **Procesamiento de los datos**: Implementar un proceso para la extracción, transformación y carga de los datos, aplicando técnicas de ingeniería de características.

3. **Selección del modelo**: Evaluar el desempeño de diferentes algoritmos de aprendizaje automático para el pronóstico de precipitación acumulada, utilizando los datos procesados y métricas de evaluación empleadas en predicción climática.

4. **Diseño de implementación**: Diseñar una arquitectura para la implementación del modelo en un entorno de prueba, aplicando prácticas y herramientas de operaciones de aprendizaje automático.

## Cronograma

| No. | Fase                                               | Actividades                                                         | Fecha         |
|-----|----------------------------------------------------|---------------------------------------------------------------------|---------------|
| 1   | **Entendimiento de los datos**                     | - Análisis del problema de negocio                                  | Del 31 de marzo al 06 de abril de 2025    |
|     |                                                    | - Diseño de arquitectura y selección de tecnologías                 | Del 31 de marzo al 06 de abril de 2025    |
|     |                                                    | - Derivación del problema de aprendizaje automático                 | Del 31 de marzo al 06 de abril de 2025    |
|     |                                                    | - Comprensión de los datos requeridos                               | Del 31 de marzo al 06 de abril de 2025    |
|     |                                                    | - Conexión con las fuentes de datos iniciales                       | Del 07 de abril al 13 de abril de 2025    |
|     |                                                    | - Análisis de datos                                                 | Del 14 de abril al 20 de abril de 2025    |
| 2   | **Procesamiento de los datos**                     | - Extracción de datos relevantes                                    | Del 21 de abril al 27 de abril de 2025    |
|     |                                                    | - Transformaciones y limpieza de datos                              | Del 28 de abril al 04 de mayo de 2025     |
|     |                                                    | - Carga de datos procesados                                         | Del 05 de mayo al 11 de mayo de 2025      |
| 3   | **Selección del modelo**                           | - Análisis de datos procesados                                      | Del 12 de mayo al 08 de junio de 2025     |
|     |                                                    | - Ingeniería del modelo                                             | Del 12 de mayo al 08 de junio de 2025     |
|     |                                                    | - Entrenamiento, evaluación y exportación del modelo                | Del 12 de mayo al 08 de junio de 2025     |
| 4   | **Diseño de implementación**                       | - Registro centralizado de modelos                                  | Del 09 de junio al 22 de junio de 2025    |
|     |                                                    | - Flujos de trabajo automatizados                                   | Del 16 de junio al 29 de junio de 2025    |
|     |                                                    | - Despliegue del modelo                                             | Del 23 de junio al 06 de julio de 2025    |
|     |                                                    | - Monitoreo del modelo                                              | Del 30 de junio al 13 de julio de 2025    |
|     |                                                    | - Ciclo de retroalimentación                                        | Del 07 de julio al 20 de julio de 2025    |

*Nota: Las fechas son estimadas y pueden ajustarse según el progreso del proyecto.*

## Equipo del Proyecto

- **Líder del proyecto**: *Juan Diego Mogollón Oviedo*
- **Director**: *Jorge Eliecer Camargo Mendoza*

## Presupuesto

El proyecto cuenta con un presupuesto asignado específico. Se utilizarán recursos disponibles y herramientas de código abierto para su desarrollo, optimizando al máximo los recursos existentes.

## Stakeholders

- **Instituciones meteorológicas y ambientales**: Necesitan modelos predictivos precisos para anticipar fenómenos climáticos.

- **Gobiernos locales y autoridades de gestión de emergencias**: Requieren pronósticos para gestionar riesgos de inundaciones y planificar infraestructuras.

- **Sector agrícola**: Dependiente de las precipitaciones para la planificación de cultivos y riego.

- **Compañías de seguros**: Utilizan predicciones para ajustar pólizas y calcular riesgos asociados a fenómenos climáticos.

- **Sector energético**: Empresas hidroeléctricas y de energías renovables que necesitan optimizar la producción basada en recursos hídricos.

**Relación con los stakeholders**:

El proyecto busca proporcionar una herramienta que mejore la precisión en la predicción de precipitaciones, lo que beneficiará directamente las operaciones y planificación de los stakeholders.

**Expectativas de los stakeholders**:

- **Precisión**: Obtener predicciones confiables y precisas de las precipitaciones futuras.

- **Aplicabilidad**: Que el modelo sea aplicable a diferentes regiones y escalable.

- **Utilidad práctica**: Mejorar la toma de decisiones y gestión de recursos en sus respectivos sectores.

