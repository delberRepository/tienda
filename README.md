# 🛍️ Proyecto WordPress Local: Tienda Online

Este repositorio contiene un sitio WordPress desarrollado localmente usando **XAMPP**, **PHPMyAdmin**, **WordPress** y **WooCommerce**.  
El proyecto simula una tienda online con fines de aprendizaje y portfolio profesional.

---

## 🚀 Tecnologías utilizadas

- WordPress 6.x
- WooCommerce
- XAMPP (Apache + MySQL)
- PHPMyAdmin
- PHP 8.x
- HTML / CSS / JS personalizados
- Plugins y temas adaptados

---

## 🧩 Estructura del repositorio

Incluye:

- Archivos base de WordPress
- Temas y plugins activos en `wp-content/`
- Archivo `wp-config-sample.php` como plantilla de configuración
- `.gitignore` adaptado para proteger datos sensibles y archivos locales

---

## ⚙️ Cómo ponerlo en marcha en tu equipo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/delberRepository/tiendaDiscos

2. Crea una base de datos vacía en tu entorno local (ej. phpMyAdmin).
3. Copia el archivo `wp-config-sample.php` y renómbralo como `wp-config.php`.
4. Edita ese archivo con tus datos de base de datos locales:

    define( 'DB_NAME', 'nombre_de_tu_base_de_datos' );
    define( 'DB_USER', 'root' );
    define( 'DB_PASSWORD', '' ); // o la que uses en XAMPP
    define( 'DB_HOST', 'localhost' );

5. Importa el archivo `.sql` con la base de datos del proyecto.
6. Inicia XAMPP (Apache y MySQL) 
7. Ve a : http://localhost/wordpress/
