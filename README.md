# formularioALBB7
Clase de programación
<!DOCTYPE html>
<html>
<meta charset="utf-8">
<head>
	<title>Formulario/Curriculum Vitae</title>
    <script type="text/javascript" src="Andrea_Bordones_27521576_G1/jquery-1.12.4.min.js"></script>
</head>
<link rel="stylesheet" type="text/css" href="andrea_css2.css">
<body>
    <script src="js/Andrea.js"></script>
	<!--Nombre e imagen-->
	<h1 align="left"><font color="white">Curriculum Vitae</font></h1>
	<img class="img" src="C:\Users\Andrea\Documents\Ejercicios de progra\letter B typography f.png" width="330px" height="330px">
        <!--Ingreso de datos personales-->
        <h4 align="left">Personal Information</h4>
            <table widht="100%" id="otros_campos" name="ADD" value="ADD">
                <tr id="f1'+i+'">
                    <td align="center">
                    	<form><label for="Name"><font color="#28004D">Names</font> <br />
		    	    <input type="text" id="First_Second_Name" name="User_Name" placeholder="Example: Angela/Julián" style="width: 300px; height: 20px"></label>
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
		    	    </td></tr>

		            <tr id="f2'+i+'">
                        <td align="center">
                            <label for="Name"><font color="#28004D">Surnames</font> <br />
		    	    <input type="text" id="Surnames" name="User_Name" placeholder="Example: López/Rodríguez" style="width: 300px; height: 20px"></label>
                    <input onclick="otros_campos();" type="button"name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
		    	    </td></tr>
		        
		            <tr><td align="center"><label for="Cedula_Identidad"><font color="#28004D">C.I.</font> <br />
		    	    <input type="number" id="number" maxlength="10" name="Cedula_Identidad" placeholder="00.000.000" style="width: 200px; height: 20px">
                    
		    	    <select name="nationaly" id="nationality" title="select your nationality" style="width: 35px; height: 36px">

                    <option value="V" title="venezolan@">V</option>
                    <option value="E" title="extranjer@">E</option>
                    <option value="J" title="juridico">J</option>
                    <option value="G" title="gubernamental">G</option></select></label></td></tr>

                    <tr><td align="center">
                    	<label for="Date"><font color="#28004D">Date of Birth</font> <br />
        		            <input type="Date" name="User_Date" min="2003-01-01" max="1997-01-01" style="width: 200px; height: 20px"></label>
        		    </td></tr>

                    <tr><td align="center"><label for="Name"><font color="#28004D">Place of Birth</font> <br />
		    	 	<input type="text" id="User_Place_Birth" name="User_Place_Birth" placeholder="Example: Caracas, Venezuela" style="width: 300px; height: 30px"></label>
		    	    </td></tr>

		            <tr><td align="center"><label for="Name"><font color="#28004D">Direction</font> <br />
		    	    	<textarea placeholder="Street Place Name n° 20" style="width: 300px; height: 30px"></textarea>
		    	    </label>
		    	    </td></tr>

		            <tr id="f3'+i+'"><td align="center"><label for="Tel"><font color="#28004D">Phone</font> <br />
        		    <input type="tel" id="tel" name="User_tel" maxlength="11" placeholder="555.555.1211" style="width: 300px; height: 30px"></label>
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <!--value="+58"-->
        		    </td></tr>

                    <tr><td align="center"><label for="Tel"><font color="#28004D">Cell phone</font> <br />
        		    <input type="tel" id="tel" name="User_Cell" maxlength="11"placeholder="555.555.1211" style="width: 300px; height: 30px"></label></td></tr>

		            <tr><td align="center"><label for="mail"><font color="#28004D">E-mail</font> <br />
        		    <input type="text" id="email" name="email" placeholder="example@email.com" style="width: 300px; height: 30px"></label>
        		    </td></tr>

        		<tr>
        	        <td align="center">
        	        	<label for="Civil_Status"><font color="#28004D">Civil Status:</font>
        		            <input input type="radio" name="Civil_Status" id="Civil_Status" size="40px"></label>
        		                <label for="Civil_Status">Single</label>
        		            <input type="radio" name="Civil_Status" id="Civil_Status">
			                    <label for="Civil_Status">Married</label>
        		    </td>
        		</tr>
        		<tr>
        	        <td align="center">
        	        	<label for="Gender"><font color="#28004D">Gender: 
        		            <input input type="radio" name="Gender" id="Gender" size="40px"></label>
        		                <label for="Gender">Male</label>
        		            <input type="radio" name="Gender" id="Gender">
			                    <label for="Gender">Female</label>
			        </form>
        		    </td>
        		</tr>
            </table>
        <!--Estudios Realizados-->
            <h4 align="left">Performed Studies</h4>
            <table class="Performed" id="otros_campos" name="ADD" value="ADD">
                <tr id="f4'+i+'">
                    <th align="center">
                    <form><label for="Name"><font color="#28004D">Grado Obtenido</font> <br />
                    <input type="text" id="Primary" name="Primary" placeholder="Degree" style="width: 300px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Name"><font color="#28004D">Nombre de la Escuela</font> <br />
                    <input type="text" id="School_Name" name="School_Name" placeholder="Institute" style="width: 300px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Name"><font color="#28004D">Tiempo Cursado</font> <br />
                    <input type="text" id="Primary" name="Primary" placeholder="January 2006 - July 2011" style="width: 300px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                </tr>
            </table>
            <!--Cursos Realizados-->
            <h4 align="left">Courses Taken</h4>
            <table widht="100%" class="Cursos" id="otros_campos" name="ADD" value="ADD">
                <tr id="F5'+i+'">
                    <th align="center">
                        <form><label for="Name"><font color="#28004D">Location</font> <br />
                    <input type="text" type="button" id="Place_Name" name="Place_Name" placeholder="Place Name" style="width: 210px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Institute</font> <br />
                    <input type="text" id="Institute_Name" name="Institute_Name" placeholder="Institute Name" style="width: 240px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Curse</font> <br />
                    <input type="text" id="Curse_Name" name="Curse_Name" placeholder="Curse Name" style="width: 220px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Time Spent</font> <br />
                    <input type="text" id="Cursed_Time" name="Cursed_Time" placeholder="July 2021 - May 2023" style="width: 210px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                </form>
                    </th>
                </tr>
            </table>
            <!--Experiencia Laboral-->
            <h4 align="left">Work Experience</h4>
            <table widht="100%" class="Work" id="otros_campos" name="ADD" value="ADD">
                <tr id="F6'+i+'">
                    <th align="center">
                        <form><label for="Name"><font color="#28004D">Location</font> <br />
                    <input type="text" id="Place_Name" name="Place_Name" placeholder="Caracas" style="width: 200px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Comapny Name</font> <br />
                    <input type="text" id="Company_Name" name="Company_Name" placeholder="Comapny Name" style="width: 230px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Completed Tasks</font> <br />
                    <input type="text" id="Completed_Tasks" name="Completed Tasks" placeholder="Completed Tasks" style="width: 200px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>
                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Time Worked</font> <br />
                    <input type="text" id="Worked_Time" name="Worked_Time" placeholder="September 2024 - January 2024" style="width: 250px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                </form>
                    </th>
                </tr>
            </table>
            <!--Referencis Personales-->
            <h4 align="left">Personal Reference</h4>
            <table widht="100%" class="Reference" id="otros_campos" name="ADD" value="ADD">
                <tr id="F7'+i+'">
                    <th align="center">
                        <form><label for="Name"><font color="#28004D">Person Name</font> <br />
                    <input type="text" id="Person_Name" name="Person_Name" placeholder="Person Name" style="width: 250px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>

                    <th align="center">
                        <label for="Cedula_Identidad"><font color="#28004D">C.I.</font> <br />
                    <input type="text" id="number" maxlength="10" name="Cedula_Identidad" placeholder="00.000.000" style="width: 180px; height: 25px">
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    
                    <select name="nationaly" id="nationality" title="select your nationality" style="width: 35px; height: 25px">

                    <option value="V" title="venezolan@">V</option>
                    <option value="E" title="extranjer@">E</option>
                    <option value="J" title="juridico">J</option>
                    <option value="G" title="gubernamental">G</option></select></label></th>

                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">email</font> <br />
                    <input type="text" id="email" name="email" placeholder="example@email.com" style="width: 250px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                    </th>

                    <th align="center">
                        <form><label for="Curse"><font color="#28004D">Phone</font> <br />
                    <input type="tel" id="tel" name="Phone" placeholder="555.555.1211" style="width: 200px; height: 25px"></label>
                    <input type="button" name="ADD" id="otros_campos" value="ADD">
                    <input onclick="otros_campos();" type="button" name="delete" id="delete" styke="background-color: red"; color="white" value="delete" onclick="eliminar_campos('+i+')">
                </form>
                    </th>
                </tr>
            </table>
            <!--Idiomas-->
            <h4>Idioms</h4>
            <table widht="100%" class="Language">
                <tr>
                    <td align="left">
                            <input type="checkbox" name="idiom" value="English"/>English</br>
                            <input type="checkbox" name="idiom" value="German"/>German</br>
                            <input type="checkbox" name="idiom" value="Spanish"/>Spanish</br>
                    </td>
                </tr>
        </table>
</body>
</html>

<script src="js/Andrea.js">

</script>