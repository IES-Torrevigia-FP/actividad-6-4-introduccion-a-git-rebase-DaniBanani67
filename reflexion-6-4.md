1. Explica con tus palabras la diferencia entre git merge y git rebase en cuanto al historial que generan.

El git merge une dos ramas creando un commit de merge, el historial queda no lineal y se conserva exactamente como ocurrio el trabajo
Mientras que el git rebase reescribe el historial moviendo los commits encima de otra rama, el historial queda lineal y parece mas limpio pero cambia el historial inicia

2. Indica una situación en la que preferirías usar rebase y otra en la que preferirías usar merge.

Usaria rebase cuando estoy yo solo trabajando en una rama local, cuando quiero un historial limpio antes de añadir cambios
Y usaria merge cuando trabajo en equipo, la rama esta compartida y cuando quiero mantener un historial real de lo que paso

3. ¿Por qué se recomienda no usar rebase sobre ramas que ya han sido compartidas con otras personas (push al remoto)?

por que reescribe el historial, cambian los commits y otros compañeros tendran un historial diferente
puede causar conflictos y problemas al hacer pull