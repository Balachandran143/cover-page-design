# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new Django project and app.
### Step 2:
Create a static file directory and mention the changes in settings.
### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.
### Step 4:
Write down the code for book cover using HTML and CSS.
### Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(colorful-smoke-back-background_291177-135.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:yellow;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: yellow;
            display: inline;
            position: relative;
            color:lightblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:yellow;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="WhatsApp Image 2023-05-15 at 09.31.39.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>BALACHANDRAN S</b></p>
            </div>
            <div class="publisher">
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:
![Screenshot 2023-05-15 094016](https://github.com/Balachandran143/cover-page-design/assets/118886489/ba1d7f89-dc92-4366-b918-ccbfb6b2eb9c)

## Result:
Thus a website to display the cover page design of a book was successfully created.

