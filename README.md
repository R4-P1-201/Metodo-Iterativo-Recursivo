# Metodo-Iterativo-Recursivo
Metodo Iterativo y Recursivo - Estructuras de datos y algortimos fundamentales - Tecnol贸gico de Monterrey

馃摉 - 驴Qu茅 es el metodo recursivo?
Toma en cuenta este caso de la funci贸n factorial 

0! = 1
1! = 1
2! = 2*1 = 2
3! = 3*2*1 = 6
4! = 4*3*2*1 = 24
n! = n*(n-1)*(n-2)*...*2*1

n!
馃搶 - Si n = o entonces es 1
馃搶 - Si n > 0 entonces n * (n-1) * (n-2) * ... 1

馃摑 - Ejemplo: 
  5! = 5 * 4 * 3 * 2 * 1 = 120

Para la forma recursiva (para valores no negativos de n) es de esta forma: 
n!
馃搶 - Si n = 0 entones es 1
馃搶 - Si n > 0 entonces n*(n-1)!

馃捇 - 驴Qu茅 hay dentro de esta funci贸n?
int fact(int n){
  if (n == 0){
    return 1;
  }
  else{
    return n * fact(n-1);
  }

馃 - El caso base es el caso en el que no se vuelve a llamar la misma funci贸n, de tal forma que se termina la recursi贸n.
馃 - Una funci贸n recursiva debe tener al menos un caso base. 


