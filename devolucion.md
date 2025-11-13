# Devolución - Examen Recuperatorio
## Control de Versiones con Git y GitHub

**Alumno:** Ignacio Manuel Bernat Maggi  
**Repositorio:** https://github.com/NachoBern2457/recuperatorio-git-Ignacio-Bernat  
**Fecha de evaluación:** 06/11/2025

---

## Evaluación por Criterios

### 1. Creación del repositorio remoto - **1/1 pts**
✅ **Cumplido**
- El repositorio fue creado correctamente con el nombre `recuperatorio-git-Ignacio-Bernat`
- Se incluye el archivo README.md inicial
- La configuración remota apunta correctamente a GitHub

**Observaciones:** Perfecto. El repositorio fue creado correctamente.

---

### 2. Clonación y primera modificación - **2/2 pts**
✅ **Cumplido**
- El repositorio fue clonado correctamente
- Se realizó el commit "1er Agregado readme" que actualiza el README.md con la información del proyecto
- La información del README incluye correctamente:
  - Materia: Electrónica digital 4
  - Tema: Control de Versiones
  - Año: 2025

**Observaciones:** Excelente. La primera modificación en main fue realizada correctamente.

---

### 3. Creación de archivo de código - **3/3 pts**
✅ **Cumplido**
- Se creó la rama `feature-codigo` correctamente
- Se creó el archivo `programa.py` con la función `saludar()` inicial
- Se realizó el commit "Creacion de programa .py"
- Se creó el Pull Request #1 que fue fusionado exitosamente a main

**Observaciones:** Muy bien. El flujo de trabajo con la rama feature y el PR fue correctamente ejecutado.

---

### 4. Sincronización y creación de ramas - **2/2 pts**
✅ **Cumplido**
- Se actualizó la rama main local
- Se crearon las ramas `documentacion` y `actualizacion-codigo`
- Ambas ramas están presentes en el repositorio remoto

**Observaciones:** Correcto. Las ramas fueron creadas según lo solicitado.

---

### 5. Modificación en rama documentación - **2/2 pts**
✅ **Cumplido**
- Se modificó el README.md agregando la sección de documentación (commit "Añadido documentacion README 2")
- Se incluyeron los requisitos (Python 3.x, Git instalado)
- Se agregó la información del autor con nombre y fecha
- Se creó el Pull Request #2 desde la rama documentacion

**Observaciones:** Perfecto. La documentación fue agregada correctamente y el PR fue creado.

---

### 6. Modificación en rama actualizacion-codigo - **2/2 pts**
✅ **Cumplido**
- Se modificó el archivo `programa.py` agregando la función `despedir()`
- Se actualizó el README.md cambiando el título a "# Proyecto de recuperatorio - Versión actualizada"
- Se realizaron los commits correspondientes:
  - "Añadido documentacion README"
  - "Update codigo"
  - "Update codigo2"
- Se creó el Pull Request #3 desde actualizacion-codigo

**Observaciones:** Excelente. Ambos archivos fueron modificados y el PR fue creado correctamente.

---

### 7. Generación y resolución del conflicto - **4/4 pts**
✅ **Cumplido**
- Se generó el conflicto esperado en el archivo README.md entre las ramas documentacion y actualizacion-codigo
- El conflicto fue resuelto manteniendo ambas informaciones de forma coherente
- El README.md final incluye:
  - El título actualizado: "# Proyecto de recuperatorio - Versión actualizada"
  - La información original del proyecto (Materia, Tema, Año)
  - La sección de Documentación con requisitos y autor
- Ambos Pull Requests (#2 y #3) fueron fusionados exitosamente
- El archivo `programa.py` contiene ambas funciones (`saludar()` y `despedir()`)

**Observaciones:** Excelente trabajo en la resolución del conflicto. El contenido final es coherente y completo.

---

### 8. Creación de rama hotfix - **2/2 pts**
✅ **Cumplido**
- Se creó la rama `hotfix-typo` correctamente
- Se modificó el mensaje de la función `saludar()` al texto correcto: "¡Bienvenido al sistema de control de versiones!"
- Se realizó el commit "CHANGE message"
- Se creó y fusionó el Pull Request #4

**Observaciones:** Perfecto. El hotfix fue implementado correctamente con el flujo de trabajo apropiado.

---

### 9. Sincronización final y limpieza - **1/2 pts**
⚠️ **Parcialmente cumplido**
- ✅ La rama main local está actualizada
- ❌ Las ramas locales no fueron eliminadas (todavía existen en el repositorio remoto)
- ✅ El repositorio está correctamente sincronizado con GitHub

**Observaciones:** El repositorio está sincronizado, pero las ramas remotas no fueron eliminadas. Las ramas `feature-codigo`, `documentacion`, `actualizacion-codigo` y `hotfix-typo` aún están en origin. Según las consignas, se debían eliminar las ramas locales después de ser fusionadas.

---

## Resumen de Calificación

| Criterio | Puntaje Obtenido | Puntaje Máximo |
|----------|------------------|----------------|
| 1. Creación del repositorio remoto | 1 | 1 |
| 2. Clonación y primera modificación | 2 | 2 |
| 3. Creación de archivo de código | 3 | 3 |
| 4. Sincronización y creación de ramas | 2 | 2 |
| 5. Modificación en rama documentación | 2 | 2 |
| 6. Modificación en rama actualizacion-codigo | 2 | 2 |
| 7. Generación y resolución del conflicto | 4 | 4 |
| 8. Creación de rama hotfix | 2 | 2 |
| 9. Sincronización final y limpieza | 1 | 2 |

**CALIFICACIÓN FINAL: 19/20 puntos**

---

## Comentarios Generales

El alumno demostró un excelente dominio de Git y GitHub. El trabajo fue realizado de manera prolija y siguiendo correctamente las consignas. Los aspectos destacables son:

**Fortalezas:**
- ✅ Uso correcto del flujo de trabajo con ramas
- ✅ Creación y manejo apropiado de Pull Requests
- ✅ Resolución efectiva del conflicto manteniendo la integridad de la información
- ✅ Commits con mensajes descriptivos
- ✅ Sincronización correcta entre repositorio local y remoto
- ✅ Implementación correcta del hotfix

**Área de mejora:**
- ⚠️ Faltó eliminar las ramas locales después de ser fusionadas (paso 9)

**Recomendación:** Para completar el proceso de limpieza, ejecutar:
```bash
git branch -d feature-codigo documentacion actualizacion-codigo hotfix-typo
git push origin --delete feature-codigo documentacion actualizacion-codigo hotfix-typo
```

---

## Conclusión

Excelente trabajo en general. El alumno ha demostrado comprensión de los conceptos fundamentales de control de versiones y manejo de repositorios Git. Solo faltó completar la limpieza de ramas al final del proceso.

**¡Aprobado con nota destacada!**
