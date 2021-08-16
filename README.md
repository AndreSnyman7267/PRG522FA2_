# PRG522FA2_
using System;

namespace PRG522_FA2
{
    class Program
    {
        // function without any return type declaration  
        public void square(int nmbr)
        {
            int sq = nmbr * nmbr;
            Console.WriteLine("Square of the given number is  " + sq);

            // Don’t provide any return statement  
        }

        public static void Main(string[] args)
        {
            Program pr = new Program(); // Creating a class Object  
            pr.square(2); //calling the method
        }
    }
