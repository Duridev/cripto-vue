# Cotizador de Criptomonedas con Vue

Este proyecto es una aplicación de **cotización de criptomonedas** creada con **Vue 3**. Utiliza la API de CryptoCompare para mostrar información actualizada sobre los precios de criptomonedas en diferentes monedas. Puedes explorar la demo funcional en el siguiente enlace: [Cotizador de Criptomonedas](https://duridev-cripto-vue.netlify.app/).

## 🚀 Características Principales

- **Selección Dinámica de Monedas y Criptomonedas:**
  - Lista de monedas disponibles: Dólar estadounidense (USD), Peso chileno (CLP), Peso mexicano (MXN), y Euro (EUR).
  - Top 20 criptomonedas por capitalización de mercado, obtenidas dinámicamente desde CryptoCompare.

- **Cotización Detallada:**
  - Precio actual.
  - Precio más alto y más bajo del día.
  - Variación en las últimas 24 horas.
  - Fecha y hora de la última actualización.

- **Interfaz Intuitiva y Reactiva:**
  - Validación de campos de entrada.
  - Indicador de carga mientras se obtiene la información.

## 🔧 Tecnologías Utilizadas

- **Vue 3**: Framework progresivo de JavaScript.
- **Composable (useCripto)**: Manejador reutilizable de la lógica principal del proyecto.
- **CSS**: Estilos personalizados para la interfaz.
- **CryptoCompare API**: Para obtener datos de criptomonedas y realizar cotizaciones.

## 📝 Instalación y Configuración

1. **Clona el repositorio**

```bash
https://github.com/tuusuario/cotizador-criptomonedas.git
```

2. **Instala las dependencias**

```bash
npm install
```

3. **Inicia el servidor de desarrollo**

```bash
npm run dev
```

4. **Abre el proyecto en tu navegador**

```
http://localhost:5173
```

## 🔍 Estructura del Proyecto

### **Componentes**

- `App.vue`: Componente principal donde se coordina toda la lógica.
- `Alerta.vue`: Componente para mostrar mensajes de error.
- `Spinner.vue`: Indicador visual de carga.

### **Composable**

- `useCripto.js`: Manejador reutilizable para:
  - Obtener las criptomonedas desde la API.
  - Realizar la cotización seleccionada por el usuario.
  - Controlar el estado de carga y la visualización del resultado.

## 📊 Demostración

Visita la demo funcional en [Netlify](https://duridev-cripto-vue.netlify.app/).

## 📚 Autor

Desarrollado por [Duridev](https://github.com/duridev).

## 🛠️ Licencia

Este proyecto está licenciado bajo la [MIT License](https://opensource.org/licenses/MIT).


