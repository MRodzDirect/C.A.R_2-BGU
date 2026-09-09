# 📦 Registro de Auditoría de Git (Commits y Push)

> Salidas de shell de los commits automáticos al cierre de jornada o sincronización manual.

### 🚀 Git Auto-Commit Inicial: `2026-09-08 00:00:00`
> **Mensaje:** `Auto-update SFMS: Configuración inicial v1.3`  
> **Resumen:** Módulos de trazabilidad, sanitización, staging y PostgreSQL integrados.

```shell
$ git status
On branch master
nothing to commit, working tree clean
```
---

### 🚀 Git Auto-Commit: `2026-09-08 01:15:15`
> **Mensaje:** `Auto-update SFMS: 2026-09-08 01:15:09`  
> **Resumen:** Sincronización automática periódica

```shell
$ git add .
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/eliminaciones.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/git_audit.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/movimientos.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/timeline.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Biologia/NOTAS_BIOLOGIA/Promedios-Finales/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Biologia/NOTAS_BIOLOGIA/Trimestrales/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Biologia/Septiembre/Recursos/Transcriptos/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Biologia/Septiembre/Tareas/Calificado/Grupal/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Biologia/Septiembre/Tareas/Calificado/Individual/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Biologia/Septiembre/Tareas/Examen/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Historia/Septiembre/Tareas/.gitkeep', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'PRESENTAR_HOY/.gitkeep', LF will be replaced by CRLF the next time Git touches it


$ git commit -m "Auto-update SFMS: 2026-09-08 01:15:09"
[main 28b9567] Auto-update SFMS: 2026-09-08 01:15:09
 64 files changed, 1671 insertions(+)
 create mode 100644 .audit/eliminaciones.md
 create mode 100644 .audit/git_audit.md
 create mode 100644 .audit/movimientos.md
 create mode 100644 .audit/timeline.md
 create mode 100644 .metadata/General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md.metadata.json
 create mode 100644 .sfms_data/sfms_postgres_ledger.db
 create mode 100644 Biologia/NOTAS_BIOLOGIA/Promedios-Finales/.gitkeep
 create mode 100644 Biologia/NOTAS_BIOLOGIA/Trimestrales/.gitkeep
 create mode 100644 Biologia/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Biologia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Biologia/Septiembre/Tareas/Calificado/Individual/.gitkeep
 rename Biologia/Septiembre/Tareas/Diagnosticas/{ => .metadata}/.metadata (100%)
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.zip.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.zip.metadata.json
 rename Biologia/Septiembre/Tareas/Diagnosticas/{EVALUACION DIAGNOSTICA BIOLOGIA 07-09-2026_C.A.R.pdf => Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename Biologia/Septiembre/Tareas/Diagnosticas/{Tarea Diagnostica Biologia - Correo Registrado cesarisra.png => Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png} (100%)
 rename Biologia/Septiembre/Tareas/Diagnosticas/{EVALUACION DIAGNOSTICA BIOLOGIA 07-09-2026.mthml.zip => Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.zip} (100%)
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 Biologia/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Tareas/Diagnosticas/.metadata/Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Ciudadania/Septiembre/Tareas/Diagnosticas/.metadata/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Ciudadania/Septiembre/Tareas/Diagnosticas/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 Ciudadania/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Diagnosticas/.metadata/Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Diagnosticas/.metadata/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Diagnosticas/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 Filosofia/Septiembre/Tareas/Diagnosticas/.metadata/Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Filosofia/Septiembre/Tareas/Diagnosticas/.metadata/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Filosofia/Septiembre/Tareas/Diagnosticas/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 Filosofia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md
 create mode 100644 Historia/Septiembre/Tareas/.gitkeep
 create mode 100644 Historia/Septiembre/Tareas/Diagnosticas/.metadata/Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Historia/Septiembre/Tareas/Diagnosticas/.metadata/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Historia/Septiembre/Tareas/Diagnosticas/Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename "Historia/Septiembre/Tareas/Diagnosticas/EVALUACI\303\223N_DIAGN\303\223STICA HISTORIA 07-09-2026_C.A.R.pdf" => Historia/Septiembre/Tareas/Diagnosticas/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf (98%)
 create mode 100644 Historia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 Ingles/Septiembre/Tareas/Diagnosticas/.metadata/Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Ingles/Septiembre/Tareas/Diagnosticas/.metadata/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Ingles/Septiembre/Tareas/Diagnosticas/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 Ingles/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 Lenguaje/Septiembre/Tareas/Diagnosticas/.metadata/Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Lenguaje/Septiembre/Tareas/Diagnosticas/.metadata/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 Lenguaje/Septiembre/Tareas/Diagnosticas/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 Lenguaje/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
 create mode 100644 PRESENTAR_HOY/.gitkeep
 create mode 100644 PRESENTAR_HOY/08_09_2026/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 PRESENTAR_HOY/08_09_2026/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png
 create mode 100644 PRESENTAR_HOY/08_09_2026/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 PRESENTAR_HOY/08_09_2026/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 PRESENTAR_HOY/08_09_2026/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 PRESENTAR_HOY/08_09_2026/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 PRESENTAR_HOY/08_09_2026/INDEX.md
 create mode 100644 PRESENTAR_HOY/08_09_2026/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 PRESENTAR_HOY/08_09_2026/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf
 create mode 100644 REGISTRO_CARPETA.md
 create mode 100644 RESUMEN_ARCHIVOS_2BGU-leer-facil.md
 create mode 100644 RESUMEN_ARCHIVOS_2BGU.md


$ git push
To https://github.com/MRodzDirect/C.A.R_2-BGU
   e89b145..28b9567  main -> main
```
---
### 🚀 Git Auto-Commit: `2026-09-08 01:32:53`
> **Mensaje:** `Auto-update SFMS: 2026-09-08 01:32:49`  
> **Resumen:** Sincronización automática periódica

