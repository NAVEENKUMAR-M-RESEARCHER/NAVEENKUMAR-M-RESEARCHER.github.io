<html>
 <head>
      <title>Teaching/Learning tool (HTML)</title>
     <style>
	   h1
	   {
	     font-family: Segoe Print;
         font-size:40px;
	     color:white;
	   }
	   h3{color:white;font-family: Segoe Print;}
	   .t
	    {
		  color:white;
		}
		#b2
		{
		  background-color:#33ADAD;
		  height: 50px;
		  width: 150px;
		}
		#b2:hover
		{
		  background-color:#1A8E88;
		}
		#b3
		{
		  background-color:#33ADAD;
		  height: 50px;
		  width: 100px;
		}
		#b3:hover
		{
		  background-color:#1A8E88;
		}
	 </style>
	 <script>
	     function bas()
		 {
	        document.getElementById("h").innerHTML = "<embed SRC=basics.html  WIDTH=90% HEIGHT=90%>"
	     }
		 function tab()
		 {
		    document.getElementById("h").innerHTML = "<embed SRC=table.html  WIDTH=90% HEIGHT=90%>"

	     }
		 function fm()
		 {
		    document.getElementById("h").innerHTML = "<embed SRC=form.html  WIDTH=90% HEIGHT=90%> "

	     }
		 function adv()
		  {
		   document.getElementById("h").innerHTML = "<embed SRC=advance.html  WIDTH=90% HEIGHT=90%>"
		  } 
	 </script>
  </head>
<body> 
<div class="head" style="background-color:#33ADAD;width:100%;height:25%;">

<center>
     <h1><i>HTML:Teaching/Learning tool, SRM University</i></h1>
	 <table border=0 class="t" width="35%" height="15%">   
   <tr> 
        <td align="center"><button  id="b2" onclick="bas()"><h3>HTML Basics</h3></button></td>
        <td align="center"><button  id="b3" onclick="tab()"><h3>Tables</h3></button></td>
        <td align="center"><button  id="b3" onclick="fm()"><h3>Forms</h3></button></td>
        <td align="center"><button  id="b2" onclick="adv()"><h3>HTML Advanced</h3></button></td>		
   </tr>
   </table>	
</center>
</div>
<div class="home" style="background-color:	#D4D4D4;width:100%;height:72%;">
<p id="h">
<br>&nbsp;<strong>HTML-Hyper Text Markup Language</strong><br><br>
<table border="0"width="100%" height="50%">
<tr>
  <td width="20%" height-"50%"><img src="lee.jpg" width="200"></img><br>Berners Lee-Founder of HTML</td>
  <td valign="top">What is HTML?<br><br>
H-T-M-L are initials that stand for HyperText Markup Language. Let me break it down for you:<br><br>
<strong><b>Hyper</b> </strong>is the opposite of linear. It used to be that computer programs had to move in a linear fashion. This before this, this before this, and so on.
 HTML does not &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;hold to that pattern and allows the person viewing the World Wide Web page to go anywhere, any time they want.<br>
<strong>Text</strong> is what you will use. Real, honest to goodness English letters.<br>
<strong>Mark up </strong>is what you will do. You will write in plain English and then mark up what you wrote. More to come on that in the next Primer.<br>
<strong>Language</strong> because they needed something that started with "L" to finish HTML and Hypertext Markup Louie didn't flow correctly.</td>
</tr>
</table>
</p>
</div>		 


</body>
</html>
