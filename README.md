namespace ConsoleApp4
{

    internal class Program
    {
        class fakto
        {
            public int kdş(int sayi1)
            {
                int toplam = 1;
                for (int i = 1; i <= sayi1; i++)
                {
                    toplam = toplam * i;
                }
                return toplam;
            }
        }
       
        static void Main(string[] args)
        {
            fakto fakto = new fakto();
            Console.WriteLine("sayı girin");
            int sayi1 = Convert.ToInt32(Console.ReadLine());
            int toplam = fakto.kdş(sayi1);
            Console.WriteLine("Faktöriyel:{0}", toplam);
            Console.ReadKey();


        }
    }
}
