# Arrays
<hr style="width:200; background-color: blue;">
package searching_array;

public class SearchingArray_caused_ArrayIndexOutOfBoundsException {
	
	static int []intNumbers = {1, 2, 3};

	public static void main(String[] args) {
		/*causes Exception in thread "main" java.lang.ArrayIndexOutOfBoundsException: 
		Index 3 out of bounds for length 3 */
		 for(int i : intNumbers){
		if(intNumbers[i]== 4){
			System.out.println(4+" is present");
		}else {
			System.out.println(4+" is not present");
		}
	 }
	}	 
}
