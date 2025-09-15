# Express TypeScript API Template

Una plantilla completa para crear APIs REST con Express y TypeScript.

## 🚀 Características

- ✅ **TypeScript** con configuración estricta
- ✅ **Express.js** como framework web
- ✅ **Seguridad** con Helmet y CORS
- ✅ **Rate Limiting** para protección contra abuso
- ✅ **Logging** con Morgan
- ✅ **Compresión** de respuestas
- ✅ **Validación** de datos
- ✅ **Manejo de errores** centralizado
- ✅ **Hot reload** en desarrollo
- ✅ **Testing** con Jest
- ✅ **Linting** con ESLint

## 📁 Estructura del Proyecto

```
src/
├── controllers/     # Controladores de rutas
├── routes/         # Definición de rutas
├── middleware/     # Middlewares personalizados
├── models/         # Modelos de datos
├── services/       # Lógica de negocio
├── utils/          # Utilidades
├── types/          # Definiciones de tipos TypeScript
└── app.ts          # Archivo principal
```

## 🛠️ Instalación

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Configurar variables de entorno:**
   ```bash
   cp env.example .env
   # Editar .env con tus configuraciones
   ```

3. **Ejecutar en desarrollo:**
   ```bash
   npm run dev
   ```

4. **Compilar para producción:**
   ```bash
   npm run build
   npm start
   ```

## 📝 Scripts Disponibles

- `npm run dev` - Ejecutar en modo desarrollo con hot reload
- `npm run build` - Compilar TypeScript a JavaScript
- `npm start` - Ejecutar aplicación compilada
- `npm test` - Ejecutar tests
- `npm run lint` - Verificar código con ESLint
- `npm run typecheck` - Verificar tipos de TypeScript

## 🔗 Endpoints

- `GET /health` - Health check
- `GET /api` - Información de la API

## 🧪 Testing

```bash
npm test
npm run test:watch
```

## 📊 Linting

```bash
npm run lint
npm run lint:fix
```

## 🚀 Despliegue

1. Compilar el proyecto:
   ```bash
   npm run build
   ```

2. Ejecutar en producción:
   ```bash
   npm start
   ```

## 📚 Próximos Pasos

- Agregar base de datos (PostgreSQL, MongoDB, etc.)
- Implementar autenticación JWT
- Agregar validación de datos con Joi
- Implementar tests unitarios
- Agregar documentación con Swagger
- Configurar CI/CD

