

## UC – 2 Saving ## 

 

 **Extracting Responsibilities**

<table>
	<tr>
		<th> Responsibilities Description </th>
		<th> Type  


		new files are dded here 
			<br />

			cleared 
			<br />

			just for test 

</th>
		<th>Concept name </th>
</tr>
<tr>
<td>Page make should have made the page for save

this is new 
</td>
<td>K 
<br />
all done now sir 
</td>
<td>Page maker</td>
</tr>
<tr> 
	<td>The result should be get it from the different (UCS)</td>
	<td> D </td> 
	<td>Getter</td>
</tr>
<tr> 
<td> The parameter should be added to database</td>
<td> D </td>
<td> saver </td>
</tr>
<tr>
	<td>The page shows the content of the page</td>
	<td> K </td>
	<td> interface page </td>
</tr>
<tr>
		<td> The page that shows the content to be saved </td>
		<td> K </td>
		<td> Interface Page </td>
		</tr>
<tr> 
		<td> The interface page that get parameters or edits </td>
		<td> K </td>
		<td> Interface Page </td>
</tr>
<tr> 		
		<td> The saver will right to database. </td>
		<td> D </td>
		<td> Write to Data Base </td>
</tr>
<tr> 		
		<td> The holder for the contents  </td>
		<td> K <td> 
		<td> Holder </td> 
</tr>
<tr> 
		<td> Controller where to write the contents </td>
		<td> D </td>
		<td> Controller </td>
</tr>
	</table>

	<center>
	####Extracting Association####  
</center>
<table>	
<tr> 
		<th> concept pari </th>
		<th> description </th>
		<th> association name </th>
</tr>
<tr> 	
		<td> Controller ßà interface page</td>
		<td> Interface page will get the input </td>
		<td> Preparing</td>
</tr>
<tr> 
		<td> Interface page ßà getter </td>
		<td> The getter gets the contents. <br />
		this part is new every body just for test <br />
		what about this one .

</td>
		<td> Getter for data </td>
</tr>
<tr> 		
		<td> Getter ßà saver </td>
		<td> Saver will prepare the content for writing to database </td>
		<td> Prepare </td>
</tr>
<tr>
		<td> Saver <----> writer </td>
		<td> The saver will give it to the writer for righting </td>
		<td> Write </td>
</tr>
<tr> 	
		<td> Writerßà dbs</td>
		<td> Writer will write to database </td>
		<td> writer </td> 
</tr>
</table>
			<center>  
####Extracting the attributes#### </center>
<table>
<tr> 	
		<th> concept </th>
		<th> attribute </th>
		<th> description </th>
</tr>
<tr> 
		<td> Checking</td>
		<td> Checker <.td>
		<td> Checks where it should write.</td>
</tr>
<tr> 
		<td> Searching</td>
		<td> Searcher </td>
		<td> Search to write to database. </td>
</tr>
<tr> 
		<td> writing </td>
		<td> writer </td>
		<td> Writer should write to database. </td>
</tr>
		<img src="Domain Model pics/save.jpg" />
</table>
	<center>  		####USE CASE 3: Deleting#### 	
Extract responsibilities 	</center>
<table>
<tr> 
		<th> Description </th>
		<th> type </th>
		<th> concept name </th>
</tr>
<tr> 
		<td> checker for the files to be deleted </td>
		<td> D </td>
		<td> Checker</td>
</tr>
<tr>
		<td> the content of the page must be made. Or updated.</td>
		<td> D </td>
		<td> Updater </td>
</tr>
<tr> 
		<td> Shows a confirmation page for delete </td>
		<td> K </td>
		<td> Int page</td>
</tr>
<tr> 
		<td> Find the object and delete </td>
		<td> D </td>
		<td> deleter </td>
</tr>
</table>
		<center>  #### Extract Association #### </center>
<table>
<tr>
		<th> Concept pair </th>
		<th> description </th>
		<th> Association name </th>
</tr>
<tr> 
		<td> Interface Page ßà delete</td>
		<td> Shows the contents to be deleted </td>
		<td> Request </td>
</tr>
<tr>
		<td>Delete ßà dbs connector</td>
		<td> Gets the content to be deleted. </td>
		<td> Request for delete </td>
</tr>
<tr> 
		<td> Dbs ßà data holder </td>
		<td> Holds data get it form dbs connector</td>
		<td> Get the request </td>