```shell
$ git add .
warning: in the working copy of '.audit/git_audit.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/timeline.md', LF will be replaced by CRLF the next time Git touches it


$ git commit -m "Auto-update SFMS: 2026-09-08 01:32:49"
[main a244de3] Auto-update SFMS: 2026-09-08 01:32:49
 257 files changed, 348 insertions(+), 687 deletions(-)
 create mode 100644 "Acompa\303\261amiento Integral/NOTAS_ACOMPA\303\221AMIENTO_INTEGRAL/Promedios-Finales/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/NOTAS_ACOMPA\303\221AMIENTO_INTEGRAL/Trimestrales/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Recursos/Audios/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Recursos/Lecturas/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Recursos/Libros/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Recursos/Other/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Recursos/Transcriptos/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Recursos/Videos/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Tareas/Calificado/Grupal/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Tareas/Calificado/Individual/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Tareas/Diagnosticas/.gitkeep"
 create mode 100644 "Acompa\303\261amiento Integral/Septiembre/Tareas/Examen/.gitkeep"
 delete mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 delete mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png.metadata.json
 delete mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.zip.metadata.json
 rename Biologia/Septiembre/Tareas/Diagnosticas/{Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename Biologia/Septiembre/Tareas/Diagnosticas/{Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png => Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png} (100%)
 rename Biologia/Septiembre/Tareas/Diagnosticas/{Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.zip => Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.zip} (100%)
 create mode 100644 Ciencias Naturales/NOTAS_CIENCIAS_NATURALES/Promedios-Finales/.gitkeep
 create mode 100644 Ciencias Naturales/NOTAS_CIENCIAS_NATURALES/Trimestrales/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Ciencias Naturales/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Ciencias Sociales/NOTAS_CIENCIAS_SOCIALES/Promedios-Finales/.gitkeep
 create mode 100644 Ciencias Sociales/NOTAS_CIENCIAS_SOCIALES/Trimestrales/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Ciencias Sociales/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Ciudadania/NOTAS_CIUDADANIA/Promedios-Finales/.gitkeep
 create mode 100644 Ciudadania/NOTAS_CIUDADANIA/Trimestrales/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Ciudadania/Septiembre/Tareas/Diagnosticas/.gitkeep
 delete mode 100644 Ciudadania/Septiembre/Tareas/Diagnosticas/.metadata/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename Ciudadania/Septiembre/Tareas/Diagnosticas/{Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 create mode 100644 Ciudadania/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Cultura Fisica/NOTAS_CULTURA_FISICA/Promedios-Finales/.gitkeep
 create mode 100644 Cultura Fisica/NOTAS_CULTURA_FISICA/Trimestrales/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Diagnosticas/.gitkeep
 delete mode 100644 Cultura Fisica/Septiembre/Tareas/Diagnosticas/.metadata/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename Cultura Fisica/Septiembre/Tareas/Diagnosticas/{Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 create mode 100644 Cultura Fisica/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 ECA/NOTAS_ECA/Promedios-Finales/.gitkeep
 create mode 100644 ECA/NOTAS_ECA/Trimestrales/.gitkeep
 create mode 100644 ECA/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 ECA/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 ECA/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 ECA/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 ECA/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 ECA/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 ECA/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 ECA/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 ECA/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 ECA/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Emprendimiento y Gestion/NOTAS_EMPRENDIMIENTO_Y_GESTION/Promedios-Finales/.gitkeep
 create mode 100644 Emprendimiento y Gestion/NOTAS_EMPRENDIMIENTO_Y_GESTION/Trimestrales/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Emprendimiento y Gestion/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Estudios Sociales/NOTAS_ESTUDIOS_SOCIALES/Promedios-Finales/.gitkeep
 create mode 100644 Estudios Sociales/NOTAS_ESTUDIOS_SOCIALES/Trimestrales/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Estudios Sociales/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Filosofia/NOTAS_FILOSOFIA/Promedios-Finales/.gitkeep
 create mode 100644 Filosofia/NOTAS_FILOSOFIA/Trimestrales/.gitkeep
 create mode 100644 Filosofia/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Filosofia/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Filosofia/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Filosofia/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Filosofia/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Filosofia/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Filosofia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Filosofia/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Filosofia/Septiembre/Tareas/Diagnosticas/.gitkeep
 delete mode 100644 Filosofia/Septiembre/Tareas/Diagnosticas/.metadata/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename Filosofia/Septiembre/Tareas/Diagnosticas/{Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 create mode 100644 Filosofia/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Fisica/NOTAS_FISICA/Promedios-Finales/.gitkeep
 create mode 100644 Fisica/NOTAS_FISICA/Trimestrales/.gitkeep
 create mode 100644 Fisica/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Fisica/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Fisica/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Fisica/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Fisica/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Fisica/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Fisica/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Fisica/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Fisica/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Fisica/Septiembre/Tareas/Examen/.gitkeep
 delete mode 100644 General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md
 create mode 100644 Historia/NOTAS_HISTORIA/Promedios-Finales/.gitkeep
 create mode 100644 Historia/NOTAS_HISTORIA/Trimestrales/.gitkeep
 create mode 100644 Historia/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Historia/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Historia/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Historia/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Historia/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Historia/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Historia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Historia/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Historia/Septiembre/Tareas/Diagnosticas/.gitkeep
 delete mode 100644 Historia/Septiembre/Tareas/Diagnosticas/.metadata/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename Historia/Septiembre/Tareas/Diagnosticas/{Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 create mode 100644 Historia/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Ingles/NOTAS_INGLES/Promedios-Finales/.gitkeep
 create mode 100644 Ingles/NOTAS_INGLES/Trimestrales/.gitkeep
 create mode 100644 Ingles/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Ingles/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Ingles/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Ingles/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Ingles/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Ingles/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Ingles/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Ingles/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Ingles/Septiembre/Tareas/Diagnosticas/.gitkeep
 delete mode 100644 Ingles/Septiembre/Tareas/Diagnosticas/.metadata/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename Ingles/Septiembre/Tareas/Diagnosticas/{Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 create mode 100644 Ingles/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Lenguaje/NOTAS_LENGUAJE/Promedios-Finales/.gitkeep
 create mode 100644 Lenguaje/NOTAS_LENGUAJE/Trimestrales/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Lenguaje/Septiembre/Tareas/Diagnosticas/.gitkeep
 delete mode 100644 Lenguaje/Septiembre/Tareas/Diagnosticas/.metadata/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 rename Lenguaje/Septiembre/Tareas/Diagnosticas/{Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 create mode 100644 Lenguaje/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Matematicas/NOTAS_MATEMATICAS/Promedios-Finales/.gitkeep
 create mode 100644 Matematicas/NOTAS_MATEMATICAS/Trimestrales/.gitkeep
 create mode 100644 Matematicas/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Matematicas/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Matematicas/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Matematicas/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Matematicas/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Matematicas/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Matematicas/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Matematicas/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Matematicas/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Matematicas/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 PPE-2/NOTAS_PPE_2/Promedios-Finales/.gitkeep
 create mode 100644 PPE-2/NOTAS_PPE_2/Trimestrales/.gitkeep
 create mode 100644 PPE-2/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 PPE-2/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 PPE-2/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 PPE-2/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 PPE-2/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 PPE-2/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 PPE-2/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 PPE-2/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 PPE-2/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 PPE-2/Septiembre/Tareas/Examen/.gitkeep
 rename PRESENTAR_HOY/08_09_2026/{Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png => Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf => Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf} (100%)
 rename PRESENTAR_HOY/08_09_2026/{INDEX.md => PRESENTAR_HOY.md} (100%)
 create mode 100644 Proyecto-Interdisciplinario-2BGU/NOTAS_PROYECTO_INTERDISCIPLINARIO_2BGU/Promedios-Finales/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/NOTAS_PROYECTO_INTERDISCIPLINARIO_2BGU/Trimestrales/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Examen/.gitkeep
 create mode 100644 Quimica/NOTAS_QUIMICA/Promedios-Finales/.gitkeep
 create mode 100644 Quimica/NOTAS_QUIMICA/Trimestrales/.gitkeep
 create mode 100644 Quimica/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Quimica/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Quimica/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Quimica/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Quimica/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Quimica/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Quimica/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Quimica/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Quimica/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Quimica/Septiembre/Tareas/Examen/.gitkeep
 delete mode 100644 REGISTRO_CARPETA.md
 create mode 100644 Sociologia/NOTAS_SOCIOLOGIA/Promedios-Finales/.gitkeep
 create mode 100644 Sociologia/NOTAS_SOCIOLOGIA/Trimestrales/.gitkeep
 create mode 100644 Sociologia/Septiembre/Recursos/Audios/.gitkeep
 create mode 100644 Sociologia/Septiembre/Recursos/Lecturas/.gitkeep
 create mode 100644 Sociologia/Septiembre/Recursos/Libros/.gitkeep
 create mode 100644 Sociologia/Septiembre/Recursos/Other/.gitkeep
 create mode 100644 Sociologia/Septiembre/Recursos/Transcriptos/.gitkeep
 create mode 100644 Sociologia/Septiembre/Recursos/Videos/.gitkeep
 create mode 100644 Sociologia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
 create mode 100644 Sociologia/Septiembre/Tareas/Calificado/Individual/.gitkeep
 create mode 100644 Sociologia/Septiembre/Tareas/Diagnosticas/.gitkeep
 create mode 100644 Sociologia/Septiembre/Tareas/Examen/.gitkeep


$ git push
To https://github.com/MRodzDirect/C.A.R_2-BGU
   28b9567..a244de3  main -> main
```

