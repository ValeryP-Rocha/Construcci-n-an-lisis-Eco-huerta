## Aplicación web para visualizar un catálogo de plantas con búsqueda y filtrado por disponibilidad.

Análisis del Proyecto
1. Flujo de datos unidireccional
Los datos van de arriba hacia abajo. El componente principal tiene la información y se la pasa a los componentes hijos. Si un hijo necesita cambiar algo, le avisa al padre mediante una función, y el padre hace el cambio.
2. El papel del useState
Guarda información que puede cambiar (el texto de búsqueda, el estado del filtro, la lista de plantas). Cuando cambia, React actualiza automáticamente la pantalla.
3. Importancia de los componentes
Hace el código más ordenado, fácil de mantener y reutilizable. Cada componente hace una sola cosa y puede usarse en diferentes lugares.
4. Ventaja de JSX
Escribes directamente cómo quieres que se vea la interfaz, en lugar de crear cada elemento paso a paso. Es más rápido y claro.
5. Componentes nuevos que se podrían agregar

Estadísticas: Mostrar totales y disponibilidad
Filtros por categoría: Botones para filtrar por tipo de planta
Detalle de planta: Modal con información completa al hacer clic
