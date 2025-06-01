# Mi Primer Repositorio                      ---Sebastian Silva Quintos

Este es un proyecto de práctica para aprender Git y GitHub.

##  Objetivos

- Aprender a crear y conectar un repositorio local con GitHub.
- Usar ramas para desarrollo de nuevas funcionalidades.
- Trabajar colaborativamente usando Pull Requests e Issues.
- Configurar integración continua (CI) con GitHub Actions.
- Documentar el proceso de aprendizaje y dificultades.

---

##  Funcionalidades implementadas

- `README.md` con la descripción del proyecto.
- `EXPERIENCIA.md` con reflexiones personales sobre el proceso.
- Uso de ramas (`feature`) para nuevas funcionalidades.
- Pull Request creado y fusionado con `main`.
- Issue creado y gestionado con etiquetas y milestones.
- Archivo de prueba (`test_basico.py`) para validar integración.
- GitHub Action configurada para ejecutar `pytest` automáticamente.

---

##  Automatización con GitHub Actions

Se agregó un flujo de trabajo de CI (Integración Continua) usando `pytest` para que, cada vez que se realice un push a `main`, se ejecuten automáticamente las pruebas del repositorio.  
Archivo del flujo: `.github/workflows/python-app.yml`.
