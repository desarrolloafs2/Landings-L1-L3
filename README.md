# 📚 Plataforma de Convocatorias de Cursos L1 y L3

Este proyecto es una **web informativa** sobre las convocatorias de cursos L1 y L3.  
Su objetivo es facilitar a los usuarios la búsqueda de cursos, la consulta de fechas de inicio, modalidades y horarios, así como el envío de solicitudes mediante un formulario de contacto.
Cada convocatoria se encuentra en una vista diferente, cada una con su ruta.

---

## ✨ Características principales

✅ **Página principal con información general** sobre la formación L1 / L3.  
✅ **Listado de cursos** con tarjetas que muestran:  
- Imagen representativa  
- Nombre del curso  
- Horario y modalidad  
- Fecha de inicio  
- Duración en horas  

✅ **Formulario de contacto** para que los usuarios puedan solicitar información o inscribirse.  
✅ **Diseño responsive**: totalmente adaptable a móviles, tablets y escritorio.  
✅ **Secciones con fondos personalizados** e imágenes oficiales de los organismos colaboradores.  

---

## 🛠️ Tecnologías utilizadas

- **HTML5** y **CSS3** → Maquetación y estilos.  
- **Bootstrap 5** → Sistema de grid y componentes responsive.  
- **Blade (Laravel)** → Plantillas dinámicas y helpers (`asset()`, `url()`).  
- **PHP** → Gestión del formulario y envío de datos.  

---

## 🚀 Instalación y Uso

Sigue estos pasos para instalar y ejecutar el proyecto en tu entorno local con Laragon:

- Clonar el repositorio en el visual Studio Code usando: git@github.com:desarrolloafs2/Landings-L1-L3.git
- Añadir la carpeta del repositorio en C:\laragon\www
- En Laragon nos aparecerá en el apartado de root
- Abrir terminal de Laragon, acceder al proyecto y arrancarlo ejecutando el comando: php artisan serve
- La ruta en el navegador será algo como esto para la convocatoria L1:
  http://127.0.0.1:8000/cursos-gratis-ocupados-ministerio
- Y la ruta en el navegador será algo como esto para la convocatoria L3:
  http://127.0.0.1:8000/cursos-gratis-desempleados-ministerio

