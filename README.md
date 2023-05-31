internal class Program
{
    private static void Main(string[] args)
    {
   

        for (int counter = 0,prev= 0, current = 1; counter < 10; ++counter)
        {
            Console.WriteLine(prev + "  ");
            int newfib = prev + current;
            prev = current;

            current = newfib;
        }
    }
}
