# 📊 Análisis Operativo y Eficiencia de Carga - Puertos de Panamá

Dashboard interactivo desarrollado en **Power BI** enfocado en el análisis logístico del movimiento de contenedores en los litorales Atlántico y Pacífico de Panamá. 

El proyecto transforma datos crudos de operaciones portuarias en insights estratégicos para optimizar rutas, identificar ineficiencias de transporte (contenedores vacíos) y evaluar la estacionalidad de la demanda.

---

## 📷 Vista General del Dashboard

💡 Hallazgos y Decisiones de Negocio Clave
*   **Dominio del Litoral Atlántico:** Con un movimiento histórico de **5.1 millones de contenedores**, el Atlántico lidera la operación frente al Pacífico (**3.2 millones**). El reporte cuenta con funcionalidad de *Drill Down* para auditar individualmente puertos clave (MIT, Cristóbal, CCT, etc.).
*   **Oportunidad en Logística Inversa:** El **47.31%** de los contenedores que se movilizan vacíos (lo que representa un alto costo de reposicionamiento) se concentra en un único puerto. Centralizar allí las estrategias de intercambio de equipo reducirá drásticamente los fletes improductivos.
*   **Análisis de Estacionalidad:** El tráfico de **Trasbordo** (motor principal) experimenta una fuerte aceleración a partir de julio, alcanzando su pico máximo en septiembre para responder a la temporada alta comercial. El tráfico **Local** se mantiene plano y predecible todo el año.
*   **Eficiencia Operativa al 70.95%:** Se consolidó una tarjeta KPI directa que mide el porcentaje de contenedores llenos sobre el total, permitiendo a la dirección monitorear la salud del negocio de un vistazo rápido.
## 🛠️ Habilidades Técnicas Aplicadas
1.  **Limpieza y Transformación (Power Query):** Modificación del esquema de datos, eliminación de dependencias circulares de fechas y normalización de tablas para optimizar el rendimiento del archivo.
2.  **Modelado de Datos y DAX:** Creación de tablas de dimensiones temporales, y desarrollo de medidas personalizadas para el cálculo de tasas de eficiencia operacional y lógica regional.
3.  **UI/UX Design (Modo Oscuro):** Aplicación de principios de diseño limpio (*Clean Data Design*), reduciendo el ruido visual para guiar la vista del usuario directamente a los indicadores clave de rendimiento (KPIs).

*   `[Nombre_De_Tu_Archivo].pbix`: Archivo editable del reporte de Power BI.
*   `[Nombre_De_Tu_Base_De_Datos].csv`: Set de datos original utilizado para el análisis.
