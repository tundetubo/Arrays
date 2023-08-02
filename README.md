# Arrays

[<svg xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 576 512"><!--! Font Awesome Free 6.4.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2023 Fonticons, Inc. --><path d="M575.8 255.5c0 18-15 32.1-32 32.1h-32l.7 160.2c0 2.7-.2 5.4-.5 8.1V472c0 22.1-17.9 40-40 40H456c-1.1 0-2.2 0-3.3-.1c-1.4 .1-2.8 .1-4.2 .1H416 392c-22.1 0-40-17.9-40-40V448 384c0-17.7-14.3-32-32-32H256c-17.7 0-32 14.3-32 32v64 24c0 22.1-17.9 40-40 40H160 128.1c-1.5 0-3-.1-4.5-.2c-1.2 .1-2.4 .2-3.6 .2H104c-22.1 0-40-17.9-40-40V360c0-.9 0-1.9 .1-2.8V287.6H32c-18 0-32-14-32-32.1c0-9 3-17 10-24L266.4 8c7-7 15-8 22-8s15 2 21 7L564.8 231.5c8 7 12 15 11 24z"/></svg>](https://tundetubo.github.io)

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

<div class="footer">
  
  <hr style="width:200; background-color: blue;">

 <div>
   <p>Terms and conditions</p>
   <p>License agreement</p>
   <p>Privacy policy</p>
   <p>Cookies policy</p>
   <p style="color:blue;">Tiberus 2023</p>
 </div>
 <div style="text-align: center">

    <a style="padding:10px; "><img src="https://i.ibb.co/bPLzh61/circle-facebook.png" alt="Facebook" title="Facebook" style="width:32px; border:0; text-align: center;" ></a>  
    <a style="padding:10px; "><img src="https://i.ibb.co/sRH7TK2/circle-twitter.png" alt="twitter" style="width:32px; border:0;" ></a>
    <a style="padding:10px; "><img src="https://i.ibb.co/VQ9nCv3/circle-youtube.png" alt="youtube" style="width:32px; border:0;" ></a>
    <a style="padding:10px; "><img src="https://i.ibb.co/K5wbWBS/circle-linkedin.png" alt="linkedin" style="width:32px; border:0;" ></a> 
    <a style="padding:10px; "><img src="https://i.ibb.co/x8G1NMz/circle-instagram.png" alt="instagram" style="width:32px; border:0;" ></a>
 </div>
</div>