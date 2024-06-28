# Arquitectura base react

Este proyecto está configurado con React y Vite, y utiliza una arquitectura modular para organizar el código de manera eficiente y escalable. A continuación se describe la estructura del proyecto y el propósito de cada carpeta y archivo.

## Estructura del Proyecto



### Descripción de las Carpetas y Archivos

- **node_modules**: Contiene todos los paquetes y dependencias instaladas a través de npm.

- **public**: Esta carpeta contiene archivos estáticos que serán servidos directamente. Normalmente se incluye el archivo `index.html` que es el punto de entrada de la aplicación.

- **src**: Carpeta principal que contiene el código fuente de la aplicación React.

  - **assets**: Contiene archivos estáticos como imágenes, fuentes, y otros recursos que serán utilizados en la aplicación.
  
  - **components**: Almacena los componentes reutilizables de la aplicación. Cada componente se define generalmente en un archivo separado.
  
  - **config**: Almacena archivos de configuración y constantes que son utilizadas a lo largo de la aplicación.
  
  - **hooks**: Contiene hooks personalizados de React que encapsulan lógica reutilizable.
  
  - **layout**: Almacena componentes de diseño como encabezados, pies de página, barras laterales, etc., que se utilizan para construir la estructura de la aplicación.
  
  - **router**: Contiene la configuración de enrutamiento de la aplicación, utilizando `react-router-dom` para definir las rutas y navegación.
  
  - **store**: Almacena la configuración de Redux y los slices del estado global de la aplicación. Aquí es donde se configura Redux Toolkit.
  
  - **views**: Contiene los componentes de vista o páginas de la aplicación. Cada archivo en esta carpeta representa una vista completa.
  
  - **App.jsx**: El componente principal de la aplicación. Aquí se define la estructura general de la aplicación y se integran los routers y los providers.
  
  - **main.jsx**: El punto de entrada de la aplicación React. Este archivo renderiza el componente `App` y lo monta en el DOM.

- **.eslintrc.cjs**: Archivo de configuración de ESLint para mantener la consistencia en el estilo de código y detectar errores.

- **.gitignore**: Lista de archivos y carpetas que Git debe ignorar.

- **index.html**: Archivo HTML principal que se sirve desde el servidor y en el que se monta la aplicación React.

- **package-lock.json**: Archivo que contiene la versión exacta de cada paquete instalado para mantener consistencia en las instalaciones.

- **package.json**: Archivo de configuración de npm que incluye los scripts de construcción, las dependencias del proyecto y otra metadata.

- **README.md**: Este archivo, que proporciona una descripción general del proyecto, su estructura y cómo configurarlo.

- **vite.config.js**: Archivo de configuración de Vite, que define cómo se comporta el servidor de desarrollo y cómo se construye la aplicación.

## Configuración del Proyecto

Para iniciar el proyecto localmente, sigue estos pasos:

1. **Clonar el proyecto**:
   ```sh
   git clone <URL>
2. **Entrar dentro del proyect**:
   ```sh
   cd ./path_carpeta_proyecto
3. **Instalar dependencias**:
   ```sh
   npm install
4. **Correr el proyecto localmente**:
   ```sh
   npm run dev
