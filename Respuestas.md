1. En la primer expresión de la sentencia for encontramos "nl = 0, nc = 0".
La "," dentro de esta expresión oficia de operador.
Su función es evaluar el primer argumento, luego el segundo, teniendo como objetivo el efecto de lado: para ambas variables se les asigna el valor "0".
Una expresión equivalante puede ser (nl=nc)=0.

2. Los paréntesis son necesarios en la expresión c=getchar() dado que la asociatividad es de derecha a izquierda. En caso de no usarlos se produciría un error en el programa.

3. En cuanto a la sentencia if que está a continuación de la sentencia for, se analiza:
3.1 Semántica:
3.1.1 Evalúa la expresión del if.
3.1.2 Evalúa si es verdadera.
3.1.3 Si el resultado es verdadero, llama a perror con el argumento ("Error!").
3.1.4 Invoca a la función feof, con stdin y lo niega.
3.1.5 Invoca a ferror con el argumento ("Error!").

3.2 Pragmática: Ver si terminó con error o no.

4. La función perror emite los errores por stderror, lo que me permite detectarlos sin interrumpir la pantalla.

5.  