```c#
using System;

namespace progcont

{

class Program

{

static void fibonacci()

{

double x = 0, y = 1,limit, aux = 1;

Console.WriteLine(&quot;Enter a lenght of numbers for fibonacci&quot;);

limit = int.Parse(Console.ReadLine());

for(double i = 2; i < limit ; i++)

{

aux = x + y;

y = aux;

Console.Write (y + " ");

}

Console.Readkey();

}

static void primescont()

{

Console.WriteLine("Enter a Number: ");

double x;

x = double.Parse(Console.ReadLine());

for (double i = 2; i <= x; i = i + 1)

{

if ((i % 2 != 0)|| (i==2))

{

Console.Write("{0} ", 1);

}

}

Console.ReadKey();

}

static void naturalcont()

{

Console.WriteLine(&quot;Please Enter a number:&quot;);

int x = int.Parse(Console.ReadLine());

for (int i = 0; i <= x; i++)

{

Console.WriteLine(i);

}

Console.ReadKey();

}

static void Main(string[] args)

{

naturalcont();

primescont();

fibonacci();

}

}

}
```

https://youtu.be/8dxLsmEv1-Y

Playlist: https://www.youtube.com/playlist?list=PL5K8kPa4QpEFWJnPREdQi_VxooLGl57m7