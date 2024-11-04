# Ex.06 Book Front Cover Page Design
## Date: 04.11.2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html>

<head>
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(0, 7, 9);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url('https://img.freepik.com/free-vector/network-mesh-wire-digital-technology-background_1017-27428.jpg?size=626&ext=jpg&ga=GA1.1.1827530304.1715472000&semt=ais_user') ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(0, 5, 10);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(28, 25, 2);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(28, 8, 3);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(0, 10, 3);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(8, 123, 31);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(243, 243, 6);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>COMPUTER NETWORKS</b>
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(218, 246, 9)">
            </div>
            <div class="booktitle">
                <h1><b>COMPUTER NETWORKS</b></h1></div>
            <div class="subtitle">
                 <b>Introduction of Computer Networks </b> 
            <div class="subtitle2">
                <b>>> Everyone should build their network before they need it.</b><br>
                <b>>> The Internet is not just one thing, it's a collection of things</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="C:\Users\admin\Desktop\web dev\23014049.jpg" width="100" height="90" >
            </div>
            <div class="id">
                <hr style="color:rgb(1, 0, 8)">
            </div>
            <div class="author">
               <p><b>SURIYA RAJ K(212223040216)</b></p>
            </div>
            <div class="pub">
                SEC 27'
            </div>
        </div>
    </div>
</body>
</html>
    </html>    

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6178df9c-b42f-47cb-b8f2-3d256fd30ed8)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
