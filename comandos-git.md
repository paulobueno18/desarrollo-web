# Comandos Git - Referencia Rápida

## SOLO LA PRIMERA VEZ (configuración inicial)

```bash
git init
git add .
git commit -m "primera version landing page"
git remote add origin https://github.com/paulobueno18/desarrollo-web.git
git push -u origin master
```

## CADA VEZ QUE MODIFICÁS UN ARCHIVO

```bash
git add .
git commit -m "descripcion de lo que cambiaste"
git push
```
## cuando modificamos el nombre del archivo
git commit -m "Renombrar practica5 a trabajo 1"
```

## NOTAS IMPORTANTES

- Siempre guardá el archivo en VS Code con **Ctrl + S** antes de hacer git add .
- El mensaje del commit describe qué cambiaste, por ejemplo:
  - "agregue seccion habilidades"
  - "modifique footer"
  - "corregi errores index.html"
- Los 3 comandos siempre van en orden: add → commit → push
