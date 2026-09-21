# Mi presentación

**Holaa esto es un nuevo archivo**

*Me gusta escribir poesía*

Por estas razones:

1. Es divertido
2. Es romántico
3. Desarrola la creatividad

Aaah y la serie que más me **inspira** y es mi favorita es esta:

![](https://nuestrotiempo.unav.edu/documents/116202662/191698003/arcane_cartel.jpg/619fb679-4c8a-a30f-540a-a3aacf57bece?version=1.0&t=1760089513761)


# Hobbys

Sé programar en Java

``` java
import java.util.Scanner;

public class Calculadora {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Primer número: ");
        double a = sc.nextDouble();

        System.out.print("Operador (+, -, *, /): ");
        String op = sc.next();

        System.out.print("Segundo número: ");
        double b = sc.nextDouble();

        double resultado = 0;

        if (op.equals("+")) {
            resultado = a + b;
        } else if (op.equals("-")) {
            resultado = a - b;
        } else if (op.equals("*")) {
            resultado = a * b;
        } else if (op.equals("/")) {
            if (b == 0) {
                System.out.println("Error: no se puede dividir entre cero");
                sc.close();
                return;
            }
            resultado = a / b;
        } else {
            System.out.println("Operador no válido");
            sc.close();
            return;
        }

        System.out.println("Resultado: " + resultado);
        sc.close();
    }
}

```


## Pasión

La programación es mi pasión, mi estilo de vida y tener a tu gato durmiendo mientras programas a la luz de la Luna :full_moon:

Es simplemente maravilloso :heart:
