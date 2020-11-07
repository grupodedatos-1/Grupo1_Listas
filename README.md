# Grupo1_Listas
Primer Seminario de Est. de bases de datos UAPA

using System;
using System.Collections.Generic;
using System.Net.Http.Headers;

namespace lista_numeros
{
    class Program
    {
        static void Main(string[] args)
        {

            List<int> listadenumeros = new List<int>();

            listadenumeros.Add(5);
            listadenumeros.Add(8);

            listadenumeros.Insert(0, 2);
            listadenumeros.Insert(1, 4);

            foreach (int lista_numeros in listadenumeros)
            {
                Console.WriteLine(lista_numeros);

            }

            Console.ReadKey();


        }
    }
}
