using System;
namespace CSharp_Shell
{
	public class program
	{
		public virtual void showinfo()
		{
		Console.WriteLine("base class method");
		}
	}
	class B:program
	{
		public override void showinfo()
		{
			Console.WriteLine("derived class method");
		}
		public static void Main()
		{
			B b1=new B();
			b1.showinfo();
			b1.showinfo();
		}
	}
	}
