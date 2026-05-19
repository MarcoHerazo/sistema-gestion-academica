# Sistema de Gestión Académica

## ⚠️ Estado actual
El código fuente del sistema fue perdido accidentalmente. Este repositorio contiene la **estructura de base de datos completa** como evidencia del diseño y funcionalidad del proyecto.

## 📊 Base de datos
- Archivo: `universidad.sql`
- Motor: MySQL / MariaDB
- Tablas: 6 (usuarios, cursos, notas, programas, comentarios, reportes)

## 🗂️ Estructura de datos

### Usuarios
- Autenticación con roles (admin, docente)
- Contraseñas hasheadas con bcrypt

### Cursos
- Asignados a docentes
- Código único por curso

### Notas
- Tres cortes académicos (1, 2, 3)
- Validación de notas entre 1.0 y 5.0

### Comentarios
- Comentarios por estudiante, curso y corte

## 🔧 Cómo importar la base de datos
1. Abrir phpMyAdmin
2. Crear base de datos llamada `universidad`
3. Importar el archivo `universidad.sql`

## 📅 Contexto
Este proyecto fue desarrollado durante mis prácticas profesionales (Enero - Junio 2025) en la Universidad del Sinú.

## 🔄 Próximos pasos
- [ ] Reconstruir el código PHP del sistema
- [ ] Subir versión completa a este repositorio
