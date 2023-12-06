namespace ConsoleApp4
{

    internal class Program
    {
        namespace ConsoleApp5
{
    class random
    {
        public int rastgeleSayi(int i)
        {
            random random = new random();
            int rastgeleSayi = random.Next(1, 11);
            int tahmin = 0;
            int tahminHkkı = 3;
            Console.WriteLine("1 ile 10 araasında bir sayıyı tahmin edin:");
            while (tahminHkkı > 0)
            {
                if (int.TryParse(Console.ReadLine(), out rastgeleSayi))
                {
                    if (tahmin == rastgeleSayi)
                    {
                        Console.WriteLine("Tebrikler,Tahmin Doğru:");
                        break;
                    }
                    else {
                        tahminHkkı--;
                        if (tahminHkkı > 0)
                        {
                            Console.WriteLine("Üngünüz,Tahmininiz Yanlış.Kalan Tahmin Sayınız:" + tahminHkkı);
                        }
                        else
                        {
                            Console.WriteLine("Tahmin Hakkınız Bitti.Doğru cevap:" + rastgeleSayi);
                        }


                        else
                        {
                            Console.WriteLine("Lütfen Geçerli Bir Sayı Girin.");

                        }
                    }
                    Console.WriteLine("Oyun bitti. Lütfen tekrar deneyiniz!");
                }
                

            }
           
        }





        internal class Program
        {
            static void Main(string[] args)
            {
                Console.ReadKey();
            }
        }
    } 
}
 
    
