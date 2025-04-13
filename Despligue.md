# 🌟 ¡Lleva tu Pokédex Angular a las Nubes con Azure Static Web Apps! 🌈

### Link de la web en la nube: [https://thankful-smoke-0d3c2e110.6.azurestaticapps.net/](https://thankful-smoke-0d3c2e110.6.azurestaticapps.net/)

✍️ **Autor:** Alberto José Hincapié Martínez 
📂 **Repositorio:** [https://github.com/Albertohincapie11/pokedex-alberto](https://github.com/Albertohincapie11/pokedex-alberto) 
📚 **Asignatura:** Sistemas Distribuidos
🎓 **Semestre:** 9no semestre - Ingeniería de Sistemas  
📅 **Fecha:** 13/04/2025 

**Autor:** Alberto José Hincapié Martínez 👨‍💻  
**Repositorio:** [https://github.com/Albertohincapie11/pokedex-alberto](https://github.com/Albertohincapie11/pokedex-alberto) 🐙  
**Asignatura:** Sistemas Distribuidos 📚  
**Semestre:** 9no semestre - Ingeniería de Sistemas 🎓  
**Fecha:** 13/04/2025 📅

---

## 📦 Proyecto: Pokédex Angular

**Este proyecto es una Pokédex desarrollada con el poderoso framework Angular, y la desplegaremos como una Web Estática usando Azure Static Web Apps para aprovechar su escalabilidad y facilidad de uso.**

---

## 🛠️ Despliegue Paso a Paso en Azure Static Web Apps

**Sigue estos pasos para llevar tu Pokédex al mundo con Azure:**

### 1. Prepara tu Proyecto Angular 💪

**Asegúrate de que tu proyecto Angular funciona correctamente en local. Ejecuta `ng serve` para verificarlo.**

**Construye tu proyecto para producción:**

Abre una terminal desde la carpeta raíz:

1. Navega a la carpeta de tu proyecto:
   `cd "sistemas-distribuidos\poke-dex-lab\source\pokedex-angular\"`

2. Instala las dependencias:
   `npm install`

3. Ejecuta el comando para compilar el proyecto:
   `npm run build`

Esto generará la carpeta mágica `dist/`, que contiene todos los archivos optimizados listos para ser desplegados.

***

### 2.  Sube tu Código a GitHub 📂

* **Mi repositorio es: [https://github.com/Albertohincapie11/pokedex-alberto](https://github.com/Albertohincapie11/pokedex-alberto)**

***

### 3. ¡A Desplegar en Azure! ☁️
* **Ve al [Azure Portal](https://portal.azure.com) 🚪**

* **Busca y selecciona **"Static Web Apps"** y haz clic en **"Crear"**.**

* **Configura los detalles de tu Web App:**
    * **Nombre de la app:** `pokedex-static` (o el nombre que prefieras 🏷️)
    * **Plan de hosting:** Selecciona el plan **"Gratis"** para empezar 🆓
    * **Origen del código:** Elige **"GitHub"** 🐙

* **Detalles del repositorio:**
    * Autoriza Azure para acceder a tu cuenta de GitHub
    * Selecciona tu repositorio (`pokedex-alberto`)
    * Elige la rama que quieres desplegar (normalmente `main` o `master`)

* **Detalles de compilación:**
    * **Ruta de la aplicación:** `dist/pokedex-angular`
    * **Build Presets:** Selecciona "Custom" �️
    * **Output folder:** `dist/pokedex-angular`

* Azure creará automáticamente un **flujo de trabajo de GitHub Actions** 🤖. Este flujo se encargará de compilar y desplegar tu Pokédex cada vez que hagas cambios en la rama seleccionada. 

***

## 🙌 Autor
**Alberto José Hincapié Martínez**  
**Estudiante de Ingeniería de Sistemas**  
**GitHub:** [https://github.com/Albertohincapie11](https://github.com/Albertohincapie11) 
