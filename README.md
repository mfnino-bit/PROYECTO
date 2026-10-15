# PROYECTO
Tutorial de Git en español, basado en el libro [Pro Git](https://git-scm.com/book/es/v2) (Chacon & Straub, 2014). Cada capítulo se redactó en un documento de Word distinto y se exportó a PDF.

| Capítulo | Documento Word | Documento PDF |
|---|---|---|
| 1. Inicio – Sobre el control de versiones | 01_Inicio_Control_de_Versiones.docx | 01_Inicio_Control_de_Versiones.pdf |
| 2. Fundamentos de Git | 02_Fundamentos_de_Git.docx | 02_Fundamentos_de_Git.pdf |
| 3. Ramificaciones en Git | 03_Ramificaciones_en_Git.docx | 03_Ramificaciones_en_Git.pdf |
| 4. Git en el servidor | 04_Git_en_el_Servidor.docx | 04_Git_en_el_Servidor.pdf |
| 5. Git en entornos distribuidos | 05_Git_en_entornos_distribuidos.docx | 05_Git_en_entornos_distribuidos.pdf |
| 6. GitHub | 06_GitHub.docx | 06_GitHub.pdf |
| 7. Herramientas de Git | 07_Herramientas_de_Git.docx | 07_Herramientas_de_Git.pdf |
| 8. Personalización de Git | 08_Personalizacion_de_Git.docx | 08_Personalizacion_de_Git.pdf |
| 9. Git y otros sistemas | 09_Git_y_otros_sistemas.docx | 09_Git_y_otros_sistemas.pdf |
| 10. Los entresijos internos de Git | 10_Los_entresijos_internos_de_Git.docx | 10_Los_entresijos_internos_de_Git.pdf |

## Proceso seguido

1. Creación de la cuenta en GitHub.
2. Instalación de Git y configuración de la identidad (git config --global user.name y user.email).
3. Creación del repositorio en GitHub.
4. Clonación en el computador local con git clone.
5. Elaboración de un documento de Word por cada capítulo de Pro Git y exportación a PDF.
6. Por cada capítulo: git add → git commit -m "..." → git push.
7. Redacción de este README.md para documentar el proceso.

### Comandos utilizados

bash
git --version
git config --global user.name "Nombre Apellido"
git config --global user.email "correo@ejemplo.com"
git clone https://github.com/<usuario>/<repositorio>.git
git status
git add .
git commit -m "Agrega capítulo N: título"
git push origin main
git log --oneline


## Registro de cambios

Un commit por capítulo, enviado al repositorio remoto al terminar cada uno.

| Commit | Cambio realizado |
|---|---|
| 1 | Agrega capítulo 1: Inicio – Sobre el control de versiones |
| 2 | Agrega capítulo 2: Fundamentos de Git |
| 3 | Agrega capítulo 3: Ramificaciones en Git |
| 4 | Agrega capítulo 4: Git en el servidor |
| 5 | Agrega capítulo 5: Git en entornos distribuidos |
| 6 | Agrega capítulo 6: GitHub |
| 7 | Agrega capítulo 7: Herramientas de Git |
| 8 | Agrega capítulo 8: Personalización de Git |
| 9 | Agrega capítulo 9: Git y otros sistemas |
| 10 | Agrega capítulo 10: Los entresijos internos de Git |
| 11 | Agrega README.md con la documentación del proceso |

## Referencias

- Chacon, S., & Straub, B. (2014). Pro Git (2nd ed.). Apress. https://git-scm.com/book/es/v2
- GitHub, Inc. (2019). GitHub Guides: Learn Git and GitHub. https://guides.github.com/
- Hutch Data Science. (n.d.). Using GitHub in a workflow. https://hutchdatascience.org/Tools_for_Reproducible_Workflows_in_R/using-github-in-a-workflow.html
