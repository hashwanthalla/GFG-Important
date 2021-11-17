class Largest
{
    
    public static String findLargestNumber(ArrayList<Integer> A)
    {
     String res ="";
       Collections.sort(A,new Comparator<Integer>()
       {
           @Override
           public int compare(Integer a, Integer b)
           {
               String c1 = String.valueOf(a)+String.valueOf(b);
               String c2 = String.valueOf(b)+String.valueOf(a);
           
              if(c1.compareTo(c2)>0)
              {
                  return -1;
              }
              else if(c1.compareTo(c2)<0)
              {
                  return 1;
              }
              else
              {
                  return 0;
              }
              
           }
       });
          Iterator it = A.iterator();
          while(it.hasNext())
          {
          res= res+String.valueOf(it.next());
          }
        return res;
    }
    
}
