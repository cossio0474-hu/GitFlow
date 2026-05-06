# Nombre del Proyecto

## Descripción

## Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Loigon12/Consultorio.git
   ```

2. Accede a la carpeta del proyecto:
   ```bash
   cd Consultorio
   ```

3. Instala las dependencias del backend (Python):
   ```bash
   cd Backend
   pip install -r requirements.txt
   ```

4. Configura las variables de entorno de Supabase en el archivo correspondiente con tus credenciales (URL y clave pública del proyecto Supabase).

5. Abre el archivo `index.html` en tu navegador o usa un servidor local (como Live Server en VS Code) para visualizar la aplicación.

> También puedes acceder a la versión desplegada en: [https://loigon12.github.io/Consultorio/](https://loigon12.github.io/Consultorio/)

## Uso

La aplicación web del **Consultorio Odontológico - Rosa Ducuara** permite:

1. **Página de inicio (`index.html`):** Visualiza la información del consultorio, los servicios ofrecidos (Odontología General, Ortodoncia, Higiene Oral, Retenedores y Estética Dental), la ubicación y los horarios de atención.

2. **Registro e inicio de sesión:** Desde el botón *Iniciar Sesión* puedes crear una cuenta con tu nombre, documento de identidad, teléfono, correo y contraseña, o acceder con una cuenta existente.

3. **Consultar y agendar citas:** Una vez autenticado, accede al portal de citas para consultar disponibilidad y agendar tu consulta odontológica.

4. **Tratamientos (`Tratamientos.html`):** Explora el catálogo detallado de todos los tratamientos disponibles en el consultorio.

5. **Panel de administración (`admin.html`):** Sección exclusiva para el personal del consultorio para gestionar citas y pacientes.

## Autores

| Usuario | Rol |
|---|---|
| [@Loigon12](https://github.com/Loigon12) | Desarrollador principal / Repositorio |

> Puedes consultar todos los colaboradores del proyecto en la sección [Contributors](https://github.com/Loigon12/Consultorio/graphs/contributors) del repositorio.

## Flujo de trabajo Git

## Evidencias   

Todo esta bien carita feliz

Rama develop:
Se utilizó como rama principal de integración de funcionalidades. Durante el desarrollo del sistema de consultorio, todas las nuevas características se implementaron en ramas independientes y luego se integraron a develop mediante Pull Requests. Esto permitió probar y validar cambios antes de llevarlos a producción.

Ramas feature/:
Para el desarrollo de funcionalidades específicas del sistema, se crearon ramas de tipo feature, por ejemplo:

feature/login (gestión de autenticación de usuarios)
feature/pacientes (módulo de gestión de pacientes)
feature/citas (agendamiento de citas médicas)

Cada una de estas ramas permitió trabajar de forma aislada y luego integrarse a develop.

Rama release/v1.0.0:
Se creó esta rama para preparar la primera versión estable del sistema. En esta etapa se realizaron pruebas finales, corrección de errores menores y validación general del funcionamiento del consultorio antes de su publicación.
Rama hotfix/readme-typo:
Posterior al lanzamiento, se utilizó esta rama para corregir un error menor en la documentación del README sin afectar el flujo principal del desarrollo.
Versionado

El proyecto incluye el tag v1.0.0, el cual representa la primera versión estable del sistema de consultorio. Este tag se generó después de finalizar la rama release/v1.0.0 y fusionarla con la rama principal, asegurando un punto de referencia claro en la evolución del proyecto.

Evidencias

A continuación, se presentan referencias verificables del repositorio:

Repositorio: https://github.com/Loigon12/Consultorio
Ramas: https://github.com/Loigon12/Consultorio/branches
Pull Requests: https://github.com/Loigon12/Consultorio/pulls
Commits: https://github.com/Loigon12/Consultorio/commits