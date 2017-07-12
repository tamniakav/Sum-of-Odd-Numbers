# Sum-of-Odd-Numbers
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Sum_of_Odd_Numbers
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());
            int sum = 0;
            int num = -1;

            for (int i = 0; i < n; i++)
            {
                num += 2;
                Console.WriteLine(num);
                sum += num;                
            }
            Console.WriteLine($"Sum: {sum}");
        }
    }
}
