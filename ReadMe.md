# Repositorio de Laravel

![PHP Version](https://img.shields.io/badge/PHP-7.4%2B-blue)
![Status](https://img.shields.io/badge/status-completed-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green)

---

## Prerequisito: (ecosistema de desarrollo del lab)

    ▪ PHP versión 8.0 o superior.
    ▪ Composer última versión estable.
    ▪ Laravel Installer o crear proyecto con laravel new composer create-project.
    ▪ Paquete de servidor web local. (Entorno de Desarrollo)(ej.XAMPP, WampServer o Laragon).
    ▪ Servidor web: Apache o Nginx
    ▪ Base de datos MySQL/MariaDB funcionando.
    ▪ Editor de código (Visual Studio Code recomendado).

---

## Instalacion de dependencias

Se instalaron las siguientes dependencias y flujo:
| Dependencia | Comando |
|-------------|---------|
| Composer | `php composer-setup.php --install-dir=bin --filename=composer` |
| Laravel | `composer global require laravel/installer` |
| Laravel UI | `composer require laravel/ui` |

---

## Flujo de proyecto Laravel

| Orden | Paso                            |
|-------|---------------------------------|
| 1     | `laravel new example-app`       |
| 2     | `php artisan serve`             |
| 3     | `composer require laravel/ui`   |
| 4     | `php artisan ui bootstrap`      |
| 5     | `php artisan ui bootstrap --auth` |
| 6     | `npm install`                   |
| 7     | `npm run dev`                   |
| 8     | `php artisan serve`             |

---

## Introducción

El presente laboratorio se desarrolló utilizando el patrón de arquitectura de software MVC (Modelo - Vista - Controlador), implementado mediante el framework Laravel. Este patrón permite separar la lógica de negocio, la interfaz de usuario y el control de flujo de la aplicación, facilitando el mantenimiento y la escalabilidad del código.

---

## Referencias
https://www.php.net/docs.php <br>
https://www.php.net/manual/es/language.control-structures.php
https://www.w3schools.com/php/

--

## Este laboratorio ha sido desarrollado por el estudiante de la **Universidad Tecnológica de Panamá**:

Nombre: Jose Barahona
Correo: jose.barahona7@utp.ac.pa
Curso: Desarrollo de Software VII
Instructor del Laboratorio: Irina Fong.
