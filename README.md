# proyecto_final_linux

# Proyecto Final Bash: Automatización de Sistemas y Análisis de Logs

## 🌐 Descripción
Este proyecto tiene como objetivo aplicar los conocimientos adquiridos sobre Bash y administración de sistemas mediante la automatización de tareas reales en un entorno Linux/WSL2. Se abordan la gestión de usuarios, permisos especiales, generación y análisis de logs, y mantenimiento del sistema.

---

## 📂 Estructura del proyecto
```
proyecto_final/
├── main.sh
├── scripts/
│   ├── usuarios.sh
│   └── logs.sh
├── logs/
│   ├── eventos.log
│   ├── informe_eventos.txt
│   └── actividad.log
├── respaldo/
├── usuarios/
│   └── estructura.txt
└── README.md
```

---

## 🔧 Instrucciones de ejecución
1. Clona o copia el proyecto en tu entorno WSL2.
2. Asegúrate de tener permisos sudo.
3. Ejecuta el script principal:
```bash
bash main.sh
```
4. Sigue el menú interactivo para realizar cada acción.

---

## 🔢 Funcionalidades principales
- Creación de usuarios reales (`admin1`, `tecnico1`, `auditor1`) y asignación a grupos.
- Aplicación de permisos SetUID, SetGID, Sticky Bit y ACL.
- Generación de logs en tiempo real con eventos aleatorios.
- Análisis automático de los logs y generación de informe.
- Creación de backups comprimidos de directorios críticos.
- Limpieza de archivos temporales `.tmp`.

---

## 📊 Comandos utilizados
`useradd`, `groupadd`, `usermod`, `chmod`, `chown`, `setfacl`, `getfacl`, `find`, `tar`, `df`, `ls`, `cut`, `grep`, `awk`, `sort`, `uniq`, `wc`, `tail`, `sleep`, `date`

---

## 📜 Ejemplo de salida (informe_eventos.txt)
```
========== INFORME DE EVENTOS ==========
Fecha de análisis: 2025-06-21 17:00:00

Total de errores:
4

Últimos 5 errores:
[2025-06-21 16:58:33] USUARIO: admin1 - EVENTO: ERROR
...

Eventos más frecuentes:
10 INFO
8 LOGIN
6 ERROR
...

Usuario con más actividad:
admin1
```

---

## 📚 Autores
- Nombre y apellidos de los integrantes del grupo.

## 🎓 Centro de formación
- Escuela de Talento Joven Santander Construye 2023