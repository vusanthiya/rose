public class CountDigits
{
  public class void main(String args[])
  {
    int count=0,a=12345;
    while(a!=0)
    {
      a=a/10;
      ++count;
     }
    System.out.println("Number of digits :" + count);
   }
  }
