# Cuenta bancaria — Git y pull requests

**Autor:** Alejandro Elías Castañeda Ibarra

## Cómo correr

    ./correr.sh

## Mis pull requests

| # | Qué cambió |
|---|---|
| 1 | El estado de cuenta muestra cuántos retiros se hicieron y cuántos fueron gratis |
| 2 | README y evidencia de la práctica |

## Boleto de salida

1. ¿Qué diferencia hay entre `git add` y `git commit`?

   Respuesta: El add añade los cambios que se subiran al commit y commit es el que guarda el registro de los cambios con un mensaje personalizado.

2. ¿Por qué después del merge en GitHub tu `main` de Ubuntu no tenía el cambio hasta que hiciste `git pull`?

   Respuesta: Porque el merge se hizo desde el repositorio remoto, no desde el local, por eso solo se reflejó en GitHub, al hacer pull el repositorio local llama los cambios que se hicieron desde el remoto.

3. Abriste un PR y después hiciste otro commit en la misma rama. ¿Qué pasó con el PR?

   Respuesta: El PR detectó el nuevo commit y lo pusó despues del comentario, además se actualizó el código en Files changed.

4. ¿Por qué en un equipo nadie hace cambios directamente en `main`?

   Respuesta: Porque es la rama principal, cada integrante debe tener su propia rama y trabajar sus propios cambios ahí, es en la rama main donde se añaden el cambio de todos los integrantes.