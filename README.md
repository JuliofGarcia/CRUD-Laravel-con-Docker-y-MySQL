# CRUD Laravel con Docker y MySQL

Proyecto base de aplicación web construida con **Laravel** dentro de un entorno contenedorizado con **Docker** y **Docker Compose**, utilizando **PHP 8.3** y **MySQL 8.0**.

---

## Arquitectura del entorno

El proyecto está organizado con una carpeta raíz de infraestructura Docker y el código fuente de Laravel dentro de `src/`:

```text
CRUD-Laravel/
├── Dockerfile        # Imagen personalizada PHP 8.3 CLI + extensiones + Composer
├── compose.yml       # Orquestación de servicios (app y db) y volúmenes
├── README.md         # Documentación del proyecto
└── src/              # Código fuente de la aplicación Laravel
