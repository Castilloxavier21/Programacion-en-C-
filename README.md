# Programacion-en-C-
Programcion básica en C# gestión 2018
//sumar dos numeros
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int x,y,r;
            Console.WriteLine("Ingrese el primer número: ");
            x = int.Parse(Console.ReadLine());
              Console.WriteLine("Ingrese el segundo número: ");
            y = int.Parse(Console.ReadLine());
            r=x+y;
            Console.WriteLine("El resultados es: " + r);
        }
    }
}

//mayor de dos numeros
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int x,y;
            Console.WriteLine("Ingrese el primer número: ");
            x = int.Parse(Console.ReadLine());
              Console.WriteLine("Ingrese el segundo número: ");
            y = int.Parse(Console.ReadLine());
          if(x>y){
               Console.WriteLine("El mayor es : " + x);
          }
          else{
            Console.WriteLine("El mayor es: " + y);
        } }
    }
}
//numeros par && impar
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int x,r;
            Console.WriteLine("Ingrese el primer número: ");
            x = int.Parse(Console.ReadLine());
            r=x%2;
            if(r==0)
            {
                    Console.WriteLine("Es par");
            }
            else
            {
                    Console.WriteLine("Es impar");
            }
        } 
    }
}
//Numeros Impares error en codigo

using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int x,i,r,ac;
            i=1;
            ac=0;
            Console.WriteLine("Ingrese el primer número: ");
            x = int.Parse(Console.ReadLine());
           while(i <= x){
               r = i%2;
            if(r == 1){
                 ac= ac+i;
                 i=i+1;
               }
               
           
           }
            Console.WriteLine("Los Numeros Impares son: " + ac);
            
        } 
    }
}

//contar digitos de un Numero

using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int n,c,r;
            c=0;
            Console.WriteLine("Ingrese un número: ");
            n = int.Parse(Console.ReadLine());
           while(n>0){
               r = n%10;
               n=(n-r)/10;
               c=c+1;
           
               
           
           }
            Console.WriteLine("La cantidad de digitos son: " + c);
            
        } 
    }
}

//menor digito de un numero
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int n,m,r;
           m=9;
            Console.WriteLine("Ingrese un número: ");
            n = int.Parse(Console.ReadLine());
           while(n>0){
               r = n%10;
               n=(n-r)/10;
               if(r<=m)
               {
                   m=r;
               }
             
           
               
           
           }
            Console.WriteLine("El menor digito es: " + m);
            
        } 
    }
}

//mayor digito de un numero

using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int n,m,r;
           m=1;
            Console.WriteLine("Ingrese un número: ");
            n = int.Parse(Console.ReadLine());
           while(n>0){
               r = n%10;
               n=(n-r)/10;
               if(r>=m)
               {
                   m=r;
               }
             
           
               
           
           }
            Console.WriteLine("El mayor digito es: " + m);
            
        } 
    }
}

// sumar numeros pares de un serie
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int n,ac,i,r;
           i=1;
           ac=0;
            Console.WriteLine("Ingrese un número: ");
            n = int.Parse(Console.ReadLine());
           while(i<=n){
               r = i%2;
               if(r==0)
               {
                   ac=ac+i;
               }
               i=i+1;
             
           
               
           
           }
            Console.WriteLine("El suma de numeros pares son: " + ac);
            
        } 
    }
}

// sumar numeros impares de un serie
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int n,ac,i,r;
           i=1;
           ac=0;
            Console.WriteLine("Ingrese un número: ");
            n = int.Parse(Console.ReadLine());
           while(i<=n){
               r = i%2;
               if(r==1)
               {
                   ac=ac+i;
               }
               i=i+1;
             
           
               
           
           }
            Console.WriteLine("El suma de numeros impares son: " + ac);
            
        } 
    }
}

//multiplicaciónde un serie 1*2*3*4=24
using System;

namespace myApp
{
    class Program
    {
        static void Main(string[] args)
        {
            int n,ac,i;
           i=1;
           ac=1;
            Console.WriteLine("Ingrese un número: ");
            n = int.Parse(Console.ReadLine());
           while(i<=n){
               ac=ac*i;
                i=i+1;
           }
            Console.WriteLine("El Producto  de una serie es: " + ac);
            
        } 
    }
}



