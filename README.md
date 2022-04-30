# 🦄 C# ASP.NET CORE 5 MVC PERMISSION MANAGEMENT

[![Github][github-shield]][github-url]
[![Kofi][kofi-shield]][kofi-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Khanakat][khanakat-shield]][khanakat-url]

## TABLA DE CONTENIDO

* [Acerca del proyecto](#acerca-del-proyecto)
* [Características](#características)
* [Instalación](#instalación)
* [Dependencias](#dependencias)
* [Licencia](#licencia)

## 🔥 ACERCA DEL PROYECTO

Este proyecto es una muestra de gestión de usuarios, inicio de sesión, cierre de sesión, registro, roles y permisos. Se utilizo ``ASP.NET Core 5 MVC`` con C# + Entity Framework + SQLServer.

## ✔️ CARACTERÍSTICAS

- [x] Login
- [x] Logout
- [x] Register
- [x] Roles Manager
- [x] Permissions Manager
- [x] User Roles

## ⚙️ INSTALACIÓN

Clonar el repositorio.

```bash
gh repo clone FernandoCalmet/dotnet-5-aspnet-core-mvc-permission-management
```

Crear la migración de base de datos

```bash
update-database
```

Ejecutar aplicación.

```bash
dotnet run
```

### APUNTES ADICIONALES

No es necesario para la instalación.

Agregar una nueva migración

```bash
add-migration "example name migration"
update-database
```

Eliminar la base de datos

```bash
drop-database
```

## 📥 DEPENDENCIAS

- [Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore](https://www.nuget.org/packages/Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore/) : Middleware ASP.NET Core para páginas de error de Entity Framework Core. Utilice este middleware para detectar y diagnosticar errores con las migraciones de Entity Framework Core.
- [Microsoft.AspNetCore.Identity.EntityFrameworkCore](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity.EntityFrameworkCore/) : Proveedor de identidad ASP.NET Core que usa Entity Framework Core.
- [Microsoft.AspNetCore.Identity.UI](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity.UI/) : La interfaz de usuario de identidad de ASP.NET Core es la interfaz de usuario integrada de Razor Pages predeterminada para el marco de identidad de ASP.NET Core.
- [Microsoft.EntityFrameworkCore.SqlServer](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/) : Proveedor de base de datos de Microsoft SQL Server para Entity Framework Core.
- [Microsoft.EntityFrameworkCore.Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools/) : Entity Framework Core Tools para la consola del administrador de paquetes NuGet en Visual Studio.

## 📄 LICENCIA

Este proyecto está bajo la Licencia (Licencia MIT) - mire el archivo [LICENSE](LICENSE) para más detalles.

## ⭐️ DAME UNA ESTRELLA

Si esta Implementación le resultó útil o la utilizó en sus Proyectos, déle una estrella. ¡Gracias! O, si te sientes realmente generoso, [¡Apoye el proyecto con una pequeña contribución!](https://ko-fi.com/fernandocalmet).

<!--- reference style links --->
[github-shield]: https://img.shields.io/badge/-@fernandocalmet-%23181717?style=flat-square&logo=github
[github-url]: https://github.com/fernandocalmet
[kofi-shield]: https://img.shields.io/badge/-@fernandocalmet-%231DA1F2?style=flat-square&logo=kofi&logoColor=ff5f5f
[kofi-url]: https://ko-fi.com/fernandocalmet
[linkedin-shield]: https://img.shields.io/badge/-fernandocalmet-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernandocalmet
[linkedin-url]: https://www.linkedin.com/in/fernandocalmet
[khanakat-shield]: https://img.shields.io/badge/khanakat.com-brightgreen?style=flat-square
[khanakat-url]: https://khanakat.com
