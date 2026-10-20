# Kallpa SIG - Prototipo de la versión 2.0

Prototipo navegable del Sistema de Información Gerencial para la gestión y asignación de recursos en una empresa de transporte de personal minero (curso Tópicos en Sistemas de Información, UNA Puno).

Incluye los módulos de la versión 1.0 y las mejoras M0 a M7. Los datos son ficticios y se guardan en el navegador.

## Ver en línea
GitHub Pages: https://fiorelavilchez.github.io/psistema-control/

## Ejecutar con Docker
```
docker build -t kallpa-sig .
docker run -d -p 8080:80 kallpa-sig
```
Abrir http://localhost:8080
