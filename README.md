# calculadora
<html>
<CENTER>
<FORM NAME="Calculadora">
<TABLE BORDER=4 WIDTH="155" bgcolor="green">
	<TR>
		<TD ALIGN="CENTER">
			<INPUT TYPE="text"  NAME="Input" SIZE="16">
		</TD>
	</TR>
	<TR>
		<TD ALIGN="CENTER">
			<INPUT TYPE="button" NAME="one"
			VALUE="  1  " onClick="Calculadora.Input.value += '1'">
			<INPUT TYPE="button" NAME="two"
			VALUE="  2  " onClick="Calculadora.Input.value += '2'">
			<INPUT TYPE="button" NAME="three"
			VALUE="  3  " onClick="Calculadora.Input.value += '3'">
			<INPUT TYPE="button" NAME="plus"
			VALUE="  +  " onClick="Calculadora.Input.value += ' + '">
			<BR>
			<INPUT TYPE="button" NAME="four"
			 VALUE="  4  " onClick="Calculadora.Input.value += '4'">
			 <INPUT TYPE="button" NAME="five"
			 VALUE="  5  " onClick="Calculadora.Input.value += '5'">
			 <INPUT TYPE="button" NAME="six"
			 VALUE="  6  " onClick="Calculadora.Input.value += '6'">
			 <INPUT TYPE="button" NAME="minus"
			 VALUE="  -   " onClick="Calculadora.Input.value += ' - '">
			<BR>
			 <INPUT TYPE="button" NAME="seven"
			 VALUE="  7  " onClick="Calculadora.Input.value += '7'">
			 <INPUT TYPE="button" NAME="eight"
			 VALUE="  8  " onClick="Calculadora.Input.value += '8'">
			 <INPUT TYPE="button" NAME="nine"
			 VALUE="  9  " onClick="Calculadora.Input.value += '9'">
			 <INPUT TYPE="button" NAME="times"
			 VALUE="  x  " onClick="Calculadora.Input.value += ' * '">
			<BR>
			<INPUT TYPE="button" NAME="clear"
			 VALUE="  c  " onClick="Calculadora.Input.value = ''">
			 <INPUT TYPE="button" NAME="zero"
			 VALUE="  0  " onClick="Calculadora.Input.value += '0'">
			 <INPUT TYPE="button" NAME="DoIt"
			 VALUE="  =  " onClick="Calculadora.Input.value = eval(Calculadora.Input.value)">
			 <INPUT TYPE="button" NAME="div"
			 VALUE="  /   " onClick="Calculadora.Input.value += ' / '">
		</TD>
	</TR>
</TABLE>
</FORM>
</CENTER>
</html>
