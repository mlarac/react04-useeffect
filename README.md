# Pizzería Mamma Mia - Aplicación Web


Este es un proyecto de una aplicación web para la Pizzería Mamma Mia. La aplicación permite a los usuarios ver el menú de pizzas, agregar productos al carrito de compras, y simular una experiencia de compra. Está desarrollada usando React, Bootstrap y una API local para gestionar los datos de las pizzas.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Ejecución del Proyecto](#ejecución-del-proyecto)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Descripción de Componentes](#descripción-de-componentes)
- [API](#api)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Instalación

Para instalar y ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/pizzeria-mamma-mia.git
   ```
2. **Navega al directorio del proyecto**:
   ```bash
   cd pizzeria-mamma-mia
   ```
3. **Instala las dependencias**:
   ```bash
   npm install
   ```

## Ejecución del Proyecto

1. **Inicia el servidor de la API local**:
   Asegúrate de tener la API en funcionamiento. Si estás utilizando un servidor local para la API, asegúrate de que está corriendo en `http://localhost:5000`.

2. **Inicia la aplicación React**:
   ```bash
   npm run dev
   ```
   La aplicación se abrirá automáticamente en tu navegador en `http://localhost:5173`.

## Estructura del Proyecto

```
pizzeria-mamma-mia/
├── public/
├── src/
│   ├── assets/
│   │   └── pizzas.js           # Simulación de datos de pizzas
│   ├── components/
│   │   ├── NavigationBar.jsx   # Componente de barra de navegación
│   │   ├── Footer.jsx          # Componente de pie de página
│   │   ├── Header.jsx          # Componente de cabecera con imagen de fondo
│   │   ├── CardPizza.jsx       # Componente de tarjeta para mostrar pizzas
│   │   └── Cart.jsx            # Componente de carrito de compras
│   ├── pages/
│   │   └── Home.jsx            # Página principal que muestra el menú de pizzas
│   ├── App.css                 # Estilos globales
│   ├── App.jsx                 # Componente principal de la aplicación
│   └── main.jsx                # Punto de entrada de la aplicación
├── package.json
└── README.md
```

## Descripción de Componentes

- **NavigationBar**: Barra de navegación que incluye el nombre del negocio y enlaces de navegación.
- **Footer**: Pie de página que incluye información de derechos de autor.
- **Header**: Componente que muestra una imagen de fondo con texto centrado.
- **CardPizza**: Tarjeta que muestra la información de una pizza específica.
- **Cart**: Componente que simula un carrito de compras, mostrando las pizzas añadidas y permitiendo la modificación de la cantidad.

## API

Este proyecto se conecta a una API local para obtener los datos de las pizzas. Asegúrate de que la API esté corriendo antes de iniciar la aplicación.

### Endpoints

- `GET /api/pizzas`: Retorna una lista de todas las pizzas disponibles.
- `GET /api/pizzas/:id`: Retorna los detalles de una pizza específica por ID.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto o solucionar algún problema, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y realiza un commit (`git commit -m 'Añadida nueva funcionalidad'`).
4. Sube los cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
