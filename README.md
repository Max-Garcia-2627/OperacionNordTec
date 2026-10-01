# Max García

## Práctica de Markdown

Este README forma parte de la práctica **practica-markdown**. Hoy he repasado cómo guardar y subir cambios usando Git y GitHub.

## Subir un cambio a GitHub

1. Comprobar los archivos modificados con `git status`.
2. Preparar los cambios con `git add README.md`.
3. Crear un commit con `git commit -m "Completar README de práctica"`.
4. Subir los cambios con `git push`.

### Tareas

- [x] Completar el README con Markdown.
- [x] Configurar el remoto de GitHub.
- [ ] Revisar el repositorio después de subir los cambios.

### Enlace y comandos de hoy

Repositorio: [GitHub - Max-Garcia-2627](https://github.com/Max-Garcia-2627/README.md)

```bash
git status
git remote -v
git remote add origin https://github.com/Max-Garcia-2627/README.md.git
git push -u origin main
```

### Comandos Git

| Comando | Qué hace |
| --- | --- |
| `git status` | Muestra el estado de los archivos y la rama actual. |
| `git add README.md` | Prepara el README para incluirlo en el próximo commit. |
| `git commit -m "mensaje"` | Guarda los cambios preparados con un mensaje. |
| `git remote -v` | Muestra los remotos configurados para descargar y subir cambios. |
| `git push` | Envía los commits locales al repositorio remoto. |
| `git pull` | Descarga e integra los cambios del repositorio remoto. |

## Incidencias

Al revisar el repositorio, `git remote -v` no mostró ningún remoto configurado, así que todavía no se podían enviar los cambios a GitHub desde esta copia local. Ocurría porque el repositorio no tenía asociado un destino remoto. Lo resolví añadiendo `origin` con la URL de GitHub y comprobé la configuración con `git remote -v`.
