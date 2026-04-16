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

### Dificultades y soluciones.

#### Dificultad: <br>
Durante el proceso de instalación de laravel no me permitio realizar `laravel new example-app` y me mostraba el siguiente error `command not found: laravel` <br>

#### Solución: <br>
Realice el siguiente comando en la terminal de MacOS: <br>
`/bin/bash -c "$(curl -fsSL https://php.new/install/mac/8.4)"`

---

## Ejecución

<img width="814" height="379" alt="Screenshot 2026-04-16 at 09 46 16" src="https://github.com/user-attachments/assets/27b2ebad-323f-4971-924c-d3b2b6a02a04" />
 <br>
 <img width="1673" height="923" alt="Screenshot 2026-04-16 at 10 21 05" src="https://github.com/user-attachments/assets/04ac29fb-8d43-4729-a05d-02b65df31719" />
 <br>
 <img width="1673" height="923" alt="Screenshot 2026-04-16 at 10 21 13" src="https://github.com/user-attachments/assets/80f9e688-4048-4dc9-81a5-56fd463306a2" />
 <br>
 <img width="1673" height="923" alt="Screenshot 2026-04-16 at 10 21 57" src="https://github.com/user-attachments/assets/c0ecbe05-7e89-48da-aff2-4297b9470389" />


---

## Referencias

[Documentacion de Laravel](https://laravel.com/docs/13.x/installation) <br>
[Video guía para instalar laravel en MacOS](https://www.youtube.com/watch?v=DtUY8J2T-mc)
[Guia de instalacion Laravel general](https://www.youtube.com/watch?v=GZMGyYNq3hE)

---

## Este laboratorio ha sido desarrollado por el estudiante de la **Universidad Tecnológica de Panamá**:

Nombre: Jose Barahona <br>
Correo: jose.barahona7@utp.ac.pa    <br>
Curso: Desarrollo de Software VII   <br>
Instructor del Laboratorio: Irina Fong.
