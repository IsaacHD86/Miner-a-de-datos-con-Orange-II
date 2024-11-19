# Miner-a-de-datos-con-Orange-II
Agile Data Science y minería de datos con Orange II.

# Análisis de Efectividad de Medicamentos utilizando Orange

Este proyecto tiene como objetivo construir un modelo predictivo utilizando la plataforma **Orange** para determinar el medicamento más apropiado para pacientes que sufren de una misma enfermedad. 
El estudio se centra en evaluar la respuesta de los pacientes a 5 diferentes medicamentos: **Fármaco A**, **Fármaco B**, **Fármaco C** (proveedor nacional), **Fármaco X** y **Fármaco Y** (proveedor extranjero).

## Descripción del Proyecto

El análisis se lleva a cabo mediante el uso de herramientas de Ciencia de Datos para entender y predecir la efectividad de diversos tratamientos médicos. Utilizando **Orange**, una plataforma de análisis visual basada en flujos de trabajo, se construirá un modelo que permitirá predecir el medicamento adecuado para futuros pacientes.

### Objetivos:

1. **Explorar los Datos**:
   - Importar y analizar datos de pacientes con la misma enfermedad, incluyendo la respuesta a distintos medicamentos.
   - Preprocesar los datos, manejar valores faltantes y normalizar la información para optimizar el modelo.

2. **Construcción del Modelo**:
   - Utilizar **algoritmos de clasificación** en Orange, como árboles de decisión, máquinas de vectores de soporte (SVM) y k-NN.
   - Evaluar el rendimiento de los modelos utilizando métricas como **precisión**, **recall** y **curva ROC**.

3. **Comparación de Enfoques de Gestión de Proyectos**:
   - Analizar las diferencias entre trabajar en un **enfoque tradicional** (cascada) y un enfoque **ágil** (SCRUM/Kanban) en un proyecto de Ciencia de Datos.
   - Discutir las ventajas y desventajas de ambos enfoques, con ejemplos aplicados al análisis de datos médicos.

## Enfoques de Gestión de Proyectos: Tradicional vs Ágil

### Enfoque Tradicional (Cascada)

El enfoque tradicional sigue un flujo lineal y secuencial para la gestión de proyectos. Este enfoque es útil cuando los **requisitos son claros y no cambian** durante el ciclo del proyecto.

**Ventajas**:
- Estructura clara y definida.
- Fácil de seguir para proyectos con requisitos bien establecidos.
- Buena documentación en cada fase.

**Desventajas**:
- Menos flexibilidad ante cambios.
- Los problemas se detectan tarde, lo que puede resultar en un alto costo de corrección.
- No permite retroalimentación continua, lo que es crucial en proyectos de Ciencia de Datos.

### Enfoque Ágil (SCRUM/Kanban)

El enfoque ágil se basa en **iteraciones cortas** y **entregas continuas**. Es ideal para proyectos de Ciencia de Datos donde los requisitos pueden evolucionar basados en el análisis de datos y los resultados intermedios.

**Ventajas**:
- Mayor flexibilidad y adaptabilidad a los cambios.
- Retroalimentación constante y mejoras continuas.
- Ideal para proyectos exploratorios y experimentales.

**Desventajas**:
- Puede ser difícil de gestionar sin experiencia previa en metodologías ágiles.
- Requiere mayor comunicación y colaboración entre equipos.
- Posibilidad de alcance ampliado (scope creep) si no se gestiona adecuadamente.

### Ejemplo de Caso Real: Proyecto de Ciencia de Datos en Medicina

**Escenario**: 
Eres un investigador médico que ha recopilado datos sobre un grupo de pacientes, todos con la misma enfermedad. Durante su tratamiento, cada paciente respondió a uno de los 5 medicamentos mencionados anteriormente. El objetivo es predecir cuál medicamento podría ser más efectivo para futuros pacientes.

- En un enfoque **tradicional**, se definirían todas las variables y el diseño del estudio antes de comenzar el análisis. Una vez que los datos están listos, se construiría un modelo con Orange, pero cualquier cambio o ajuste tardaría más tiempo.
- En un enfoque **ágil**, se podría empezar rápidamente con los datos disponibles, construir prototipos de modelos, probar diferentes algoritmos en Orange, y ajustar según los resultados obtenidos en cada sprint.

## Requisitos del Proyecto

Para replicar este proyecto, asegúrate de tener instaladas las siguientes herramientas:

- [Orange](https://orange.biolab.si/download/)
- Dataset con los registros médicos en formato CSV.

## Conclusiones

Al trabajar con enfoques ágiles y la plataforma Orange, se puede optimizar el tiempo de desarrollo y mejorar la precisión del análisis predictivo en la medicina personalizada. 
La metodología ágil permite ajustes rápidos basados en la retroalimentación, lo que es especialmente útil en proyectos de Ciencia de Datos con datos complejos y cambiantes.

## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
