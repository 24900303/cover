# Ex.06 Book Front Cover Page Design
## Date:

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
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>book-front-cover</title>
    <style>
        body{
            top:0;
        }
        .pic {
            background-color: rgb(255, 0, 0);
            color: white;
            height: 100vh;
            width: 20cm;
        }

        .layout {
            margin: 0% 25% 0% 25%;
        }

        p {
            margin-bottom: 0;
            padding-bottom: 0;
        }

        h4,
        h3 {

            margin: 0;

        }
    </style>
</head>

<body>
    <div class="layout">
        <div class="pic">
            <div style="margin:2%;">
                <p style="margin-top: 2%;padding:2% 0% 0% 0%;color:rgb(0, 0, 0);font-size: 25px;"><i>READER INSIGHT</i></p>
                <div style="width:25%;">
                    <hr style="padding:0% 2% 0% 0%">
                </div>
                <h1 style="text-align: center;margin-top:5%;font-size:45px;color:rgb(0, 0, 0)"><i>Brewed Culture: A Sip Through
                        History<i> 
                        </h1>
                <p style="text-align: center">Step into the rich tapestry of coffee's journey through time and culture
                    in "Brewed Culture."</p>
                    <center><img src="OIP.jpeg" width="250px" height="200px" style="margin-top:7%;"></center><br><br><br>
                   
                <div style="display: flex;justify-content: space-between;font-size:25px;color:wheat;">
                    <h3 style="margin-top:15%;">FIRST EDITION</h3>
                    <img src="WhatsApp Image 2024-11-07 at 11.01.57_5dc34fdd.png" width="100px" height="100px" style="margin-top:7%;">
                </div>
                <hr>
                <div style="display: flex;justify-content: space-between;font-size:25px;color:rgb(245, 179, 209)">
                    <h4>RUDESH KANNA R</h4>
                    <h4>SAVEETHA ENGINEERING COLLEGE</h4>
                </div>
            </div>
        </div>
    </div>
</body>

</html>

```
## OUTPUT:

![Screenshot 2024-11-07 114141](https://github.com/user-attachments/assets/241fd812-a58e-4229-bf3c-ed20f84f7f38)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
