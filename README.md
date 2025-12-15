# milk-o-meter 🍼

Una aplicación web simple para el seguimiento de lactancia materna. Diseñada con amor para facilitar el registro de tomas y estadísticas.

## ✨ Características

### 📝 Registro de Tomas
- **Registro completo**: Hora de inicio y fin, calidad (1-5 estrellas), teta (izquierda/derecha/ambas) y comentarios
- **Tomas en curso**: Permite registrar tomas que aún están en progreso (sin hora de fin)
- **Edición y eliminación**: Modifica o elimina cualquier toma registrada
- **Cálculo automático**: Calcula correctamente el tiempo incluso cuando las tomas cruzan la medianoche

### 📊 Resumen Diario
- **Estadísticas del día**: Total de tomas, tiempo total acumulado y hora de la última toma
- **Vista rápida**: Información esencial visible de un vistazo

### 📈 Estadísticas Detalladas
Panel expandible con análisis completo:
- **Resumen general**: Total de días, tomas, tiempo total y promedio por día
- **Promedios**: Tiempo promedio por toma y calidad promedio
- **Distribución por teta**: Porcentajes y cantidades de izquierda, derecha y ambas
- **Récords**: Día con más tomas y día con más tiempo
- **Últimos 7 días**: Tabla detallada con tomas, tiempo y calidad promedio por día

### 💾 Almacenamiento y Sincronización
- **Almacenamiento local**: Los datos se guardan en el navegador (localStorage)
- **Sincronización con GitHub**: Opción de sincronizar automáticamente con un repositorio de GitHub
- **Sincronización automática**: Se sincroniza cada 30 segundos cuando está configurado
- **Configuración simplificada**: Si usas la contraseña por defecto, la configuración se carga automáticamente

### 🎨 Diseño
- **Interfaz bonita**: Colores pastel suaves y diseño moderno
- **Responsive**: Optimizado para móviles y tablets
- **Historial mejorado**: Diseño mejorado para móvil con botones siempre alineados
- **Fechas en español**: Formato largo y legible (ej: "Sábado, 11 de diciembre")
- **Estrellas amarillas**: Visualización clara de la calidad de cada toma

### 🔒 Seguridad
- **Autenticación simple**: Protección con contraseña
- **Datos privados**: Toda la información se almacena localmente o en tu repositorio privado de GitHub

## 🚀 Uso

### Inicio Rápido

1. Abre `index.html` en tu navegador
2. Ingresa la contraseña (por defecto: `ari`)
3. ¡Empieza a registrar tomas!

### Registro de una Toma

1. Haz clic en "Nueva Toma"
2. Completa los campos:
   - **Hora inicio**: Hora en que comenzó la toma
   - **Hora fin**: Hora en que terminó (o deja vacío si aún está tomando)
   - **Calidad**: Selecciona de 1 a 5 estrellas
   - **Teta**: Izquierda, Derecha o Ambas
   - **Comentarios**: Notas adicionales (opcional)
3. Guarda la toma

### Edición y Eliminación

- **Editar**: Haz clic en el botón de lápiz (✏️) junto a cualquier toma
- **Eliminar**: Haz clic en el botón de papelera (🗑️) y confirma

### Sincronización con GitHub (Opcional)

La aplicación puede sincronizar automáticamente tus datos con un repositorio de GitHub:

1. Crea un repositorio en GitHub (público o privado)
2. Crea un token de acceso personal con permisos `repo`
3. Si usas la contraseña por defecto, la configuración se carga automáticamente
4. Los datos se sincronizarán cada 30 segundos

## 🛠️ Tecnologías

- **HTML5**: Estructura
- **CSS3**: Estilos y diseño responsive
- **JavaScript (Vanilla)**: Lógica de la aplicación
- **Bootstrap 5.3.3**: Framework CSS para componentes
- **Bootstrap Icons**: Iconografía
- **GitHub API**: Sincronización de datos (opcional)

## 📱 Compatibilidad

- ✅ Navegadores modernos (Chrome, Firefox, Safari, Edge)
- ✅ Dispositivos móviles (iOS, Android)
- ✅ Tablets
- ✅ Escritorio

## 📝 Notas

- Los datos se almacenan localmente en el navegador
- Si cambias de navegador o dispositivo, necesitarás la sincronización con GitHub para acceder a tus datos
- Las tomas que cruzan la medianoche se calculan correctamente
- El formato de fecha es en español con formato largo y legible

## 💕 Hecho con amor

Esta aplicación fue creada para facilitar el seguimiento de la lactancia materna, haciendo que registrar y analizar las tomas sea simple y agradable.

---

**Versión**: 2.0  
**Última actualización**: Diciembre 2025
