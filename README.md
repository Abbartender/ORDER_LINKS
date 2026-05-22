# 🔗 Link Organizer

Una aplicación web moderna y elegante para organizar y gestionar los links de tus proyectos, landings y aplicaciones.

## ✨ Características

- 🔍 **Búsqueda en tiempo real** - Filtra por título, URL o descripción
- 💾 **Almacenamiento local** - Tus links se guardan en el navegador (localStorage)
- 📊 **Estadísticas** - Visualiza el total de links y resultados filtrados
- 🎨 **Diseño moderno** - Interfaz oscura con animaciones suaves
- 📱 **Responsive** - Funciona perfectamente en móvil, tablet y desktop
- ⚡ **100% cliente** - No requiere backend ni base de datos

## 🚀 Despliegue en Vercel

### Opción 1: Desde GitHub (Recomendado)

1. **Sube el proyecto a GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/link-organizer.git
   git push -u origin main
   ```

2. **Despliega en Vercel:**
   - Ve a [vercel.com](https://vercel.com)
   - Haz clic en "Add New Project"
   - Importa tu repositorio de GitHub
   - Vercel detectará automáticamente la configuración
   - Haz clic en "Deploy"

### Opción 2: Vercel CLI

1. **Instala Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Despliega:**
   ```bash
   vercel
   ```

3. **Para producción:**
   ```bash
   vercel --prod
   ```

## 📦 Estructura del proyecto

```
link-organizer/
├── index.html        # Aplicación completa (HTML + CSS + JS)
├── vercel.json       # Configuración de Vercel
└── README.md         # Este archivo
```

## 🎯 Uso

1. **Agregar un link:**
   - Completa el título (requerido)
   - Ingresa la URL (requerida, debe comenzar con http:// o https://)
   - Opcionalmente agrega una descripción
   - Haz clic en "Agregar Link"

2. **Buscar links:**
   - Escribe en la barra de búsqueda
   - Los resultados se filtran en tiempo real
   - La búsqueda funciona en título, URL y descripción

3. **Eliminar un link:**
   - Haz clic en el botón "Eliminar" en cualquier tarjeta
   - Confirma la eliminación

4. **Atajos de teclado:**
   - `Enter` en el título → salta a URL
   - `Enter` en URL → salta a descripción
   - `Ctrl + Enter` en descripción → agrega el link

## 💾 Almacenamiento

Los links se guardan en `localStorage` del navegador. Esto significa:

- ✅ Los datos persisten entre sesiones
- ✅ No requiere cuenta ni login
- ✅ Funciona offline
- ⚠️ Los datos se guardan por dominio/navegador
- ⚠️ Limpiar el caché del navegador borrará los datos

## 🎨 Personalización

El archivo `index.html` contiene todo el código. Puedes personalizar:

- **Colores:** Modifica las variables CSS en `:root`
- **Fuentes:** Cambia las importaciones de Google Fonts
- **Layout:** Ajusta el grid y espaciados en los estilos

## 🔧 Tecnologías

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- Vanilla JavaScript (ES6+)
- LocalStorage API

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Siéntete libre de:

- Reportar bugs
- Sugerir nuevas características
- Enviar pull requests

## 📝 Notas

- La aplicación funciona completamente del lado del cliente
- No se envían datos a ningún servidor
- Los links se almacenan únicamente en tu navegador

---

Hecho con ❤️ para organizar tus proyectos
