# 📊 Grupo Andes: Análisis Comercial e Inmobiliario
Este repositorio contiene el análisis de desempeño comercial y el modelado de datos para Grupo Andes, enfocado en la evaluación de ventas, rentabilidad por activo y comportamiento de recurrencia de clientes entre 2023 y 2024.

El proyecto implementa un modelo de datos robusto (Esquema Estrella) para transformar registros transaccionales en un dashboard ejecutivo que fundamenta decisiones estratégicas mediante evidencia numérica.

📂 Contenido del Repositorio

S11_Estudiante_Proyecto_InmobiliarioGrupoAndes.ipynb: Notebook de validación que incluye la limpieza de datos, diseño de medidas DAX y resumen ejecutivo.

URL_Dashboard.txt: Enlace al reporte interactivo (Power BI) con la visualización final de los KPIs.

🧠 Objetivo del Análisis
El propósito es diagnosticar la salud financiera y comercial de la empresa, respondiendo a interrogantes críticos de negocio:

¿Qué tipos de propiedad y canales de venta maximizan el margen de comisión?

¿Cómo evoluciona el crecimiento interanual (YoY) y el desempeño acumulado (YTD)?

¿Existe una retención efectiva de clientes tras su primera adquisición (Análisis de Cohortes)?

🛠️ Tecnologías y Metodología

Modelado de Datos: Estructura de Esquema Estrella con tablas dimensionales (dim_clientes, dim_propiedades, dim_fecha) conectadas a una tabla de hechos central.

Ingeniería de Métricas: Uso de DAX / Campos Calculados para determinar Ingreso Total, Ticket Promedio y Medidas de Participación (%) con contextos de filtro específicos (CALCULATE, ALL).

Inteligencia de Tiempo: Creación de una tabla calendario dinámica para análisis de tendencias y comparativas temporales.

📈 Hallazgos Clave (Insights)

Motores de Ingreso y Rentabilidad

Evidencia: Las Casas generan el 37.26% del revenue total ($2,241M), pero las propiedades Comerciales poseen el ticket promedio más alto ($1,797,097).

Insight: El volumen está en el mercado residencial, pero la eficiencia operativa y el retorno por transacción se concentran en el segmento comercial.

Eficiencia de Canales de Venta

Evidencia: El canal Corredor domina el 72.8% del ingreso total con 6,181 ventas.

Insight: Existe una dependencia crítica de intermediarios. Dado que el ticket promedio es similar al canal Directo, fortalecer la venta directa en activos de alto valor (Comerciales) evitaría el pago de comisiones sobre montos superiores a $1.8M.

Análisis de Retención (Cohortes)

Evidencia: El 77.1% de los clientes son recurrentes, pero los clientes de "Primera vez" tienen una retención mensual de solo el 9.4%.

Insight: El negocio es exitoso adquiriendo clientes, pero falla en la conversión inmediata hacia una segunda compra. Existe una fuga de valor masiva en los primeros 90 días post-venta.

🚀 Conclusiones y Estrategia

[!IMPORTANT]
Prioridad 1: Implementar un programa de retención para compradores de "Primera vez". Elevar la retención al 15% representaría un ingreso adicional estimado de $180M anuales.

Prioridad 2: Planificar campañas de marketing agresivas en Q1 y Q3, periodos donde se identificó una estacionalidad de demanda natural y picos consistentes de ingresos.
