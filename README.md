# Medrano Inmobiliaria Backend

Backend para plataforma de ventas inmobiliarias desarrollado por un equipo de 3 desarrolladores.

## Tecnologías

- Node.js
- Express.js
- MongoDB con Mongoose
- JWT para autenticación
- ESLint y Prettier para consistencia de código

## Instalación

1. Clonar el repositorio
2. Instalar dependencias:
   ```bash
   npm install
   ```

3. Configurar variables de entorno:
   ```bash
   cp .env.example .env
   ```

4. Iniciar el servidor:
   ```bash
   npm run dev
   ```

## Estructura del Proyecto

```
src/
  controllers/    # Controladores de la API
  models/         # Modelos de la base de datos
  routes/         # Rutas de la API
  middleware/     # Middleware personalizado
  utils/          # Utilidades y funciones auxiliares
  config/         # Configuración de la aplicación
```

## Scripts Disponibles

- `npm start` - Iniciar servidor en producción
- `npm run dev` - Iniciar servidor en desarrollo con nodemon
- `npm test` - Ejecutar pruebas
- `npm run lint` - Ejecutar ESLint y corregir errores
- `npm run format` - Formatear código con Prettier

## Contribución

1. Crear una rama para cada feature
2. Seguir las reglas de ESLint y Prettier
3. Hacer pull request para revisión

## Licencia

MIT
