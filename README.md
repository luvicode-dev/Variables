Variables (Explicación)

package variables;

Declara que el código pertenece al paquete variables.
Si estás ejecutando el código sin un entorno de paquetes, puedes omitir esta línea.
Declaración de la clase:
 
public class Variables {}


Define una clase llamada Variables.
En Java, todo el código debe estar dentro de una clase.
Método main (punto de entrada del programa):


public static void main(String[] args) {}

Java siempre empieza ejecutando el código dentro de main().

Declaración de variables y tipos de datos:


int telefono = 60347895;
int → Almacena números enteros.
telefono almacena 60347895.

char letra = 'G';
char → Almacena un único carácter, entre comillas simples ('G').

float peso = 65.2f;
float → Almacena números decimales, pero requiere la letra f al final (65.2f).

double nGrande = 76.901820;
double → Almacena números decimales con mayor precisión que float.

Impresión de valores en consola (System.out.println):

System.out.println("El número de teléfono es: " + telefono);
System.out.println("La letra es: " + letra);
System.out.println("El peso es: " + peso);
System.out.println("El número grande es: " + nGrande);

System.out.println() imprime en consola.

Se usa concatenación (+) para unir texto con variables.

Salida esperada en la consola:

El número de teléfono es: 60347895
La letra es: G
El peso es: 65.2
El número grande es: 76.90182

Puntos clave:

int → Para números enteros.
char → Para un solo carácter.
float → Para números decimales (usa f al final).
double → Para decimales con mayor precisión.
System.out.println() → Imprime en la consola.
