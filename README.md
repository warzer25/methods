# methods
//static void Main(string[] args)
        //static void Main(string[] args)
        //{
        //    displaymessage();

        //}
        //public static void displaymessage()
        //{
        //    Console.WriteLine("hello");
        //}

        //----------------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    add(5, 10);

        //}
        //public static void add(int num1, int num2)
        //{
        //    int answer = num1 + num2;
        //    Console.WriteLine(answer);
        //}

        //----------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //   int answer = add(5, 10);
        //   int secendanswer = add(answer,5);
        //    Console.WriteLine(answer);
        //    Console.WriteLine(secendanswer);

        //    Console.ReadLine();
        //}
        //public static int add(int num1, int num2)
        //{
        //    int answer = num1 + num2;
        //    return answer;
        //}

        //----------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    int studintgrade =77;
        //    Console.WriteLine("studint gradebe after for {0}", studintgrade);
        //    giveextracreid(studintgrade);
        //    Console.WriteLine("studint gradebe after for {0}", studintgrade);

        //}
        //public static void giveextracreid(int studintgrade)
        //{
        //    studintgrade += 3;
        //    Console.WriteLine("studint gradebe inside for {0}", studintgrade);

        //}

        //---------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    int[] grades = new int[1];
        //    grades [0] = 77;
        //    Console.WriteLine("studint gradebe befor for {0}", grades[0]);
        //    giveextraarray(grades);
        //    Console.WriteLine("studint gradebe after for {0}", grades[0]);
        //    Console.ReadLine();
        //}
        //public static void giveextraarray(int[]grades)
        //{
        //    grades[0] += 3;

        //}

        //-----------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    int studintgrade = 77;

        //    giveextracreid(ref studintgrade);
        //    Console.WriteLine(studintgrade);
        //    Console.ReadLine();
        //}
        //public static void giveextracreid(ref int studintgrade)
        //{
        //    studintgrade += 3;

        //}

        //--------------------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    int studintgrade;

        //    giveextracreid(out studintgrade);
        //    Console.WriteLine(studintgrade);
        //    Console.ReadLine();
        //}
        //public static void giveextracreid(out int studintgrade)
        //{
        //    studintgrade = 0;
        //    studintgrade += 3;

        //}

        //----------------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    int add;
        //    int mult;
        //    addandmult (5,10,out add, out mult);
        //    Console.WriteLine(add);
        //    Console.WriteLine(mult);
        //    Console.ReadLine();
        //}
        //public static void addandmult (int a,int b ,out int added ,out int mult)
        //{
        //    added = a + b;
        //    mult = a * b;

        //}

        //---------------------------------------------------------------------------//


        //static void Main(string[] args)
        //{
        //    Console.WriteLine("{0},{1},{2}",1,2,3);

        //    Console.ReadLine();

        //}


        //static void Main(string[] args)
        //{
        //    for (int i = 0; i < 5; i++)
        //    {

        //        Console.Write("{0},{0}", i);

        //    }
        //    Console.ReadLine();
        //}

        //--------------------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    int[] myarray = {1,2,3,4,6,5,10};
        //    printarray(myarray);
        //    printarray(2,1,3,5,7,4,3,5,7);
        //    Console.ReadLine();

        //}
        //public static void printarray (params int[] array)
        //{
        //    for (int i = 0; i < array.Length;i++)
        //    {

        //        Console.Write("{0}",array[i]);
        //        Console.Write("{0}",",");

        //    }


        //}

        //------------------------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    add(5,6);
        //    add("b", "a");
        //    add(5.2, 6.3);


        //    Console.ReadLine();
        //}
        //public static void add(int a,int b)
        //{
        //    int answer = a + b;
        //    Console.WriteLine(answer);

        //}
        //public static void add(string a, string b)
        //{
        //    string answer = a + b;
        //    Console.WriteLine(answer);

        //}
        //public static void add(double a, double b)
        //{
        //    double answer = a + b;
        //    Console.WriteLine(answer);

        //}

        //------------------------------------------------------------------------------//

        //static void Main(string[] args)
        //{
        //    add(5);
        //    add(5,z:5);

        //    Console.ReadLine();
        //}
        //public static void add(int x, int y =1 ,int z=2 )
        //{
        //    int answer = x + y + z;
        //    Console.WriteLine(answer);
        //}
