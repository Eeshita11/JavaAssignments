# package Package1;

public class sumofOdd 
{
	void sumofOdd()
	{
		int sum=0;
		System.out.println("Sum of odd numbers between 7 to 21");
		for(int i=7;i<=21;i++)
		{
			if(i%2!=0)
			{
				sum=sum+i;
			}
		}
		System.out.println("sum=" +sum);
	}
	public static void main(String[] args) 
	{
		sumofOdd so=new sumofOdd();
		so.sumofOdd();
		
	}
}
	
