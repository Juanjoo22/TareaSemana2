using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace TareaEjercicio
{
    internal class Program
    {
        static void Main(string[] args) //Programa solicita un numero y luego imprime un contador hasta el numero brindado por el usuario
        {

            {

                Console.WriteLine("Ingrese un número:");
                int n = Convert.ToInt32(Console.ReadLine());

                if (n >= 2 && n < 100)
                {
                    for (int i = 1; i < n; i++)
                    {
                        Console.WriteLine("Número actual: " + i);
                    }

                    Console.WriteLine("Numero final: "+n);
                }

                else
                {
                    Console.WriteLine("Por favor digite un numero mayor o igual que 2 y menor que 100");
                }

            }

        }

    }

}

Errores de texto, en los “Line”, escrito con minúscula en lugar de mayúscula
Se agregaron líneas (if) para prevenir posibles errores que pueda generar el programa con los datos que brinde el Usuario.






using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace TareaEjercicio3
{

    class Program
    {
        static void Main()
        {
            Console.WriteLine("Ingrese el primer número:");
            int num1 = Convert.ToInt32(Console.ReadLine());

            Console.WriteLine("Ingrese el segundo número:");
            int num2 = Convert.ToInt32(Console.ReadLine());

            int suma = num1 + num2;
            Console.WriteLine($"La suma es: {suma}");
        }
    }

}
Errores de texto, en los “Line”, escrito con minúscula en lugar de mayúscula
Se agrego el “Convert.ToInt32” para pasar el dato brindado por el usuario de string a int.












using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace TareaEjercicio3
{

    class Program
    {
        static void Main()
        {

            Console.WriteLine("Ingrese un número entero:");
            int numero = Convert.ToInt32(Console.ReadLine());

            if (numero % 3 == 0 && numero % 5 == 0)
            {
                Console.WriteLine("El número es múltiplo de 3 y 5.");
            }
            else
            {
                Console.WriteLine("El número no es múltiplo de 3 y 5.");
            }

        }
    }

}

Errores de texto, en los “Line”, escrito con minúscula en lugar de mayúscula
Se cambio el símbolo || (o) por el símbolo “&&” (and), esto para que la condición se cumple únicamente si el digito es múltiplo de 3 y 5 simultáneamente. 
