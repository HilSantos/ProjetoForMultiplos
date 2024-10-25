# ProjetoForMultiplos
Idem(25/10).

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForMultiplos
{
    public class Program
    {
        static void Main(string[] args)
        {
            /*Solicite e receba um numero inteiro e exiba os proximos 12 numeros
             * com o multiplo do valor correspondente (3).
            */
            Console.WriteLine("Informe o numero: ");
            int numero = Convert.ToInt32(Console.ReadLine());

            for (int i = 1; i <= 12; i++)
            {
                numero *= 3;
                Console.WriteLine("Numero: " + numero);
            }

                Console.ReadKey();
        }
    }
}
