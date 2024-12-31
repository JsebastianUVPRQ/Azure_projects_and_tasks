Parámetro	Descripción
Nombre		Un nombre único para el servicio vinculado
Descripción	Una descripción significativa
Tiempo de ejecución de integración	El entorno de ejecución de integración que se usa para ejecutar actividades en este servicio vinculado. Consulte Entorno de ejecución de integración en Azure Data Factory para obtener más información.
Suscripción de Azure		La suscripción de Azure en la que se aprovisiona Azure Databricks
Área de trabajo de Databricks		El área de trabajo de Azure Databricks
Clúster		El clúster de Spark en el que se ejecutará el código de actividad. Puede hacer que Azure Databricks aprovisione dinámicamente un clúster de trabajos a petición o puede especificar un clúster existente en el área de trabajo.
Tipo de autenticación		Cómo se autenticará la conexión vinculada mediante Azure Databricks. Por ejemplo, mediante un token de acceso (en cuyo caso, debe especificar el token de acceso que generó para el área de trabajo).
Configuración del clúster		La versión del entorno de ejecución de Databricks, la versión de Python, el tipo de nodo de trabajo y el número de nodos de trabajo del clúster.