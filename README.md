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
}

<!-- Multidaimensonal ArrayList -->
    ArrayList<ArrayList<Integer>> mainlist = new ArrayList<>();
	
	// one list 
	
     ArrayList<Integer> list = new ArrayList<>();
	 list.add(1);   
	 list.add(2);
	 mainlist.add(list);
	 
	//second list 
	
   ArrayList<Integer> list2 = new ArrayList<>();
	 list2.add(3);
	 list2.add(6);
	 mainlist.add(list2);
	 
	 .../ print list 
	 for(int i=0;i<mainlist.size();i++)
	{
	    System.out.println(mainlist.get(i)+" ");
	    
	}
						
	 