#### 📊 Resumen de Diferencias (Diff de Archivos)
```shell
$ git diff --name-status HEAD~1 HEAD
M	.audit/eliminaciones.md
M	.audit/git_audit.md
M	.audit/timeline.md
A	"Acompa\303\261amiento Integral/NOTAS_ACOMPA\303\221AMIENTO_INTEGRAL/Promedios-Finales/.gitkeep"
A	"Acompa\303\261amiento Integral/NOTAS_ACOMPA\303\221AMIENTO_INTEGRAL/Trimestrales/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Recursos/Audios/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Recursos/Lecturas/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Recursos/Libros/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Recursos/Other/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Recursos/Transcriptos/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Recursos/Videos/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Tareas/Calificado/Grupal/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Tareas/Calificado/Individual/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Tareas/Diagnosticas/.gitkeep"
A	"Acompa\303\261amiento Integral/Septiembre/Tareas/Examen/.gitkeep"
D	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
D	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png.metadata.json
D	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.zip.metadata.json
R100	Biologia/Septiembre/Tareas/Diagnosticas/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Biologia/Septiembre/Tareas/Diagnosticas/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	Biologia/Septiembre/Tareas/Diagnosticas/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png	Biologia/Septiembre/Tareas/Diagnosticas/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png
R100	Biologia/Septiembre/Tareas/Diagnosticas/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.zip	Biologia/Septiembre/Tareas/Diagnosticas/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.zip
M	Biologia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Ciencias Naturales/NOTAS_CIENCIAS_NATURALES/Promedios-Finales/.gitkeep
A	Ciencias Naturales/NOTAS_CIENCIAS_NATURALES/Trimestrales/.gitkeep
A	Ciencias Naturales/Septiembre/Recursos/Audios/.gitkeep
A	Ciencias Naturales/Septiembre/Recursos/Lecturas/.gitkeep
A	Ciencias Naturales/Septiembre/Recursos/Libros/.gitkeep
A	Ciencias Naturales/Septiembre/Recursos/Other/.gitkeep
A	Ciencias Naturales/Septiembre/Recursos/Transcriptos/.gitkeep
A	Ciencias Naturales/Septiembre/Recursos/Videos/.gitkeep
A	Ciencias Naturales/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Ciencias Naturales/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Ciencias Naturales/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Ciencias Naturales/Septiembre/Tareas/Examen/.gitkeep
A	Ciencias Sociales/NOTAS_CIENCIAS_SOCIALES/Promedios-Finales/.gitkeep
A	Ciencias Sociales/NOTAS_CIENCIAS_SOCIALES/Trimestrales/.gitkeep
A	Ciencias Sociales/Septiembre/Recursos/Audios/.gitkeep
A	Ciencias Sociales/Septiembre/Recursos/Lecturas/.gitkeep
A	Ciencias Sociales/Septiembre/Recursos/Libros/.gitkeep
A	Ciencias Sociales/Septiembre/Recursos/Other/.gitkeep
A	Ciencias Sociales/Septiembre/Recursos/Transcriptos/.gitkeep
A	Ciencias Sociales/Septiembre/Recursos/Videos/.gitkeep
A	Ciencias Sociales/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Ciencias Sociales/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Ciencias Sociales/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Ciencias Sociales/Septiembre/Tareas/Examen/.gitkeep
A	Ciudadania/NOTAS_CIUDADANIA/Promedios-Finales/.gitkeep
A	Ciudadania/NOTAS_CIUDADANIA/Trimestrales/.gitkeep
A	Ciudadania/Septiembre/Recursos/Audios/.gitkeep
A	Ciudadania/Septiembre/Recursos/Lecturas/.gitkeep
A	Ciudadania/Septiembre/Recursos/Libros/.gitkeep
A	Ciudadania/Septiembre/Recursos/Other/.gitkeep
A	Ciudadania/Septiembre/Recursos/Transcriptos/.gitkeep
A	Ciudadania/Septiembre/Recursos/Videos/.gitkeep
A	Ciudadania/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Ciudadania/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Ciudadania/Septiembre/Tareas/Diagnosticas/.gitkeep
D	Ciudadania/Septiembre/Tareas/Diagnosticas/.metadata/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
R100	Ciudadania/Septiembre/Tareas/Diagnosticas/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Ciudadania/Septiembre/Tareas/Diagnosticas/Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
M	Ciudadania/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Ciudadania/Septiembre/Tareas/Examen/.gitkeep
A	Cultura Fisica/NOTAS_CULTURA_FISICA/Promedios-Finales/.gitkeep
A	Cultura Fisica/NOTAS_CULTURA_FISICA/Trimestrales/.gitkeep
A	Cultura Fisica/Septiembre/Recursos/Audios/.gitkeep
A	Cultura Fisica/Septiembre/Recursos/Lecturas/.gitkeep
A	Cultura Fisica/Septiembre/Recursos/Libros/.gitkeep
A	Cultura Fisica/Septiembre/Recursos/Other/.gitkeep
A	Cultura Fisica/Septiembre/Recursos/Transcriptos/.gitkeep
A	Cultura Fisica/Septiembre/Recursos/Videos/.gitkeep
A	Cultura Fisica/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Cultura Fisica/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Cultura Fisica/Septiembre/Tareas/Diagnosticas/.gitkeep
D	Cultura Fisica/Septiembre/Tareas/Diagnosticas/.metadata/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
R100	Cultura Fisica/Septiembre/Tareas/Diagnosticas/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Cultura Fisica/Septiembre/Tareas/Diagnosticas/Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
M	Cultura Fisica/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Cultura Fisica/Septiembre/Tareas/Examen/.gitkeep
A	ECA/NOTAS_ECA/Promedios-Finales/.gitkeep
A	ECA/NOTAS_ECA/Trimestrales/.gitkeep
A	ECA/Septiembre/Recursos/Audios/.gitkeep
A	ECA/Septiembre/Recursos/Lecturas/.gitkeep
A	ECA/Septiembre/Recursos/Libros/.gitkeep
A	ECA/Septiembre/Recursos/Other/.gitkeep
A	ECA/Septiembre/Recursos/Transcriptos/.gitkeep
A	ECA/Septiembre/Recursos/Videos/.gitkeep
A	ECA/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	ECA/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	ECA/Septiembre/Tareas/Diagnosticas/.gitkeep
A	ECA/Septiembre/Tareas/Examen/.gitkeep
A	Emprendimiento y Gestion/NOTAS_EMPRENDIMIENTO_Y_GESTION/Promedios-Finales/.gitkeep
A	Emprendimiento y Gestion/NOTAS_EMPRENDIMIENTO_Y_GESTION/Trimestrales/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Recursos/Audios/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Recursos/Lecturas/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Recursos/Libros/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Recursos/Other/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Recursos/Transcriptos/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Recursos/Videos/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Emprendimiento y Gestion/Septiembre/Tareas/Examen/.gitkeep
A	Estudios Sociales/NOTAS_ESTUDIOS_SOCIALES/Promedios-Finales/.gitkeep
A	Estudios Sociales/NOTAS_ESTUDIOS_SOCIALES/Trimestrales/.gitkeep
A	Estudios Sociales/Septiembre/Recursos/Audios/.gitkeep
A	Estudios Sociales/Septiembre/Recursos/Lecturas/.gitkeep
A	Estudios Sociales/Septiembre/Recursos/Libros/.gitkeep
A	Estudios Sociales/Septiembre/Recursos/Other/.gitkeep
A	Estudios Sociales/Septiembre/Recursos/Transcriptos/.gitkeep
A	Estudios Sociales/Septiembre/Recursos/Videos/.gitkeep
A	Estudios Sociales/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Estudios Sociales/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Estudios Sociales/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Estudios Sociales/Septiembre/Tareas/Examen/.gitkeep
A	Filosofia/NOTAS_FILOSOFIA/Promedios-Finales/.gitkeep
A	Filosofia/NOTAS_FILOSOFIA/Trimestrales/.gitkeep
A	Filosofia/Septiembre/Recursos/Audios/.gitkeep
A	Filosofia/Septiembre/Recursos/Lecturas/.gitkeep
A	Filosofia/Septiembre/Recursos/Libros/.gitkeep
A	Filosofia/Septiembre/Recursos/Other/.gitkeep
A	Filosofia/Septiembre/Recursos/Transcriptos/.gitkeep
A	Filosofia/Septiembre/Recursos/Videos/.gitkeep
A	Filosofia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Filosofia/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Filosofia/Septiembre/Tareas/Diagnosticas/.gitkeep
D	Filosofia/Septiembre/Tareas/Diagnosticas/.metadata/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
R100	Filosofia/Septiembre/Tareas/Diagnosticas/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Filosofia/Septiembre/Tareas/Diagnosticas/Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
M	Filosofia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Filosofia/Septiembre/Tareas/Examen/.gitkeep
A	Fisica/NOTAS_FISICA/Promedios-Finales/.gitkeep
A	Fisica/NOTAS_FISICA/Trimestrales/.gitkeep
A	Fisica/Septiembre/Recursos/Audios/.gitkeep
A	Fisica/Septiembre/Recursos/Lecturas/.gitkeep
A	Fisica/Septiembre/Recursos/Libros/.gitkeep
A	Fisica/Septiembre/Recursos/Other/.gitkeep
A	Fisica/Septiembre/Recursos/Transcriptos/.gitkeep
A	Fisica/Septiembre/Recursos/Videos/.gitkeep
A	Fisica/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Fisica/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Fisica/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Fisica/Septiembre/Tareas/Examen/.gitkeep
D	General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md
A	Historia/NOTAS_HISTORIA/Promedios-Finales/.gitkeep
A	Historia/NOTAS_HISTORIA/Trimestrales/.gitkeep
A	Historia/Septiembre/Recursos/Audios/.gitkeep
A	Historia/Septiembre/Recursos/Lecturas/.gitkeep
A	Historia/Septiembre/Recursos/Libros/.gitkeep
A	Historia/Septiembre/Recursos/Other/.gitkeep
A	Historia/Septiembre/Recursos/Transcriptos/.gitkeep
A	Historia/Septiembre/Recursos/Videos/.gitkeep
A	Historia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Historia/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Historia/Septiembre/Tareas/Diagnosticas/.gitkeep
D	Historia/Septiembre/Tareas/Diagnosticas/.metadata/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
R100	Historia/Septiembre/Tareas/Diagnosticas/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Historia/Septiembre/Tareas/Diagnosticas/Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
M	Historia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Historia/Septiembre/Tareas/Examen/.gitkeep
A	Ingles/NOTAS_INGLES/Promedios-Finales/.gitkeep
A	Ingles/NOTAS_INGLES/Trimestrales/.gitkeep
A	Ingles/Septiembre/Recursos/Audios/.gitkeep
A	Ingles/Septiembre/Recursos/Lecturas/.gitkeep
A	Ingles/Septiembre/Recursos/Libros/.gitkeep
A	Ingles/Septiembre/Recursos/Other/.gitkeep
A	Ingles/Septiembre/Recursos/Transcriptos/.gitkeep
A	Ingles/Septiembre/Recursos/Videos/.gitkeep
A	Ingles/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Ingles/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Ingles/Septiembre/Tareas/Diagnosticas/.gitkeep
D	Ingles/Septiembre/Tareas/Diagnosticas/.metadata/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
R100	Ingles/Septiembre/Tareas/Diagnosticas/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Ingles/Septiembre/Tareas/Diagnosticas/Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
M	Ingles/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Ingles/Septiembre/Tareas/Examen/.gitkeep
A	Lenguaje/NOTAS_LENGUAJE/Promedios-Finales/.gitkeep
A	Lenguaje/NOTAS_LENGUAJE/Trimestrales/.gitkeep
A	Lenguaje/Septiembre/Recursos/Audios/.gitkeep
A	Lenguaje/Septiembre/Recursos/Lecturas/.gitkeep
A	Lenguaje/Septiembre/Recursos/Libros/.gitkeep
A	Lenguaje/Septiembre/Recursos/Other/.gitkeep
A	Lenguaje/Septiembre/Recursos/Transcriptos/.gitkeep
A	Lenguaje/Septiembre/Recursos/Videos/.gitkeep
A	Lenguaje/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Lenguaje/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Lenguaje/Septiembre/Tareas/Diagnosticas/.gitkeep
D	Lenguaje/Septiembre/Tareas/Diagnosticas/.metadata/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
R100	Lenguaje/Septiembre/Tareas/Diagnosticas/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	Lenguaje/Septiembre/Tareas/Diagnosticas/Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
M	Lenguaje/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	Lenguaje/Septiembre/Tareas/Examen/.gitkeep
A	Matematicas/NOTAS_MATEMATICAS/Promedios-Finales/.gitkeep
A	Matematicas/NOTAS_MATEMATICAS/Trimestrales/.gitkeep
A	Matematicas/Septiembre/Recursos/Audios/.gitkeep
A	Matematicas/Septiembre/Recursos/Lecturas/.gitkeep
A	Matematicas/Septiembre/Recursos/Libros/.gitkeep
A	Matematicas/Septiembre/Recursos/Other/.gitkeep
A	Matematicas/Septiembre/Recursos/Transcriptos/.gitkeep
A	Matematicas/Septiembre/Recursos/Videos/.gitkeep
A	Matematicas/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Matematicas/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Matematicas/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Matematicas/Septiembre/Tareas/Examen/.gitkeep
A	PPE-2/NOTAS_PPE_2/Promedios-Finales/.gitkeep
A	PPE-2/NOTAS_PPE_2/Trimestrales/.gitkeep
A	PPE-2/Septiembre/Recursos/Audios/.gitkeep
A	PPE-2/Septiembre/Recursos/Lecturas/.gitkeep
A	PPE-2/Septiembre/Recursos/Libros/.gitkeep
A	PPE-2/Septiembre/Recursos/Other/.gitkeep
A	PPE-2/Septiembre/Recursos/Transcriptos/.gitkeep
A	PPE-2/Septiembre/Recursos/Videos/.gitkeep
A	PPE-2/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	PPE-2/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	PPE-2/Septiembre/Tareas/Diagnosticas/.gitkeep
A	PPE-2/Septiembre/Tareas/Examen/.gitkeep
R100	PRESENTAR_HOY/08_09_2026/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/Biologia_Week2_September_09_08_2026_Biologia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.png	PRESENTAR_HOY/08_09_2026/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png
R100	PRESENTAR_HOY/08_09_2026/Ciudadania_Week2_September_09_08_2026_Ciudadania-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/Cultura-Fisica_Week2_September_09_08_2026_Cultura-Fisica-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/Filosofia_Week2_September_09_08_2026_Filosofia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/Historia_Week2_September_09_08_2026_Historia-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/Ingles_Week2_September_09_08_2026_Ingles-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/Lenguaje_Week2_September_09_08_2026_Lenguaje-Week1-September-09-07-2026_Cesar_Abarca_Rodriguez.pdf	PRESENTAR_HOY/08_09_2026/Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf
R100	PRESENTAR_HOY/08_09_2026/INDEX.md	PRESENTAR_HOY/08_09_2026/PRESENTAR_HOY.md
A	Proyecto-Interdisciplinario-2BGU/NOTAS_PROYECTO_INTERDISCIPLINARIO_2BGU/Promedios-Finales/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/NOTAS_PROYECTO_INTERDISCIPLINARIO_2BGU/Trimestrales/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Audios/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Lecturas/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Libros/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Other/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Transcriptos/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Recursos/Videos/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Proyecto-Interdisciplinario-2BGU/Septiembre/Tareas/Examen/.gitkeep
A	Quimica/NOTAS_QUIMICA/Promedios-Finales/.gitkeep
A	Quimica/NOTAS_QUIMICA/Trimestrales/.gitkeep
A	Quimica/Septiembre/Recursos/Audios/.gitkeep
A	Quimica/Septiembre/Recursos/Lecturas/.gitkeep
A	Quimica/Septiembre/Recursos/Libros/.gitkeep
A	Quimica/Septiembre/Recursos/Other/.gitkeep
A	Quimica/Septiembre/Recursos/Transcriptos/.gitkeep
A	Quimica/Septiembre/Recursos/Videos/.gitkeep
A	Quimica/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Quimica/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Quimica/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Quimica/Septiembre/Tareas/Examen/.gitkeep
D	REGISTRO_CARPETA.md
M	RESUMEN_ARCHIVOS_2BGU-leer-facil.md
M	RESUMEN_ARCHIVOS_2BGU.md
A	Sociologia/NOTAS_SOCIOLOGIA/Promedios-Finales/.gitkeep
A	Sociologia/NOTAS_SOCIOLOGIA/Trimestrales/.gitkeep
A	Sociologia/Septiembre/Recursos/Audios/.gitkeep
A	Sociologia/Septiembre/Recursos/Lecturas/.gitkeep
A	Sociologia/Septiembre/Recursos/Libros/.gitkeep
A	Sociologia/Septiembre/Recursos/Other/.gitkeep
A	Sociologia/Septiembre/Recursos/Transcriptos/.gitkeep
A	Sociologia/Septiembre/Recursos/Videos/.gitkeep
A	Sociologia/Septiembre/Tareas/Calificado/Grupal/.gitkeep
A	Sociologia/Septiembre/Tareas/Calificado/Individual/.gitkeep
A	Sociologia/Septiembre/Tareas/Diagnosticas/.gitkeep
A	Sociologia/Septiembre/Tareas/Examen/.gitkeep

$ git diff --stat HEAD~1 HEAD
.audit/eliminaciones.md                            |   3 +-
 .audit/git_audit.md                                |  96 +++++++++++++++++++++
 .audit/timeline.md                                 |   1 +
 .../Promedios-Finales/.gitkeep"                    |   1 +
 .../Trimestrales/.gitkeep"                         |   1 +
 .../Septiembre/Recursos/Audios/.gitkeep"           |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep"         |   1 +
 .../Septiembre/Recursos/Libros/.gitkeep"           |   1 +
 .../Septiembre/Recursos/Other/.gitkeep"            |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep"     |   1 +
 .../Septiembre/Recursos/Videos/.gitkeep"           |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep"  |   1 +
 .../Tareas/Calificado/Individual/.gitkeep"         |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep"       |   1 +
 .../Septiembre/Tareas/Examen/.gitkeep"             |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...7-2026_Cesar_Abarca_Rodriguez.png.metadata.json |  60 -------------
 ...7-2026_Cesar_Abarca_Rodriguez.zip.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.png} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.zip} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   8 +-
 .../Promedios-Finales/.gitkeep                     |   1 +
 .../NOTAS_CIENCIAS_NATURALES/Trimestrales/.gitkeep |   1 +
 .../Septiembre/Recursos/Audios/.gitkeep            |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 .../Septiembre/Recursos/Libros/.gitkeep            |   1 +
 .../Septiembre/Recursos/Other/.gitkeep             |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 .../Septiembre/Recursos/Videos/.gitkeep            |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 .../Septiembre/Tareas/Examen/.gitkeep              |   1 +
 .../Promedios-Finales/.gitkeep                     |   1 +
 .../NOTAS_CIENCIAS_SOCIALES/Trimestrales/.gitkeep  |   1 +
 .../Septiembre/Recursos/Audios/.gitkeep            |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 .../Septiembre/Recursos/Libros/.gitkeep            |   1 +
 .../Septiembre/Recursos/Other/.gitkeep             |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 .../Septiembre/Recursos/Videos/.gitkeep            |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 .../Septiembre/Tareas/Examen/.gitkeep              |   1 +
 .../NOTAS_CIUDADANIA/Promedios-Finales/.gitkeep    |   1 +
 Ciudadania/NOTAS_CIUDADANIA/Trimestrales/.gitkeep  |   1 +
 Ciudadania/Septiembre/Recursos/Audios/.gitkeep     |   1 +
 Ciudadania/Septiembre/Recursos/Lecturas/.gitkeep   |   1 +
 Ciudadania/Septiembre/Recursos/Libros/.gitkeep     |   1 +
 Ciudadania/Septiembre/Recursos/Other/.gitkeep      |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 Ciudadania/Septiembre/Recursos/Videos/.gitkeep     |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Ciudadania/Septiembre/Tareas/Diagnosticas/.gitkeep |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   4 +-
 Ciudadania/Septiembre/Tareas/Examen/.gitkeep       |   1 +
 .../Promedios-Finales/.gitkeep                     |   1 +
 .../NOTAS_CULTURA_FISICA/Trimestrales/.gitkeep     |   1 +
 Cultura Fisica/Septiembre/Recursos/Audios/.gitkeep |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 Cultura Fisica/Septiembre/Recursos/Libros/.gitkeep |   1 +
 Cultura Fisica/Septiembre/Recursos/Other/.gitkeep  |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 Cultura Fisica/Septiembre/Recursos/Videos/.gitkeep |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   4 +-
 Cultura Fisica/Septiembre/Tareas/Examen/.gitkeep   |   1 +
 ECA/NOTAS_ECA/Promedios-Finales/.gitkeep           |   1 +
 ECA/NOTAS_ECA/Trimestrales/.gitkeep                |   1 +
 ECA/Septiembre/Recursos/Audios/.gitkeep            |   1 +
 ECA/Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 ECA/Septiembre/Recursos/Libros/.gitkeep            |   1 +
 ECA/Septiembre/Recursos/Other/.gitkeep             |   1 +
 ECA/Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 ECA/Septiembre/Recursos/Videos/.gitkeep            |   1 +
 ECA/Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 ECA/Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 ECA/Septiembre/Tareas/Examen/.gitkeep              |   1 +
 .../Promedios-Finales/.gitkeep                     |   1 +
 .../Trimestrales/.gitkeep                          |   1 +
 .../Septiembre/Recursos/Audios/.gitkeep            |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 .../Septiembre/Recursos/Libros/.gitkeep            |   1 +
 .../Septiembre/Recursos/Other/.gitkeep             |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 .../Septiembre/Recursos/Videos/.gitkeep            |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 .../Septiembre/Tareas/Examen/.gitkeep              |   1 +
 .../Promedios-Finales/.gitkeep                     |   1 +
 .../NOTAS_ESTUDIOS_SOCIALES/Trimestrales/.gitkeep  |   1 +
 .../Septiembre/Recursos/Audios/.gitkeep            |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 .../Septiembre/Recursos/Libros/.gitkeep            |   1 +
 .../Septiembre/Recursos/Other/.gitkeep             |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 .../Septiembre/Recursos/Videos/.gitkeep            |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 .../Septiembre/Tareas/Examen/.gitkeep              |   1 +
 .../NOTAS_FILOSOFIA/Promedios-Finales/.gitkeep     |   1 +
 Filosofia/NOTAS_FILOSOFIA/Trimestrales/.gitkeep    |   1 +
 Filosofia/Septiembre/Recursos/Audios/.gitkeep      |   1 +
 Filosofia/Septiembre/Recursos/Lecturas/.gitkeep    |   1 +
 Filosofia/Septiembre/Recursos/Libros/.gitkeep      |   1 +
 Filosofia/Septiembre/Recursos/Other/.gitkeep       |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 Filosofia/Septiembre/Recursos/Videos/.gitkeep      |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Filosofia/Septiembre/Tareas/Diagnosticas/.gitkeep  |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   4 +-
 Filosofia/Septiembre/Tareas/Examen/.gitkeep        |   1 +
 Fisica/NOTAS_FISICA/Promedios-Finales/.gitkeep     |   1 +
 Fisica/NOTAS_FISICA/Trimestrales/.gitkeep          |   1 +
 Fisica/Septiembre/Recursos/Audios/.gitkeep         |   1 +
 Fisica/Septiembre/Recursos/Lecturas/.gitkeep       |   1 +
 Fisica/Septiembre/Recursos/Libros/.gitkeep         |   1 +
 Fisica/Septiembre/Recursos/Other/.gitkeep          |   1 +
 Fisica/Septiembre/Recursos/Transcriptos/.gitkeep   |   1 +
 Fisica/Septiembre/Recursos/Videos/.gitkeep         |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Fisica/Septiembre/Tareas/Diagnosticas/.gitkeep     |   1 +
 Fisica/Septiembre/Tareas/Examen/.gitkeep           |   1 +
 ..._September_09_08_2026_Cesar_Abarca_Rodriguez.md |  12 ---
 Historia/NOTAS_HISTORIA/Promedios-Finales/.gitkeep |   1 +
 Historia/NOTAS_HISTORIA/Trimestrales/.gitkeep      |   1 +
 Historia/Septiembre/Recursos/Audios/.gitkeep       |   1 +
 Historia/Septiembre/Recursos/Lecturas/.gitkeep     |   1 +
 Historia/Septiembre/Recursos/Libros/.gitkeep       |   1 +
 Historia/Septiembre/Recursos/Other/.gitkeep        |   1 +
 Historia/Septiembre/Recursos/Transcriptos/.gitkeep |   1 +
 Historia/Septiembre/Recursos/Videos/.gitkeep       |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Historia/Septiembre/Tareas/Diagnosticas/.gitkeep   |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   7 +-
 Historia/Septiembre/Tareas/Examen/.gitkeep         |   1 +
 Ingles/NOTAS_INGLES/Promedios-Finales/.gitkeep     |   1 +
 Ingles/NOTAS_INGLES/Trimestrales/.gitkeep          |   1 +
 Ingles/Septiembre/Recursos/Audios/.gitkeep         |   1 +
 Ingles/Septiembre/Recursos/Lecturas/.gitkeep       |   1 +
 Ingles/Septiembre/Recursos/Libros/.gitkeep         |   1 +
 Ingles/Septiembre/Recursos/Other/.gitkeep          |   1 +
 Ingles/Septiembre/Recursos/Transcriptos/.gitkeep   |   1 +
 Ingles/Septiembre/Recursos/Videos/.gitkeep         |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Ingles/Septiembre/Tareas/Diagnosticas/.gitkeep     |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   4 +-
 Ingles/Septiembre/Tareas/Examen/.gitkeep           |   1 +
 Lenguaje/NOTAS_LENGUAJE/Promedios-Finales/.gitkeep |   1 +
 Lenguaje/NOTAS_LENGUAJE/Trimestrales/.gitkeep      |   1 +
 Lenguaje/Septiembre/Recursos/Audios/.gitkeep       |   1 +
 Lenguaje/Septiembre/Recursos/Lecturas/.gitkeep     |   1 +
 Lenguaje/Septiembre/Recursos/Libros/.gitkeep       |   1 +
 Lenguaje/Septiembre/Recursos/Other/.gitkeep        |   1 +
 Lenguaje/Septiembre/Recursos/Transcriptos/.gitkeep |   1 +
 Lenguaje/Septiembre/Recursos/Videos/.gitkeep       |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Lenguaje/Septiembre/Tareas/Diagnosticas/.gitkeep   |   1 +
 ...7-2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  60 -------------
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   4 +-
 Lenguaje/Septiembre/Tareas/Examen/.gitkeep         |   1 +
 .../NOTAS_MATEMATICAS/Promedios-Finales/.gitkeep   |   1 +
 .../NOTAS_MATEMATICAS/Trimestrales/.gitkeep        |   1 +
 Matematicas/Septiembre/Recursos/Audios/.gitkeep    |   1 +
 Matematicas/Septiembre/Recursos/Lecturas/.gitkeep  |   1 +
 Matematicas/Septiembre/Recursos/Libros/.gitkeep    |   1 +
 Matematicas/Septiembre/Recursos/Other/.gitkeep     |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 Matematicas/Septiembre/Recursos/Videos/.gitkeep    |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 Matematicas/Septiembre/Tareas/Examen/.gitkeep      |   1 +
 PPE-2/NOTAS_PPE_2/Promedios-Finales/.gitkeep       |   1 +
 PPE-2/NOTAS_PPE_2/Trimestrales/.gitkeep            |   1 +
 PPE-2/Septiembre/Recursos/Audios/.gitkeep          |   1 +
 PPE-2/Septiembre/Recursos/Lecturas/.gitkeep        |   1 +
 PPE-2/Septiembre/Recursos/Libros/.gitkeep          |   1 +
 PPE-2/Septiembre/Recursos/Other/.gitkeep           |   1 +
 PPE-2/Septiembre/Recursos/Transcriptos/.gitkeep    |   1 +
 PPE-2/Septiembre/Recursos/Videos/.gitkeep          |   1 +
 PPE-2/Septiembre/Tareas/Calificado/Grupal/.gitkeep |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 PPE-2/Septiembre/Tareas/Diagnosticas/.gitkeep      |   1 +
 PPE-2/Septiembre/Tareas/Examen/.gitkeep            |   1 +
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.png} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 ...eptember_09_07_2026_Cesar_Abarca_Rodriguez.pdf} | Bin
 .../08_09_2026/{INDEX.md => PRESENTAR_HOY.md}      |   0
 .../Promedios-Finales/.gitkeep                     |   1 +
 .../Trimestrales/.gitkeep                          |   1 +
 .../Septiembre/Recursos/Audios/.gitkeep            |   1 +
 .../Septiembre/Recursos/Lecturas/.gitkeep          |   1 +
 .../Septiembre/Recursos/Libros/.gitkeep            |   1 +
 .../Septiembre/Recursos/Other/.gitkeep             |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 .../Septiembre/Recursos/Videos/.gitkeep            |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 .../Septiembre/Tareas/Diagnosticas/.gitkeep        |   1 +
 .../Septiembre/Tareas/Examen/.gitkeep              |   1 +
 Quimica/NOTAS_QUIMICA/Promedios-Finales/.gitkeep   |   1 +
 Quimica/NOTAS_QUIMICA/Trimestrales/.gitkeep        |   1 +
 Quimica/Septiembre/Recursos/Audios/.gitkeep        |   1 +
 Quimica/Septiembre/Recursos/Lecturas/.gitkeep      |   1 +
 Quimica/Septiembre/Recursos/Libros/.gitkeep        |   1 +
 Quimica/Septiembre/Recursos/Other/.gitkeep         |   1 +
 Quimica/Septiembre/Recursos/Transcriptos/.gitkeep  |   1 +
 Quimica/Septiembre/Recursos/Videos/.gitkeep        |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Quimica/Septiembre/Tareas/Diagnosticas/.gitkeep    |   1 +
 Quimica/Septiembre/Tareas/Examen/.gitkeep          |   1 +
 REGISTRO_CARPETA.md                                |  30 -------
 RESUMEN_ARCHIVOS_2BGU-leer-facil.md                |  73 +---------------
 RESUMEN_ARCHIVOS_2BGU.md                           |  29 +++----
 .../NOTAS_SOCIOLOGIA/Promedios-Finales/.gitkeep    |   1 +
 Sociologia/NOTAS_SOCIOLOGIA/Trimestrales/.gitkeep  |   1 +
 Sociologia/Septiembre/Recursos/Audios/.gitkeep     |   1 +
 Sociologia/Septiembre/Recursos/Lecturas/.gitkeep   |   1 +
 Sociologia/Septiembre/Recursos/Libros/.gitkeep     |   1 +
 Sociologia/Septiembre/Recursos/Other/.gitkeep      |   1 +
 .../Septiembre/Recursos/Transcriptos/.gitkeep      |   1 +
 Sociologia/Septiembre/Recursos/Videos/.gitkeep     |   1 +
 .../Septiembre/Tareas/Calificado/Grupal/.gitkeep   |   1 +
 .../Tareas/Calificado/Individual/.gitkeep          |   1 +
 Sociologia/Septiembre/Tareas/Diagnosticas/.gitkeep |   1 +
 Sociologia/Septiembre/Tareas/Examen/.gitkeep       |   1 +
 257 files changed, 348 insertions(+), 687 deletions(-)
```

