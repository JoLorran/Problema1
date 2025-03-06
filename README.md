using System;

class Program
{
    static void Main()
    {
        // Lendo os valores de entrada
        Console.WriteLine("Digite o primeiro valor:");
        int A = int.Parse(Console.ReadLine());
        Console.WriteLine("Digite o segundo valor:");
        int B = int.Parse(Console.ReadLine());
        // Calculando a soma
        int X = A + B;
        // Exibindo o resultado conforme especificação
        Console.WriteLine($"X = {X}");
    }
}
