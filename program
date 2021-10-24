using System;
using System.Collections.Generic;

namespace Ex3_C
{
    class Program
    {
        static void Main(string[] args)
        {
            Options options = new Options();

            var candidat = new List<Candidats>() {
                new Candidats(1,new List<String>(){ options.o1, options.o2, options.o3 }),
                new Candidats(2,new List<String>(){ options.o2, options.o3, options.o1 }),
                new Candidats(3,new List<String>(){ options.o3, options.o2, options.o1 }),
                new Candidats(4,new List<String>(){ options.o1, options.o2, options.o3 }),
                new Candidats(5,new List<String>(){ options.o2, options.o1, options.o3 }),
                new Candidats(6,new List<String>(){ options.o2, options.o1, options.o3 }),
                new Candidats(7,new List<String>(){ options.o3, options.o2, options.o1 }),
                new Candidats(8,new List<String>(){ options.o1, options.o2, options.o3 }),
                new Candidats(9,new List<String>(){ options.o2, options.o1, options.o3 })
            };

            List<int> liste1 = new List<int>()
            {

            };
            List<int> liste2 = new List<int>()
            {

            };
            List<int> liste3 = new List<int>()
            {

            };
            int i = 0;

            
                foreach (var x in candidat)
                {
                    if (x.Choise[0] == options.o1)
                    {

                        liste1.Add(x.id);

                    }
                    else
                    {
                        if (x.Choise[0] == options.o2)
                        {

                            liste2.Add(x.id);


                        }
                        else
                        {
                            if (x.Choise[0] == options.o3)
                            {

                                liste3.Add(x.id);


                            }
                        }
                    }
                    i++;
                }
           





            Console.WriteLine("liste 1");
            foreach (var a in liste1)
                Console.WriteLine(a);
            Console.WriteLine("liste 2");
            foreach (var b in liste2)
                Console.WriteLine(b);
            Console.WriteLine("liste 3");
            foreach (var c in liste3)
                Console.WriteLine(c);

        }
    }
    class Candidats
    {
        public int id { get; set; }
        public List<String> Choise { get; set; }
        public Candidats(int idd, List<String> choise)
        {
            this.id = idd;
            this.Choise = choise;
        }
    }
    class Options
    {
        public String o1 = "option 1";
        public String o2 = "option 2";
        public String o3 = "option 3";
    }
}