---
### 🚀 Git Auto-Commit: `2026-09-08 02:18:35`
> **Mensaje:** `Auto-update SFMS: 2026-09-08 02:18:33`  
> **Resumen:** Sincronización automática periódica

```shell
$ git add .
warning: in the working copy of '.audit/movimientos.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/timeline.md', LF will be replaced by CRLF the next time Git touches it


$ git commit -m "Auto-update SFMS: 2026-09-08 02:18:33"
[main 30dfda7] Auto-update SFMS: 2026-09-08 02:18:33
 2 files changed, 105 insertions(+)


$ git push
To https://github.com/MRodzDirect/C.A.R_2-BGU
   1cd970d..30dfda7  main -> main
```

#### 📊 Resumen de Diferencias (Diff de Archivos)
```shell
$ git diff --name-status HEAD~1 HEAD
M	.audit/movimientos.md
M	.audit/timeline.md

$ git diff --stat HEAD~1 HEAD
.audit/movimientos.md | 53 +++++++++++++++++++++++++++++++++++++++++++++++++++
 .audit/timeline.md    | 52 ++++++++++++++++++++++++++++++++++++++++++++++++++
 2 files changed, 105 insertions(+)
```

---
### 🚀 Git Auto-Commit: `2026-09-08 02:31:26`
> **Mensaje:** `Auto-update SFMS: 2026-09-08 02:31:23`  
> **Resumen:** Sincronización automática periódica

