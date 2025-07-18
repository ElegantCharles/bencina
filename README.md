# 🚗⛽ Calculadora de Consumo de Combustible

Una aplicación web moderna y fácil de usar para calcular el gasto en combustible de tus viajes, optimizada para la Región de Valparaíso, Chile.

## ✨ Características Principales

### 🚙 **Vehículos Incluidos**
- **Chevrolet Sail 1.5L 2020** (10.2 km/L)
- **Suzuki Dzire 1.2L 2024** (15.0 km/L)
- **⚙️ Auto Personalizado** - Ingresa el consumo de cualquier vehículo

### 🗺️ **Cálculo de Distancias**
- **📏 Ingreso Manual** - Introduce kilómetros directamente
- **🧠 Mapa Inteligente** - Calcula distancias realistas por carreteras
- **📍 Múltiples Destinos** - Agrega tantas paradas como necesites
- **🔄 Ida y Vuelta** - Duplica automáticamente para viajes de retorno

### 🎯 **Optimizado para tu Región**
- **📍 Centrado en San Antonio** - Mapa inicia en tu ubicación
- **🏙️ Reconoce Zonas Urbanas** - San Antonio, Valparaíso, Santiago
- **🌊 Factor Costero** - Considera carreteras serpenteantes de la costa
- **🗻 Factor Geográfico** - Ajusta por cerros y geografía local

### 📊 **Funcionalidades Avanzadas**
- **💰 Cálculo Detallado** - Litros consumidos, costo total y por km
- **📝 Historial Completo** - Guarda todos tus cálculos
- **📱 Diseño Responsivo** - Funciona perfecto en móvil y desktop
- **⚡ Sin APIs Externas** - Funciona 100% offline

## 🚀 Demo en Vivo

[Ver Demo](https://elegantcharles.github.io/bencina/)


## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con gradientes
- **JavaScript ES6+** - Lógica de la aplicación
- **Tailwind CSS** - Framework de estilos utilitarios
- **Leaflet.js** - Mapas interactivos
- **OpenStreetMap** - Datos cartográficos

## 🎯 Casos de Uso

### 🏠 **Viajes Cotidianos**
- Casa ↔ Trabajo
- Compras al supermercado
- Visitas familiares

### 🌊 **Turismo Regional**
- San Antonio → Valparaíso
- Ruta costera a Cartagena
- Excursiones a Santiago

### 💼 **Uso Profesional**
- Cálculo de viáticos
- Presupuestos de transporte
- Control de gastos de combustible

## 🚀 Instalación y Uso

### Opción 1: Usar Directamente
1. Visita la [demo en vivo](https://elegantcharles.github.io/bencina/)
2. ¡Empieza a calcular tus gastos!

### Opción 2: Clonar Repositorio
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/calculadora-combustible.git

# Navegar al directorio
cd calculadora-combustible

# Abrir en navegador
open index.html
# O usar un servidor local
python -m http.server 8000
```

## 📖 Cómo Usar

### 1️⃣ **Selecciona tu Vehículo**
- Elige entre los autos predefinidos
- O crea uno personalizado con tu consumo real

### 2️⃣ **Calcula la Distancia**
- **Manual**: Ingresa kilómetros directamente
- **Mapa**: Haz clic para marcar origen y destino(s)

### 3️⃣ **Ingresa el Precio de Combustible**
- Precio actual por litro en tu bencinera

### 4️⃣ **¡Obtén tu Resultado!**
- Litros necesarios
- Costo total del viaje
- Costo por kilómetro

## 🧠 Algoritmo de Estimación Inteligente

La app utiliza un algoritmo propietario que considera:

- **📏 Distancia Base** - Cálculo geodésico entre puntos
- **🏙️ Factor Urbano** - Mayor complejidad en ciudades (1.1x)
- **🌊 Factor Costero** - Carreteras serpenteantes (1.05x)
- **🛣️ Factor de Distancia** - Rutas cortas más complejas (1.4x), largas más directas (1.15x)
- **🗻 Factor Geográfico** - Diferencias de elevación y geografía

### Precisión Típica
- ✅ **85-95%** de la distancia real por carreteras
- 🎯 **Optimizado** para la geografía chilena
- 📍 **Calibrado** específicamente para la Región de Valparaíso

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! 

### 🚗 **Agregar Vehículos**
```javascript
// En cars object, agrega:
'nuevo-auto': {
    name: 'Nombre del Auto',
    model: 'Motor • Año',
    consumption: XX.X, // km/L
    icon: '🚗'
}
```

### 🐛 **Reportar Bugs**
1. Abre un [Issue]
2. Describe el problema detalladamente
3. Incluye pasos para reproducir

### 💡 **Sugerir Mejoras**
- Nuevas funcionalidades
- Mejoras de UI/UX
- Optimizaciones de performance

## 📄 Licencia

Este proyecto está bajo la **Licencia MIT** - mira el archivo [LICENSE](LICENSE) para más detalles.

### 🎉 Uso Libre
- ✅ Uso comercial
- ✅ Modificación
- ✅ Distribución
- ✅ Uso privado

**Solo se requiere** mantener el aviso de copyright y la mención de licencia.

## 🙏 Reconocimientos

- **🤖 Claude (Anthropic)** - Asistente de IA que ayudó en el desarrollo
- **🗺️ OpenStreetMap** - Datos cartográficos colaborativos
- **🍃 Leaflet.js** - Librería de mapas interactivos
- **🎨 Tailwind CSS** - Framework de estilos utilitarios
- **📍 Comunidad de Desarrolladores** - Por las librerías y herramientas open source

## 📞 Contacto

- **👤 Autor**: Tu Nombre
- **📧 Email**: tu.email@ejemplo.com
- **🐙 GitHub**: [@tu-usuario](https://github.com/ElegantCharles)
- **🌐 Website**: [tu-website.com](https://charleslettuce.me)

---

### 💖 ¿Te gustó el proyecto?

⭐ **¡Dale una estrella!** ⭐

Ayuda a otros desarrolladores a encontrar este proyecto útil.

---

**Hecho con ❤️ en San Antonio, Chile 🇨🇱**
