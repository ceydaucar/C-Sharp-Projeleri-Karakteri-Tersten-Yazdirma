# C-Sharp-Projeleri-Karakteri-Tersten-Yazdirma

Verilen string ifade içerisindeki karakterleri bir önceki karakter ile yer değiştiren console uygulamasını yazınız.

Örnek: Input: Merhaba Hello Question

Output: erhabaM elloH uestionQ

    using System;

    class Program {
      public static void Main (string[] args) {

        Console.Write("Lütfen kelime girin): ");
        string word = Console.ReadLine();

        string ch = word.Substring(0,1);

        string newWord = word.Substring(1, word.Length - 1);

        System.Console.WriteLine(newWord + ch);
      }
    }
