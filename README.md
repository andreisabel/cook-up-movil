# Proyecto Desarrollo Móvil Semestre 2023/I: Cook Up - Aplicación Móvil de Recetas


---

## 1. Descripción y Propósito

**Cook Up** es una aplicación móvil desarrollada en **Flutter** que funciona como el compañero culinario del blog de recetas. El objetivo principal es ofrecer a los usuarios una **experiencia única e intuitiva** para **compartir, visualizar y descubrir deliciosas recetas** directamente desde su dispositivo.

La aplicación busca:
* Proporcionar a los lectores recetas detalladas, fáciles de seguir y visualmente atractivas.
* Ofrecer una interfaz intuitiva y funciones versátiles para elevar las habilidades en la cocina.

---

## 2. Características Principales

Cook Up implementa:

* **Exploración de Recetas:** Navegación por una extensa biblioteca de recetas clasificadas por categorías (Desayunos, Platillos, Postres, Bebidas y Tips).
* **Interacción Social:** Los usuarios pueden dejar **comentarios y opiniones** sobre las recetas.
* **Creaciones Propias:** Los usuarios tienen la capacidad de **compartir sus propias recetas** con otros entusiastas.
* **Gestión de Perfil:** Sistema de autenticación con soporte para **Inicio de Sesión Social** (Google, Apple). Los usuarios pueden gestionar sus **"Elementos Guardados"** (favoritos).
* 
---

## 3. Arquitectura y Pila Tecnológica

El proyecto sigue una arquitectura **modularizada** y utiliza una pila **BaaS (Backend-as-a-Service)**.

### Tecnologías Fundamentales

| Componente | Herramienta | Propósito Principal |
| :--- | :--- | :--- |
| **Framework** | **Flutter** | Desarrollo de la interfaz de usuario para múltiples plataformas. |
| **Plataforma Visual** | **FlutterFlow** | Utilizada para el desarrollo visual de la aplicación móvil. |
| **Backend / Datos** | **Firebase** | Conjunto de herramientas en la nube para el almacenamiento de datos (**Cloud Firestore**), autenticación (**Firebase Auth**) y almacenamiento de archivos (**Firebase Storage**). |

### Estructura de Directorios (Modularizada)

* `/backend`: Contiene archivos relacionados con la lógica del backend, incluyendo la configuración de Firebase y los modelos de datos.
* `/flutter_flow`: Archivos generados por FlutterFlow, como el tema de la aplicación y utilidades.
* `/screens`: Contiene las diferentes pantallas de la aplicación (inicio, recetas, perfil, etc.).
* `/widgets`: Contiene *widgets* reutilizables utilizados en varias pantallas de la aplicación.

---

## 4. Instalación y Configuración

El proyecto se encuentra en la **Versión 1.0.0+1**.

### 4.1. Pre-requisitos

* **Flutter SDK** (versión >=2.12.0 <3.0.0).
* **Android Studio** o VS Code con el *plugin* de Flutter instalado.
* Acceso a la consola de **Firebase** con el proyecto configurado.

### 4.2. Pasos de Instalación

1.  **Clonar el Repositorio:**
    ```bash
    git clone [URL_DE_TU_REPOSITORIO] cook_up
    cd cook_up
    ```

2.  **Configuración de Dependencias:**
    Ejecuta el siguiente comando para instalar las librerías necesarias.
    ```bash
    flutter pub get
    ```

3.  **Configuración de Firebase:**
    * Asegúrate de que los archivos de configuración de Firebase (`google-services.json` para Android o `GoogleService-Info.plist` para iOS) estén ubicados correctamente en el proyecto.
    * Verifica la inicialización de Firebase dentro del código del *backend*.

4.  **Ejecutar la Aplicación:**
    Inicia un emulador o conecta un dispositivo y ejecuta:
    ```bash
    flutter run
    ```

---

## 6. Autoría 

Este proyecto fue desarrollado por:

* **Andrea Isabel Vega Márquez**
    * Ingeniería en Sistemas Inteligentes
