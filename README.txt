Cherry Pick
Llevar un solo commit sin necesidad de pasar todos los commit a la rama
principal, que hayas hecho cambios en rama de prueas y se necesita pasar
esos cambios en especifico a la rama master.

Command -->  git cherry-pick <#id del commit>

Cuando te da conflicto al querer combinar los archivos de ramas diferentes
es porque en ambas ramas se modificó el mismo archivo en la misma linea.
Es una de las razones por las que da conflicto al merge ramas
En codigo te aparece la parte que esta en cada rama, para que puedas modificar
y seleccionar.
