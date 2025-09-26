# Ex.06 Book Front Cover Page Design
## Date:26.09.2025

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
  <html>
<head>
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BOOK COVER PAGE</title>
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            margin: 20px auto;
            background-image: url("C:/Users/acer/Downloads/360_F_529873767_FMwTX8twWRwAI4xtk2X65THeflD7Fp9s.jpg"); /* background cover */
            background-size: cover;
            background-position: center;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position: relative;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
            color: palevioletred;
        }

        .insight {
            font-size: 18px;
            font-weight: bold;
        }

        .hrstyle hr {
            width: 100px;
            
        }

        .booktitle h1 {
            font-family: 'Courier New', Courier, monospace;
            font-size: 28px;
            text-align: center;
            margin-top: 30px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: 20px;
            text-align: center;
            margin-top: 10px;
        }

        .mypic {
            position: absolute;
            bottom: 100px;
            right: 20px;
        }

        .mypic img {
            width: 100px;
            height: 120px;
            border-radius: 8px;
            object-fit: cover;
        }

        .author {
            position: absolute;
            bottom: 60px;
            left: 20px;
            font-family: Georgia;
            font-size: medium;
            color: navajowhite;
        }

        .pub {
            position: absolute;
            bottom: 40px;
            right: 20px;
            font-size: medium;
            font-weight: bold;
        }

        .ed {
            position: absolute;
            bottom: 20px;
            left: 20px;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }
    </style>
</head>
<body>
    <div class="bookpage">
        <div class="insight">EXPERT INSIGHT</div>
        <div class="hrstyle">
            
        </div>
        <div class="booktitle">
            <h1>THE NEBULA</h1>
        </div>
        <div class="subtitle">NEBULA DREAMS</div>
        <div class="mypic">
            <img src="C:\Users\acer\Downloads\FGGHJ.jpg" alt="">
        </div>
        <div class="author"><b>DARSHINI</b></div>
        <div class="pub">TO GAZE AT NEBULA IS TO GLIMPSE THE UNIVERSE</div>
        <div class="ed"><b>Edition</b></div>
    </div>
</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot 2025-09-26 100816-1.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
