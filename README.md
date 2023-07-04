# Arrays
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
<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

.row::after {
  content: "";
  clear: both;
  display: block;
}

[class*="col-"] {
  float: left;
  padding: 15px;
}

html {
  font-family: "Lucida Sans", sans-serif;
}

body {
   background: linear-gradient(to right, #f0f0f5 25%, #d1d1e0 50%, #b3b3cb 100%);

}

.header {
  background: linear-gradient(to right, #8a00e6 25%, #9933ff 50%, #5c0099 100%);
  color: #f2e6ff;
  text-shadow: 2px 2px 4px #000000;
  padding: 15px;
}

.menu ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.menu li {
  padding: 8px;
  margin-bottom: 7px;
  background: linear-gradient(to right, #8a00e6 25%, #9933ff 50%, #5c0099 100%);
  color: #ffffff;
  box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
}

.menu li:hover {
  background:linear-gradient(to right, #d633ff 25%, #8f00b3 50%, #3d004d 100%);
}

.aside {
  background-color: #33b5e5;
  padding: 15px;
  color: #ffffff;
  text-align: center;
  font-size: 14px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
}

.footer {
  background: linear-gradient(to right, #8a00e6 25%, #9933ff 50%, #5c0099 100%);
  color: #ffffff;
  text-align: left;
  font-size: 12px;
  padding: 15px;
}

/* For desktop: */
.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}

table, th, td{
text-align: center;
color: #9900cc;
}

tr:nth-child(even) {
background-color: #E6E6FA;
color: #f2e6ff;
}

@media only screen and (max-width: 768px) {
  /* For mobile phones: */
  [class*="col-"] {
    width: 100%;
  }
}

@media only screen and (max-width: 300px) {
  /*For small mobile phones: */
  [class*="col-"] {
    width: 100%;
  }
  .header{
    font-size: 7px;
  }
  .menu{
    font-size: 6.5px;
  }
  .col-6{
    font-size: 6.8px;
    background: black;
    color: white;
  }
  
  img {
  width: 100%;
  height: auto;
}
}

img {
  width:100%;
  height:auto;
}

.lineHorizontal{
   width: 100%;
   height: 1px; 
   background: linear-gradient(to right, #d633ff 25%, #8f00b3 50%, #3d004d 100%); 
}

th {
 background-color : #4B0082;
 color : white;
}
</style>
<title>Responsive Tables</title>
</head>
<body>
  <div class="header">
    <h1>Java Odyssey</h1>
  </div>
  <div class="row">
  <div class="col-3 menu">
    <ul>
    <li>Home</li>
    <li><a href="https://tundetubo.github.io/JavaMail/">Java mail</a></li>
    <li><a href="https://tundetubo.github.io/Arrays/">Arrays</a></li>
    <li></li>
    </ul>
  </div>
  
  <div class="col-6">
    <h3></h3>
    <table>
     <tr><th></th><th>Id</th><th>Name</th><th>Category</th><th>Format</th><th>Author</th>
    </tr>
     <tr>
       <td><img src=" "/></td>
       <td>Id</td>
       <td></td>
       <td></td>
       <td></td>
       <td></td>
    </tr>
  
    </table>
    
  </div>
      
</div>


<div class="footer">
  <p>Terms and conditions</p>
  <p>License agreement</p>
  <p>Privacy policy</p>
  <p>Cookies policy</p>
  <div class="lineHorizontal"></div>
  <p>Tiberus 2023</p>
  <div style="text-align: center">

    <a style="padding:10px; "><img src="https://i.ibb.co/bPLzh61/circle-facebook.png" alt="Facebook" title="Facebook" style="width:32px; border:0; text-align: center;" ></a>  
    <a style="padding:10px; "><img src="https://i.ibb.co/sRH7TK2/circle-twitter.png" alt="twitter" style="width:32px; border:0;" ></a>
    <a style="padding:10px; "><img src="https://i.ibb.co/VQ9nCv3/circle-youtube.png" alt="youtube" style="width:32px; border:0;" ></a>
    <a style="padding:10px; "><img src="https://i.ibb.co/K5wbWBS/circle-linkedin.png" alt="linkedin" style="width:32px; border:0;" ></a> 
    <a style="padding:10px; "><img src="https://i.ibb.co/x8G1NMz/circle-instagram.png" alt="instagram" style="width:32px; border:0;" ></a>
 </div>
</div>

</body>
</html>