```shell
$ git add .
warning: in the working copy of '.audit/git_audit.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/movimientos.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/timeline.md', LF will be replaced by CRLF the next time Git touches it


$ git commit -m "Auto-update SFMS: 2026-09-08 02:31:23"
[main 8ffd57f] Auto-update SFMS: 2026-09-08 02:31:23
 32 files changed, 1027 insertions(+), 20 deletions(-)
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_Biperologia-Wefect-ek1-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_Loquesea-New-Text_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_New-Text-Document_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_d_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-ok-perfect-Loquesea-NeText-haha-haha-Rodri-ni-guez-ce-ni-ce_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-ok-perfect-Loquesea-NeText-haha-haha-Rodri-ni-guez-ce_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-ok-perfect-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-perfect-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_perfect-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
 create mode 100644 PRESENTAR_HOY/08_09_2026/.metadata/Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json


$ git push
To https://github.com/MRodzDirect/C.A.R_2-BGU
   30dfda7..8ffd57f  main -> main
```

#### 📊 Resumen de Diferencias (Diff de Archivos)
```shell
$ git diff --name-status HEAD~1 HEAD
M	.audit/eliminaciones.md
M	.audit/git_audit.md
M	.audit/movimientos.md
M	.audit/timeline.md
M	.sfms_data/sfms_postgres_ledger.db
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_Biperologia-Wefect-ek1-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_Loquesea-New-Text_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_New-Text-Document_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_d_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-ok-perfect-Loquesea-NeText-haha-haha-Rodri-ni-guez-ce-ni-ce_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-ok-perfect-Loquesea-NeText-haha-haha-Rodri-ni-guez-ce_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-ok-perfect-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_ok-perfect-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
A	Biologia/Septiembre/Tareas/Diagnosticas/.metadata/Biologia_Week1_September_09_08_2026_perfect-Loquesea-NeText-haha-haha_Cesar_Abarca_Rodriguez.txt.metadata.json
M	Biologia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Ciudadania/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Cultura Fisica/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Filosofia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Historia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Ingles/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Lenguaje/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
A	PRESENTAR_HOY/08_09_2026/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Biologia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.png.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Ciudadania_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Cultura-Fisica_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Filosofia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Historia_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Ingles_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
A	PRESENTAR_HOY/08_09_2026/.metadata/Lenguaje_Week1_September_09_07_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json
M	RESUMEN_ARCHIVOS_2BGU-leer-facil.md
M	RESUMEN_ARCHIVOS_2BGU.md

$ git diff --stat HEAD~1 HEAD
.audit/eliminaciones.md                            |   1 +
 .audit/git_audit.md                                |  33 +++++++++++++
 .audit/movimientos.md                              |  19 ++++++++
 .audit/timeline.md                                 |  30 ++++++++++++
 .sfms_data/sfms_postgres_ledger.db                 | Bin 36864 -> 40960 bytes
 ...a-haha_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...a-haha_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...w-Text_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...cument_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...2026_d_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...-ni-ce_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...uez-ce_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...a-haha_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...a-haha_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 ...a-haha_Cesar_Abarca_Rodriguez.txt.metadata.json |  54 +++++++++++++++++++++
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.png.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 ...7_2026_Cesar_Abarca_Rodriguez.pdf.metadata.json |  48 ++++++++++++++++++
 RESUMEN_ARCHIVOS_2BGU-leer-facil.md                |  18 +++----
 RESUMEN_ARCHIVOS_2BGU.md                           |   8 +--
 32 files changed, 1027 insertions(+), 20 deletions(-)
```

