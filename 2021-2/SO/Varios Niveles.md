# Cola Multinivel

> Se tienen varias colas que se clasifican según su función. Donde la cola ready esta separada en diferentes colas, que pueden tener algoritmos distintos. 
> ![[Pasted image 20211115171430.png]]

La clasificación es a nivel de SO. La cola ready se separaría en _tantas colas como niveles tuviesemos_.

![[Pasted image 20211115171901.png]]

> Cada cola tiene prioridad absoluta sobre las colas de prioridad más baja.

Cada cola puede tener su propio sistema de clasificación.

Asigna por la clasificación del proceso puntual. Lo importante es identificar prioridades y tipos de las colas.

A medida que terminan las colas de arriba, se le asignan la cpu a los de abajo.

## Ej

![[Pasted image 20211115172516.png]]

Si llega un proceso con mayor prioridad, se interrumpe el quese esta ejecutando actualmente. Es **apropiativo**.

