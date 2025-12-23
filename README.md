# Ex.06 Book Front Cover Page Design

# Date:05/12/25


# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
<head>
    <title>RESIDENT EVIL - BOOK COVER</title>

    <style>

        @import url('https://fonts.googleapis.com/css2?family=Creepster&family=Cinzel+Decorative:wght@700&display=swap');

        body {
            margin: 0;
            padding: 0;
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .book {
            width: 470px;
            height: 620px;
            position: relative;

            background-image:
                linear-gradient(to bottom, rgba(0,0,0,0) 10%, rgba(0,0,0,1)),
                url("zombie1.jpg");

            background-size: cover;
            background-position: center;

            border-radius: 12px;

            box-shadow:
                0 0 30px red,
                inset 0 0 50px black;
        }

        #edition {
            font-family: 'Cinzel Decorative', serif;
            padding-left: 25px;
            padding-top: 35px;
            font-size: 15px;
            letter-spacing: 1px;
            color: rgb(255,220,220);
            text-shadow: 0 0 8px red;
        }

        h1{
            font-family: 'Creepster', cursive;
            font-size: 65px;
            margin-left: 25px;
            margin-top: 15px;
            color: red;
            text-shadow: 0 0 15px red;
        }

        h2{
            font-family: 'Cinzel Decorative', serif;
            margin-left: 25px;
            margin-top: -10px;
            letter-spacing: 2px;
            font-size: 20px;
            color: white;
            text-shadow: 0 0 10px red;
        }

        #tagline {
            font-family: 'Cinzel Decorative', serif;
            font-size: 17px;
            width: 380px;
            margin-left: 25px;
            margin-top: 45px;
            color: white;
            line-height: 22px;
            text-shadow: 0 0 10px black;
        }

        footer {
            position: absolute;
            bottom: 0;
            width: 470px;
            padding: 15px 35px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-top: 2px solid crimson;
            background-color: rgba(0,0,0,0.6);
        }

        .author {
            font-family: 'Cinzel Decorative', serif;
            font-size: 14px;
            text-shadow: 0 0 10px red;
            color: white;
        }

        .myname {
            font-family: 'Creepster', cursive;
            font-size: 19px;
            margin-top: 5px;
            color: red;
            letter-spacing: 1px;
            text-shadow: 0 0 15px red;
        }

        .photo{
            width: 70px;
            height: 70px;
            border-radius: 50%;
            border: 3px solid crimson;
            overflow: hidden;
            box-shadow: 0 0 15px red;
        }

        .photo img{
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

    </style>
</head>

<body>

    <section class="book">

        <p id="edition">ULTIMATE HORROR COLLECTION</p>

        <h1>RESIDENT EVIL</h1>
        <h2>WHEN HUMANITY FALLS</h2>

        <p id="tagline">
            THE DEAD RISE.<br>
            THE LIVING RUN.<br>
            SURVIVAL IS A BLOODY WAR.
        </p>

        <footer>
            <div class="author">
                Published By<br>
                UMBRELLA CORP<br><br>

                <span class="myname">JEVAAPRIYAN M</span> <!-- your name added here -->
            </div>

            <div class="photo">
                <img src="jee.jpeg">
            </div>
        </footer>

    </section>

</body>
</html>

```

# OUTPUT: ![alt text](<Screenshot (131).png>)




# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
