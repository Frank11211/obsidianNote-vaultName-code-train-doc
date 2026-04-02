<h4>Basic Command</h4>
<table>
	<tr>
		<th> Command </th>	
		<th> Explanation</th>	
	</tr>

	<tr>
		<td>AC</td>
		<td>Motor Acceleration</td>
	</tr>
	
	<tr>
		<td>DC</td>
		<td>Motor Deceleration</td>
	</tr>

	<tr>
		<td>SP</td>
		<td>Motor Speed</td>
	</tr>
	
	<tr>
		<td>SH</td>
		<td>Motor Servo On</td>
	</tr>
	
	<tr>
		<td>MO</td>
		<td>Motor Servo Off</td>
	</tr>
	
	 <tr>
		<td>PA</td>
		<td>Motor Set Position </td>
	</tr>
	
	<tr>
		<td>DP</td>
		<td>Motor Define Reference Position</td>
	</tr>
</table> 

<h4> Vector </h4>
<table>
	<tr>
		<th> Command </th>	
		<th> Explanation</th>	
	</tr>

	<tr>
		<td>VM</td>
		<td>Start, specify which Axis to use</td>
	</tr>
	
	<tr>
		<td>VE</td>
		<td>End of Vector</td>
	</tr>

	<tr>
		<td>VA</td>
		<td>Vector Acceleration</td>
	</tr>

	<tr>
		<td>VD</td>
		<td>Vector Deceleration</td>
	</tr>
	
	<tr>
		<td>VS</td>
		<td>Vector Speed</td>
	</tr>
	
	<tr>
		<td>CR</td>
		<td>Perform curve</td>
	</tr>
	
</table> 

-----
<h3>Galil - Draw graph</h3>
<h4>Pre-requisition </4> 
- Ensure both Axis ( X & Y ) are implement correctly. 
- Ensure all have been reset ( Offset / Count / Graph View )

>[!note]-
>If you are controlling 2 Axis, ensure to put  2nd Axis (Y axis) on Horizontal, the graph will be reading 2 cartesian ( 2D ) image 
>
>Vertical & Horizontal
>![[Pasted image 20260401105903.png]]
>

<h3>Sample Code - Vector</h3>
>[!Success]- Razor Blade 
>```
>#blade
>DP*=0
>VMAB
>VA1000
>VD1000
>VP3000,0
>CR1000,-180,-180 <400000
>VP5000,8000
>CR1000,0,-180 <400000
>VP0,8000
>CR1000,0,-180 <400000
>VP-2000,0
>CR1000,-180,-180 <400000
>VE
>BGS
>AMS
>EN
>```

>[!success]- Middle Finger
>```
>#midFing
>DP*=0
>VMAB
>VA1000
>VD1000
>VP3000,0 ;'up
>VP3000,2000;'left
>VP6000,2000;'up
>VP6000,4000;'left
>VP3000,4000;'down
>VP3000,6000;'left
>VP0,6000;'down
>VP0,0
>VE
>BGS
>AMS
>EN
>```

----

Ethernet IP 

- IA - IP Address 
- IH - Open Internet Handler pg 97
- 
