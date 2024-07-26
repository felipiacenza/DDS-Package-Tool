# DDS Package Tool

## 1. Introducción

### Descripción del Proyecto
El **DDS Package Tool** es una aplicación de escritorio desarrollada en Java con el propósito de gestionar y calcular la distribución de paquetes para diferentes tipos de sustancias. La herramienta permite a los usuarios ingresar cantidades de diferentes sustancias, visualizarlas en listas y calcular la división en paquetes de tamaños específicos.

### Objetivos del Proyecto
- Proporcionar una interfaz gráfica para ingresar y visualizar datos sobre diferentes sustancias.
- Calcular la distribución en paquetes de tamaño específico basado en las cantidades ingresadas.
- Facilitar la limpieza y modificación de datos ingresados.

### Tecnologías Utilizadas
- **Lenguaje de Programación:** Java
- **IDE:** NetBeans
- **Sistema de Construcción:** Apache Ant

## 2. Instalación

### Requisitos Previos
- **Java Development Kit (JDK):** Asegúrate de tener instalada la versión del JDK compatible con la versión de Java utilizada en el proyecto.
- **NetBeans IDE:** El proyecto ha sido desarrollado y probado en NetBeans IDE.

### Instrucciones para Clonar el Repositorio
1. Clona el repositorio utilizando Git:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd <DIRECTORIO_DEL_PROYECTO>
    ```

### Instalación de Dependencias
1. Abre el proyecto en NetBeans IDE.
2. El proyecto utiliza Apache Ant para la construcción, así que asegúrate de tener Ant instalado.
3. En NetBeans, puedes construir el proyecto directamente usando la opción de **Build Project** en el menú **Run**.

### Configuración Inicial
No se requieren configuraciones adicionales para ejecutar el proyecto, solo asegúrate de que el JDK y NetBeans estén correctamente instalados.

## 3. Estructura del Proyecto

La estructura del proyecto es la siguiente:

```
DDSPackageTool/
├── build/ # Directorio generado por Ant para archivos construidos
├── src/ # Código fuente del proyecto
│ ├── dominio/ # Paquete que contiene la clase principal
│ │ └── ddpt.java # Clase principal que inicia la aplicación
│ └── interfaz/ # Paquete que contiene la interfaz gráfica
│ └── MainFrame.java # Clase que define la interfaz de usuario
├── build.xml # Archivo de configuración de Ant
└── nbproject/ # Configuración del proyecto para NetBeans
```

## 4. Uso

### Cómo Iniciar la Aplicación
1. Abre NetBeans IDE.
2. Carga el proyecto.
3. Ejecuta la aplicación desde NetBeans utilizando la opción **Run**.

### Navegación Básica en la Aplicación
- **Seleccionar Tipo de Sustancia:** Utiliza los botones de opción para seleccionar el tipo de sustancia.
- **Agregar Cantidades:** Ingresa la cantidad en el campo de texto y haz clic en el botón **OK** para agregarla a la lista correspondiente.
- **Eliminar Elementos:** Selecciona un elemento en la lista y haz clic en el botón **DELETE SELECTED** para eliminarlo.
- **Limpiar Datos:** Haz clic en el botón **CLEAR** para vaciar todas las listas.
- **Calcular Paquetes:** Haz clic en el botón **SEND** para calcular la distribución de paquetes y mostrar el resultado en un cuadro de diálogo.

## 5. Componentes del Proyecto

### Frontend
- **Interfaz de Usuario:** Desarrollada utilizando Swing en Java. La clase `MainFrame` gestiona la interfaz gráfica y las interacciones del usuario.

### Backend
- **Lógica de Aplicación:** Implementada en la clase `MainFrame`, que maneja la lógica para agregar, eliminar y calcular los datos ingresados.

### Base de Datos
- **No se utiliza una base de datos externa en este proyecto.** Los datos se gestionan en memoria utilizando `DefaultListModel` para las listas.

## 6. Contribuciones

Para contribuir al proyecto:
1. Haz un fork del repositorio.
2. Crea una rama para tu característica o corrección de errores (`git checkout -b feature/mi-caracteristica`).
3. Realiza los cambios necesarios y haz commit (`git commit -am 'Añadir nueva característica'`).
4. Envía tus cambios a tu repositorio (`git push origin feature/mi-caracteristica`).
5. Abre un pull request en el repositorio original.

## 7. Licencia
