[Patika.dev](https://github.com/mordulu)


Dosyalarımın içinde yer alan program.cs'ye girilme zahmeti olmaması adına aşağıya çalışmamı önizleme olarak ekliyorum(süslü parantezler önizlemede hata verdiğinden konumlandırmalarına dikkat etmeyiniz)


# C-101-Switch-Case-Yapisi


         internal class Program
          {
         private static void Main(string[] args)
          {
         int month = DateTime.Now.Month;
        
         //Expression
         switch (month)
         {
            case 1:
                System.Console.WriteLine("Ocak ayındasınız!");
                break;
            case 2:
                System.Console.WriteLine("Şubat ayındasınız!");
                break;
            case 4:
                System.Console.WriteLine("Nisan ayındasınız!");
                break;
            case 3:
                System.Console.WriteLine("Mart ayındasınız!");
                break;
            case 8:
                System.Console.WriteLine("Ağustos ayındasınız!");
                break;

            
             default:
                System.Console.WriteLine("Yalnış veri girdiniz");
             break;

         }

         switch (month)
         {
            case 12:

            case 1:

            case 2:
                System.Console.WriteLine("Kış ayındasınız!");
                 break;

            case 3:

            case 4:

            case 5:
                System.Console.WriteLine("ilkbahar ayındasınız");
                break;
            
            case 6:

            case 7:

            case 8:
                System.Console.WriteLine("Yaz ayındasınız");
                break;
            case 9:

            case 10:

            case 11:
                System.Console.WriteLine("Yaz ayındasınız");
                break;
            default:
                break;


         }
    }
}
