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
    <title>Designing a book</title>
    <style>
      .Help {
    background-image: url("Ghost2.jpg");
    background-repeat: no-repeat;
    background-position: center;
    background-size: auto 100%;
    height: 100vh;
    width: 80%;
    margin-left: 10%; 
    margin-right: 10%; 
    
}
        p{
            color:hsl(177, 100%, 51%);
            text-align: center;
            font-weight: bold;
            padding-top: 15%;
            font-size: 1.5em;
        }
        h2{
            color:hsl(177, 100%, 50%);
            text-align: center;
            font-weight: bold;
            margin-top: 20%; 
        }
        h1{
            color: white;
            text-align: center;
            margin-bottom: 7.5%;
            
        }
        img{
            width: 20%;
            margin-left: 15%;
            border-radius:5%;
            padding-top: 5%;     
        }
    </style>
</head>
<body>
    <div class="Help">
        
            <p>VOTED BSET THRILLER NOVEL 20XX</p>
            <img src="Deepi1.jpg" alt="">
            <h1>DON'T</h1>
            <h1>LOOK</h1>
            <h1>BACK</h1>
            <h2 id="authorName">ISAAC NEWTON</h2>    
    </div>
</body>
</html>
```

## OUTPUT:
![Output](https://github.com/ThangaDeepika/cover/assets/125663099/3714085c-8043-49db-9221-cb6493b066c8)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
