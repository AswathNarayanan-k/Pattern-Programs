package aaaaaa;

public class Pattern1 {
  public static void main(String args[])
  {
	  
	  
	  int n=10;
	  for(int i=1;i<=n;i++)
	  {
		  if(i<=n/2)
			for(int j=0;j<i;j++)
			 System.out.print("* ");	
		  else
			  for(int j=n-i;j>0;j--)
				  System.out.print("* ");	
		  System.out.println();		 
	  }
  }
}
