# 🌟 ¡Lleva tu Pokédex Angular a las Nubes con Azure Static Web Apps! 🌈

### Link de la web en la nube: [https://thankful-smoke-0d3c2e110.6.azurestaticapps.net/](https://thankful-smoke-0d3c2e110.6.azurestaticapps.net/)

✍️ **Autor:** Alberto José Hincapié Martínez   
📂 **Repositorio:** [https://github.com/Albertohincapie11/pokedex-alberto](https://github.com/Albertohincapie11/pokedex-alberto)   
📚 **Asignatura:** Sistemas Distribuidos   
🎓 **Semestre:** 9no semestre - Ingeniería de Sistemas   
📅 **Fecha:** 13/04/2025 

---

## 📦 Proyecto: Pokédex Angular

**Este proyecto consiste en una Pokédex desarrollada con el increíble framework Angular, y la desplegaremos como una Web Estática utilizando Azure Static Web Apps. Esto nos permitirá aprovechar al máximo su escalabilidad, rendimiento optimizado y facilidad de implementación. ¡Una combinación perfecta de tecnología para un proyecto que es tan ágil como un Pikachu en su mejor momento! ⚡️✨**

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

### 2. 🚀 **¡Sube tu Código a GitHub!** 📂

* **Mi repositorio es:** [**pokedex-alberto**](https://github.com/Albertohincapie11/pokedex-alberto) 🐙

***


### 3. ¡Es Hora de Desplegar en Azure! 🚀
* **Accede al [Azure Portal](https://portal.azure.com) 🚪**

* * **Selecciona **"Static Web Apps"** y haz clic en **"Crear"**.**

* **Configura los detalles de tu Web App:**
    * **Nombre de la app:** `pokedex-static` (o el nombre que prefieras 🏷️)
    * **Plan de hosting:** Elige el plan **"Gratis"** para comenzar sin preocupaciones 🆓
    * **Origen del código:** Selecciona **"GitHub"** 🐙

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
