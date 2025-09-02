# 🛍️ Proyecto WordPress Local: Tienda Online

Este repositorio contiene un sitio WordPress desarrollado localmente usando **XAMPP**, **PHPMyAdmin**, **WordPress** y **WooCommerce**.  
El proyecto simula una tienda online con fines de aprendizaje y portfolio profesional.

---
<img width="1338" height="616" alt="Captura de pantalla 2025-09-02 a las 18 15 58" src="https://github.com/user-attachments/assets/cc294486-24ad-4afd-b570-7bc9f7496fd6" />
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


<img width="1331" height="604" alt="Captura de pantalla 2025-09-02 a las 18 16 16" src="https://github.com/user-attachments/assets/a4cfd011-f21d-4a68-a053-111b2090a8df" />
<img width="1108" height="607" alt="Captura de pantalla 2025-09-02 a las 18 16 38" src="https://github.com/user-attachments/assets/b84dc5a7-25f8-4bd4-8dda-cd921d91b54c" />
<img width="1257" height="609" alt="Captura de pantalla 2025-09-02 a las 18 17 19" src="https://github.com/user-attachments/assets/6a09b0f2-9e08-44ce-bc84-e218e4eacd7e" />