</tr>
</table>

		<center>  #### Extracting the Attributes #### </center>
<table>
	<tr>
			<th> Concept <th>
			<th> Attribute </th>
			<th> Description </th>
</tr>
<tr> 
			<td> Search </td>
			<td> Searcher </td>
			<td> Search for records to be deleted. </td>
</tr>
<tr>
			<td> Delete </td>
			<td> delete </td>
			<td> Takes the parameter to delete and send request to delete. </td>
</tr>

</table>
		<img src="Domain Model Pics/Delete.jpg">

		<center> #### UC 4: PRINTING #### 
</center>
<table>
		<tr> 
			<th> responsibilities</th>
			<th> type </th>
			<th> concept name </th>
</tr>
<tr> 
			<td> Content must be known to print </td>
			<td> K </td>
			<td> interface Page </td>
</tr>
<tr>
			<td> Container to hold the data for print.</td>
			<td> K</td>
			<td> Data holder</td>
</tr>
<tr>
			<td> Make decision to print what</td>
			<td> D</td>
			<td> Decision maker</td>
</tr>
<tr> 
			<td> Send request for print </td>
			<td> D </td>
			<td> Requester </td>
</tr>
</table>

	<center> 
			#### Extracting Association ####
</center>

<tr> 
		<th> concept pair </th>
		<th> description </th>
		<th> association name </th>
</tr>
<tr> 
		<td> Interface page ßà data holder</td>
		<td> gets the data from data holder</td>
		<td> Sends request</td>
</tr>
<tr> 
		<td> Data holder ßà decision maker </td>
		<td> help to print  </td>
		<td> Provide control</td>
</tr>
<tr>
		<td> Decision maker ßà printer </td>
		<td> send request to print the data. </td>
		<td> Request to print</td> 
</tr> 
</table>

		<center>
				#### Extracting Attributes####
</center>

<table>
	<tr> 
			<td> concept</td>
			<td> attribute </td>
			<td> description </td>
</tr>
		<tr> 
			<td> Search </td>
			<td> Data</td>
			<td> Search data for print.</td>
</tr>
<tr> 
			<td> Notify </td>
			<td> Notifying </td>
			<td> Notify that has been printed. </td>
</tr> 
</table>
<img src="Domain Model pics/Print.jpg" /> 

<center>
				#### UC – 5 : Editing####

Extracting responsibilities
</center>
<table>
	<tr>
			<th> responsibilities </th>
			<th> type </th>
			<th> concept name </th>
</tr>
<tr>
			<td> Container for data </td>
			<td> K </td>
			<td> Data holder</td>
</tr>
<tr> 
			<td> Page maker to show the content interface page</td>
			<td> K</td>
			<td> Page maker</td>
</tr>
<tr>
			<td> Connector to database.</td>
			<td> D</td>
			<td> Connector</td>
</tr>
<tr>			
			<td> Editor change the disable to editable. </td>
			<td> D </td>
			<td> Editor </td>
</tr> 
<tr> 
			<td> Edits the page in database </td>
			<td> D </td>
			<td> Editor </td>
</tr>
<tr>
			<td> Checks if the data has been changed </td>
			<td> D </td>
			<td> checker </td>
</tr>
</table> 

		<center> 
				#### Extracting Association ####
</center>
<table>
	<tr> 
			<th> Concept pair </th>
			<th> Description </th>
			<th> Association name </th>
</tr>
<tr> 
			<td> Page maker ßà editor </td>
			<td> Gets data from page maker </td>
			<td> Request </td>
</tr>
<tr>
			<td> Editor ßà data checker</td>
			<td> Send request to take the data to check. <td>
			<td> Checker </td>
</tr>
<tr> 
			<td> Checker ßà data checker </td>
			<td> Checks if the data is being modified </td>
			<td> Send request </td>
</tr>
<tr> 
			<td> Editor ßà database </td>
			<td> Writes directly to database modified contents </td>
			<td> Modifier </td>
</tr>
</table>
	<center>
			#### Extracting Attributes ####

<table>
	<tr>
			<th> concept </th>
			<th> attribute </th>
			<th> description </th>
</tr>
<tr>
			<td> search </td>
			<td> data </td>
			<td> Search for data to get it.</td>
</tr>
<tr>			<td></td>
			<td> </td>
			<td> Make it modifiable or not. </td>
</tr>
</table>

<img src="Domain Model pics/Edit.jpg" /> 