---
### 🚀 Git Auto-Commit: `2026-09-08 02:36:25`
> **Mensaje:** `Auto-update SFMS: 2026-09-08 02:36:22`  
> **Resumen:** Sincronización automática periódica

```shell
$ git add .
warning: in the working copy of '.audit/git_audit.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of '.audit/timeline.md', LF will be replaced by CRLF the next time Git touches it


$ git commit -m "Auto-update SFMS: 2026-09-08 02:36:22"
[main 9568e20] Auto-update SFMS: 2026-09-08 02:36:22
 12 files changed, 122 insertions(+), 58 deletions(-)
 delete mode 100644 .metadata/General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md.metadata.json


$ git push
To https://github.com/MRodzDirect/C.A.R_2-BGU
   8ffd57f..9568e20  main -> main
```

#### 📊 Resumen de Diferencias (Diff de Archivos)
```shell
$ git diff --name-status HEAD~1 HEAD
M	.audit/git_audit.md
M	.audit/timeline.md
D	.metadata/General_Week2_September_09_08_2026_Cesar_Abarca_Rodriguez.md.metadata.json
M	Biologia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Ciudadania/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Cultura Fisica/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Filosofia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Historia/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Ingles/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	Lenguaje/Septiembre/Tareas/Diagnosticas/REGISTRO_CARPETA.md
M	RESUMEN_ARCHIVOS_2BGU-leer-facil.md
M	RESUMEN_ARCHIVOS_2BGU.md

$ git diff --stat HEAD~1 HEAD
.audit/git_audit.md                                | 112 +++++++++++++++++++++
 .audit/timeline.md                                 |   1 +
 ...08_2026_Cesar_Abarca_Rodriguez.md.metadata.json |  49 ---------
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 .../Tareas/Diagnosticas/REGISTRO_CARPETA.md        |   2 +-
 RESUMEN_ARCHIVOS_2BGU-leer-facil.md                |   2 +-
 RESUMEN_ARCHIVOS_2BGU.md                           |   2 +-
 12 files changed, 122 insertions(+), 58 deletions(-)
```

---
