# Práctica 2: Arquitectura de Red para ENaIR  

**Autor:** Santiago Bermúdez Blandón  
**ID:** 546563  
**Curso:** Telemática (30135)  

---

## Objetivo:
Diseñar e implementar una arquitectura de red en AWS para la empresa ficticia **ENaIR**, siguiendo los lineamientos de la guía de práctica. El proyecto busca aplicar conceptos de redes corporativas, seguridad perimetral, servicios básicos de infraestructura y documentación de evidencias.  

---

## Contenido del repositorio:
Este repositorio **no mantiene conexión directa con la red implementada en AWS**. Su función es **documental**, con el fin de centralizar y respaldar todas las evidencias de la práctica.  

El contenido incluye:  
- `configs/` → Archivos de configuración (NGINX, BIND, Postfix, Dovecot, etc.).  
- `screenshots/` → Capturas de pantalla de la consola AWS, reglas de seguridad, pruebas y servicios.  
- `scripts/` → Scripts de despliegue y automatización utilizados durante la práctica.  
- `docs/` → Documentación adicional y reporte final en PDF (`examen02_546563.pdf`).
  
---

## Alcance:
La práctica comprende:  
- Creación de una **VPC dual-stack (IPv4/IPv6)** con subredes públicas y privadas.  
- Configuración de **instancias EC2** para servicios web, correo electrónico, DNS, aplicación y base de datos.  
- Implementación de **reglas de seguridad** (Security Groups y firewalls internos UFW/Windows Defender).  
- Despliegue de servicios:  
  - Servidor web (`elgatovolador.enair.com`) con HTTPS.  
  - Servidor de correo y DNS (`elcanariovolador.enair.com`).  
  - Servidor de aplicación/streaming (`elcuervovolador.enair.com`).  
  - Base de datos en subred privada.  
- Configuración de **DNS interno con BIND9** y pruebas de resolución de nombres.  
- Documentación de **evidencias técnicas** (capturas, configuraciones y salidas de comandos).  

---

## Contenido del repositorio:
Este repositorio **no mantiene conexión directa con la red implementada en AWS**. Su función es **documental**, con el fin de centralizar y respaldar todas las evidencias de la práctica.  

El contenido incluye:  
- `configs/` → Archivos de configuración (NGINX, BIND, Postfix, Dovecot, etc.).  
- `screenshots/` → Capturas de pantalla de la consola AWS, reglas de seguridad, pruebas y servicios.  
- `scripts/` → Scripts de despliegue y automatización utilizados durante la práctica.  
- `docs/` → Documentación adicional y reporte final en PDF (`examen02_546563.pdf`).  
