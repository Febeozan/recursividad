# recursividad
**Define una función llamada nDescendentes que toma un entero n como argumento**
~~~~
fun nDescendentes(n: Int) {
~~~~         
**Verifica si el valor de n es menor o igual a 0.**
~~~~
    if (n <= 0) {
~~~~
**Si n es menor o igual a 0, imprime el valor de n.**
~~~~
        print(n)
~~~~
**Llama a la función nDescendentes con el argumento n-1 para continuar con el descenso.**
~~~~
        nDescendentes(n - 1)
    }
}
~~~~
**Define la función principal main que se ejecuta al iniciar el programa.**
~~~~
fun main() {
~~~~
**Define una variable llamada numero con el valor 5.**
~~~~
    val numero = 5
~~~~
**Llama a la función nDescendentes con la variable numero como argumento.**
~~~~
    nDescendentes(numero)
}

~~~~

es una funcion que se llama asi misma para resolver el problema
### componentes
###### caso base:
~~~~
if(n=<=0){
return}
~~~~

la comdicion que termina la recursion y evitaun ciclo infinito
##### llamada recursiva:
~~~~
numerosDescendentes(n-1)
~~~~

la funcion se llama asi misma con argumentos que progresen hacia el caso base
