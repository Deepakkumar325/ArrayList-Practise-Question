# ArrayList-Practise-Question

import java.util.ArrayList;

public class Main
{
public static void main(String[] args) {
	    // java Collections Framework
	    
	 ArrayList<Integer> list = new ArrayList<>();
	  
	  //add opeation 
	  
	 list.add(1);  // time complexity add()  O(1)
	 list.add(2);
	 list.add(3);
	 list.add(4);
	  
	  list.add(3,6);// index value give
	  
	 //get element O(1)
   
	 int ans = list.get(2);
	 System.out.println(ans);
      
      //delete o(n)
      
      list.remove(2);
      System.out.println(list);
   	 
   	  //set element at Index O(n)
   	  list.set(2,10);
   	  System.out.println(list);
	 
	 // contains O(n) 
	 System.out.println(list.contains(2));  // return true and false
	 
	 
	 // list size 
	 System.out.println( "list size: "+list.size());
	 
	 for(int i=0;i<list.size();i++){
	     System.out.println(list.get(i) +" "+);
	 }
	 // Sorting assending order
	 Collections.sort(list,collections.reverseorder())
	}
}
