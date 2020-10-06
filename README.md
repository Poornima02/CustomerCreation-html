# CustomerCreation-html
First Assignment-SUKI
<!DOCTYPE html>
<html>
    <head>
    <meta charset="ISO-8859-1">
        <style>
        h2{
    text-align: center;
}
body{
    background-color: black;
    color: #e9e9e9;
}
form{
    column-count: 4;
}
label{
    width: 140px;
    display: inline-block;
    text-align: right;
}
select{
    width: 170px;
}
.split{
height:50%;
width:100%;
}
.column{
float:left;
text-align:center;
}
.left,.center{
width:25%;
color:black;
}
.right{
width:49%;
}
table, th, td {
  border: 1px solid white;
  border-collapse: collapse;
}
#fixedbutton {
    position: fixed;
    bottom: 0px;
    left: 0px; 
}
#mybutton {
position: fixed;
    bottom: 0px;
    right: 0px;

}
#centerbutton{
position: fixed;
    bottom: 0px;
}
        </style>
    </head>
<body> 
    <div class="top-nav" style = "padding-topdown:4px; background-color: #e9e9e9;color:black">
    <h2>Customer Creation</h2> 
    </div></br>
<div class="split-top">
<form>
<label for="cname"> Customer Name </label>
<input type="text" id="cname" name="cname"></br></br>
<label for="city">City </label>
<input type="text" id="city" name="city"></br></br>
<label for="email"> E-mail </label>
<input type="email" id="email" name="email"></br></br>
<label for="gcode">Group Code </label>
<input type="text" id="gcode" name="gcode"></br></br>
<label for="vatcustomer">VAT Customer </label>
<select id="vatcustomer" name="vatcustomer">
    <option>YES</option>
    <option>NO</option>
</select></br></br>
<label for="status">Status</label>
<select id="status" name="status">
    <option>Active</option>
    <option>Inactive</option>
</select></br></br>
<label for="domain1"> Domain1 </label>
<input type="text" id="domain1" name="domain1"></br></br>
<label for="custnameinv"> Cust Name.Inv </label>
<input type="text" id="custnameinv" name="custnameinv"></br></br>
<label for="country">Country </label>
<input type="text" id="country" name="country"></br></br>
<label for="contactperson">Contact Person </label>
<input type="text" id="contactperson" name="contactperson"></br></br>
<label for="creditlimit">Credit Limit</label>
<input type="number" step="0.01"></br></br>
<label for="vatpercent">VAT Percent</label>
<input type="number" step="0.01" value="0.00"></br></br>
<label for="custcode">Customer Code </label>
<input type="text" id="custcode" name="custcode"></br></br>
<label for="domain2"> Domain2 </label>
<input type="text" id="domain2" name="domain2"></br></br>
<label for="address1"> Address1 </label>
<input type="text" id="address1" name="address1"></br></br>
<label for="Telnum"> Tel.No </label>
<input type="tel" id="Telnum" name="Telnum"></br></br>
<label for="type">Type</label>
<select id="type" name="type">
    <option>Local</option>
    <option>Non-Local</option>
</select></br></br>
<label style="width: 100px;" for="currency" > Currency </label>
<select style="width: 50px;" id="currency" name="currency">
<option>AED</option>
<option>USD</option>
</select>
<label style="width: 100px;" for="fixedCurrency">Fixed Currency</label>
<select style="width: 50px;" id="fixedCurrency" name="fixedCurrency">
    <option>YES</option>
    <option>NO</option>
</select></br></br>
<label for="vatnum"> VAT Number </label>
<input type="text" id="vatnum" name="vatnum"></br></br>
<label for="kindattn"> Kind Attn. </label>
<input type="text" id="kindattn" name="kindattn"></br></br>
<label for="domain3"> Domain3 </label>
<input type="text" id="domain3" name="domain3"></br></br>
<label for="add2"> Address 2 </label>
<input type="text" id="add2" name="add2"></br></br>
<label for="Fax num"> Fax no. </label>
<input type="text" id="Fax num" name="Fax num"></br></br>
<label for="pricelist"> Price List </label>
<input type="text" id="pricelist" name="pricelist"></br></br>
<label for="paymentterms"> Payment Terms(Days) </label>
<input type="number" step="0" value="5"></br></br>
<label for="rebatepercent"> Rebate % </label>
<input type="number" step="0.01" value="0.00"></br></br>
<label for="agenciesdiscount"> Agencies Discount % </label>
<input type="number" step="0.01" value="0.00"></br></br>
</form>
</div>    
<div class="split-down">
<div class="row">
<div class="column left"style = "padding:2px;background-color: black;color:#e9e9e9;border:1px"><h4 style = "padding:2px;background-color: #e9e9e9;color:black">Current open order and value</h1>
	
	<table style="width:100%;border:1px;" >
		<thead>
			<tr>
				<th>#</th>
				<th>SO No.</th>
				<th>ETA Dt.</th>
				<th>Value</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td>1</td>
				<td>SO-A000033</td>
				<td>19/08/2020</td>
				<td>43081.50</td>
			</tr>
			<tr>
				<td>2</td>
				<td>SO-A000039</td>
				<td>05/09/2020</td>
				<td>42430.92</td>
			</tr>
			<tr>
				<td>3</td>
				<td>SO-A000052</td>
				<td>05/09/2020</td>
				<td>40410.40</td>
			</tr>
			<tr>
				<td>4</td>
				<td>SO-A000054</td>
				<td>05/09/2020</td>
				<td>43081.50</td>
			</tr>
		</tbody>
	</table>
	<div id="fixedbutton">
	<button type="button">Back</button>
	<button type="button">Delete</button>
	</div>
	</div>
<div class="column center"style = "padding:2px;background-color: black;color:#e9e9e9"><h4 style = "padding:2px;background-color: #e9e9e9;color:black;">Outstanding Invoice and Value</h1>
<table style="width:100%;border:1px;">
	<thead>
		<tr>
			<th>#</th>
			<th>Inv.No.</th>
			<th>Date</th>
			<th>Amount</th>
			<th>Currency</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>1</td>
			<td>INV-A000002</td>
			<td>16/07/2020</td>
			<td>4100.00</td>
			<td>AED</td>
		</tr>
		<tr>
			<td>2</td>
			<td>INV-A000007</td>
			<td>07/08/2020</td>
			<td>43081.50</td>
			<td>AED</td>
		</tr>
		<tr>
			<td>3</td>
			<td>INV-A000010</td>
			<td>02/09/2020</td>
			<td>42430.92</td>
			<td>AED</td>
		</tr>
	</tbody>
</table>
<div id="centerbutton">
<button type="button">Upload Artifacts</button>
</div>
</div>
<div class="column right"style = "padding:2px;background-color: black;color:#e9e9e9;"><h4 style = "padding:2px;background-color: #e9e9e9;color:black;">Salesman List</h1></div>

<table style="width:49%;border:1px;">
	<thead>
		<tr>
			<th>
        <input type="checkbox">
    		</th>
			<th>Name</th>
			<th>Role</th>
			<th>Operation Div</th>
			<th>From</th>
			<th>To</th>
			<th>Status</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><input type="checkbox"> </td>
			<td>Doodle</td>
			<td>Operation Incharge</td>
			<td>ELECTRICAL</td>
			<td>31/08/2020</td>
			<td></td>
			<td>Active</td>
		</tr>
	</tbody>
</table>
<div id="mybutton">
<button type="button">Clear</button>
	<button type="button">Customer Price List</button>
	<button type="button">Captain/SuperIntendent Mapping</button>
	<button type="button">Save</button>
</div>
</div>
</div>
</body>
</html>
