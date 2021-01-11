# Perimeter and area of triangle 
public class Triangle
{
	public Triangle()
	{
		double perimeter,area;
		//sides are given
		int s1=3,s2=4,s3=5;
		perimeter=s1+s2+s3;
		//s is for finding area using Heron's formula
		double s=perimeter/2;
		area=Math.sqrt(s*(s-s1)*(s-s2)*(s-s3));
		System.out.println("Perimeter of triangle is "+perimeter);
		System.out.println("Area of triangle is "+area);

	}

	public static void main(String args[])
{
	Triangle obj=new Triangle();
}
}
