//questão 01 

namespace TesteTarget
{
    internal class Program
    {
        static void Main(string[] args)
        {

            int indice = 13;
            int k = 0; 
            int soma = 0;
            
            while (k < indice)
            {
                k = k + 1;
                soma = soma + k;

            }

            Console.WriteLine(soma);
        }
        

    }
}
