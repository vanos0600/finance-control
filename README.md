Dashboard de Finanzas Personales
Descripción del Proyecto
Este proyecto es un dashboard interactivo de finanzas personales, diseñado para visualizar de manera clara y sencilla los ingresos, gastos y ahorros. La aplicación fue construida como un ejemplo de un proyecto de portafolio, utilizando tecnologías modernas de desarrollo web para mostrar habilidades en la creación de interfaces dinámicas y responsivas.

Características Principales
Visualización de Datos: Muestra un resumen de los ingresos, gastos, ahorros netos y el ahorro anual proyectado en tarjetas claras y concisas.

Gráficos: Incluye un gráfico de barras para comparar ingresos y gastos, y un gráfico circular para desglosar los gastos por categoría.

Datos Dinámicos: Los datos son simulados (mock data) para demostrar el manejo del estado y la actualización de la UI sin necesidad de un backend.

Interactividad: Permite filtrar transacciones por mes y por prioridad, y ajustar el ingreso mensual y la meta de ahorro.

Modo Oscuro: Cuenta con una opción para alternar entre el modo claro y el modo oscuro, mejorando la experiencia de usuario en diferentes entornos.

Diseño Responsivo: El diseño se adapta a diferentes tamaños de pantalla, desde dispositivos móviles hasta escritorios.

Tecnologías Utilizadas
Next.js: Framework de React para el desarrollo de la aplicación.

React: Biblioteca para la construcción de la interfaz de usuario.

Tailwind CSS: Framework de CSS para un estilo rápido y moderno.

JavaScript (HTML Canvas): Utilizado para el renderizado de gráficos de manera eficiente.

Estructura del Proyecto
El código está organizado de la siguiente manera para una mejor modularidad y mantenimiento:

finance-dashboard/
├── pages/
│   └── index.js        # Dashboard principal (Componente raíz)
├── components/
│   ├── Card.js         # Componente para las tarjetas de métricas
│   ├── Transactions.js # Componente para la lista de transacciones
│   └── Charts.js       # Componente para los gráficos de barras y pastel
└── data/
    └── mockData.js     # Datos de transacciones simulados

Cómo Ejecutar el Proyecto
Clonar el repositorio:

git clone [https://github.com/vanos0600/finance-control.git](https://github.com/vanos0600/finance-control.git)
cd finance-control

Instalar dependencias:

npm install

Ejecutar el servidor de desarrollo:

npm run dev

Abrir en el navegador:
La aplicación estará disponible en http://localhost:3000.

Licencia
Este proyecto está bajo la licencia MIT.
