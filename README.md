# Arrays

 <ul style="list-style-type: none; margin: 0; padding: 0; ">
  <li style="display: inline;"><a href="https://tundetubo.github.io"><img src="home.png" alt="home-page" style="width:40px; height:40px;"/></a></li>
  <li style="display: inline;"><a href="#"><img src="about-us.png" alt="about-us" style="width:40px; height:40px;"/></a></li>
  <li style="display: inline;"><a href="mailto:tunde.tubo@gmail.com"><img src="email.png" alt="contact-us" style="width:40px; height:40px;"/></a></li>
</ul> 

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