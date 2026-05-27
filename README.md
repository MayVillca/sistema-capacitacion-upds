# Sistema de Gestión Académica — Centro de Capacitación

Proyecto universitario desarrollado para la materia de Ingeniería de Software.  
Universidad Privada Domingo Savio (UPDS) — Tarija, Bolivia.

---

## Equipo de desarrollo

| Integrante | Rol en el proyecto |
|---|---|
| May Villca | Líder técnica / Backend |
| Micaela [apellido] | Frontend / Interfaces |
| Joel [apellido] | Backend / Base de datos |
| Adriann [apellido] | Frontend / Pruebas |

---

## Descripción del sistema

Sistema web para administrar cursos cortos, docentes, estudiantes,
inscripciones, asistencia por sesión y calificaciones.
Incluye cálculo automático del estado final (Aprobado/Reprobado)
según regla de negocio: asistencia ≥ 80% Y nota final ≥ 51/100.

---

## Tecnologías utilizadas

- **Backend:** Laravel 11 (PHP 8.2)
- **Frontend:** Blade + Bootstrap 5
- **Base de datos:** MySQL (XAMPP)
- **Control de versiones:** Git + GitHub
- **Metodología:** RUP híbrida

---

## Requisitos para ejecutar el proyecto localmente

- PHP 8.2 o superior
- Composer
- MySQL (XAMPP recomendado)
- Git

---

## Instalación local (para cada integrante del equipo)

1. Clonar el repositorio:
git clone https://github.com/MayVillca/sistema-capacitacion-upds.git
2. Entrar a la carpeta:
cd sistema-capacitacion-upds
3. Instalar dependencias:
composer install
4. Copiar el archivo de entorno:
cp .env.example .env
5. Configurar la base de datos en el archivo .env

6. Generar la clave de la aplicación:
php artisan key:generate
7. Ejecutar las migraciones:
php artisan migrate
8. Iniciar el servidor:
php artisan serve

---

## Estructura de ramas

- `main` → versión estable para entrega final  
- `develop` → rama de trabajo diario del equipo

---

## Estado del proyecto

🔄 En desarrollo — Semana 1 de 2