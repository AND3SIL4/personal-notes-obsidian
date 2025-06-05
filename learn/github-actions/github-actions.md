Es una herramienta de GitHub, que funciona para automatizar tareas en repositorios del GitHub, incluye todos los repositorios.

Para que se utiliza:
- Continuos integrations and continuos deployment
- Tareas repetitivas

Workflow:
- Push
- Merge
- Pull Request

---
Conceptos:
- Acciones: todas las acciones que se puedan realizar dentro del repositorio (pull, commits, push, etc)
- Workflows: se almacenan en archivos JAM, en el workflow de github (.github/workflows)
- Triggers: hace que se ejecute un workflow al realizar una acción
- Jobs: unidad que permite definir un trabajo, un workflow puede tener mas de 1 job. Se ejecuta por separado y posiblemente en simultaneo.
- Steps: pasos individuales dentro de los jobs, se ejecutan en secuencia, usan variables de entorno
- Runners: maquinas virtuales donde se ejecutan los workflows



