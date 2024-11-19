# Ex03 Time Table
## Date:19/11/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
html>
      <body>
          <img src="logo.png" width="65%">
            <table border= "1" cellspacing="5" cellpadding="10">
                <caption> Time table </caption>
                  <tr>
                      <th color="red"> Days </th>
                      <th> 8:00 am to 10:00 am </th>
                      <th> 10:00 am to 12:00 pm </th>
                      <th> 12:00 pm to 1:00 pm </th>
                      <th> 1:00 pm to 3:00 pm </th>
                  </tr>
                  <tr>
                      <td> Monday </td> 
                      <td> free </td>
                      <td> BEEE </td>
                      <td rowspan="6"> Break </td>
                      <td> Free </td>
                  </tr>
                  <tr>
                      <td> Tuesday </td> 
                      <td> Web </td>
                      <td> BEEE </td>
                     
                      <td> Statistics </td>
                  </tr>
                  <tr>
                      <td> Wednesday </td> 
                      <td> Statistics </td>
                      <td> English </td>
                     
                      <td> Mentor meet </td>
                  </tr>
                  <tr>
                      <td> Thursday </td> 
                      <td> Machine learning </td>
                      <td> Free </td>
                      
                      <td> Physics </td>
                  </tr>
                 <tr>
                      <td> Friday </td> 
                      <td> Machine learning </td>
                      <td>  Physics</td>
                      
                      <td> Web </td>
                  </tr>
                  <tr>
                      <td> Saturday </td> 
                      <td> English </td>
                      <td> Free </td>
                      	
                      <td> Web </td>
                  </tr>
                  <tr>
                      <td> Sunday </td> 
                      <td colspan=""5"> Holiday </td>
                      
                  </tr>
       </table>           
        <table border = "2" cellspacing=""3" cellpadding="8"
        <tr>         
            <th> S.no </th>
            <th> Course </th>
            <th> Code </th>      
        </tr>
        <tr>         
            <td> 1 </td>
            <td>  BEEE</td>
            <td>  19EE305 </td>      
        </tr>
        <tr>         
            <td> 2 </td>
            <td>  Web</td>
            <td> 19A1414 </td>      
        </tr>
        <tr>         
            <td> 3 </td>
            <td>  English</td>
            <td> 19EN101 </td>      
        </tr>
        <tr>         
            <td> 4 </td>
            <td>  Statistics</td>
            <td> 19MA211 </td>      
        </tr>
        <tr>         
            <td> 5 </td>
            <td>  Physics</td>
            <td> SH3214 </td>      
        </tr>
        <tr>         
            <td> 6 </td>
            <td>  ML</td>
            <td> 19AI410 </td>      
        </tr>
        <tr>         
            <td> 7 </td>
            <td>  Mentor</td>
            <td> ECA-M Scoft  </td>      
        </tr>
    </table>
     </body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-11-19 210726.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
