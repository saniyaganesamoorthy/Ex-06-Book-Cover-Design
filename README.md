# Ex-06-Book-Cover-Design
# AIM:
Design the following book cover page using HTML and CSS

# DESIGN STEPS:
Step 1: Initialize HTML Structure:

Step 2: Define Styles:

Step 3: Create Book Cover Page Container:

Step 4: Populate Book Cover Page and adjust Formatting:

# CODE:
``````
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: rgb(255, 0, 0);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('images1.jpg');
            background-size: cover;
        }

        .insight{
            color: rgb(42, 165, 138);

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(255, 255, 255);
            display: inline;
            position: relative;
            color: rgb(67, 2, 102);
            top: 190px;

            font-family: Georgia, 'Comic Sans MS', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: left;
            position: relative;
            top: 30px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color: rgb(218, 135, 17);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }
        .mypic{
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
            <div class="insight">
                BEST SELLER
            </div>
            <div class="hrstyle">
                <hr style="color:red;">
            </div>
            <div class="booktitle">
                <h1>The Alchemist</h1>
            </div>
            <div class="subtitle">
                   "psychological thriller novel"
            </div>
            <div class="mypic">
                <img src="image2.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(0, 17, 255);">
            </div>
            <div class="author">
                <p><b>Paulo Coelho</b></p>
            </div>
            <div class="pub">
                THRILLER
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>
``````
# OUTPUT:
![Alt text](../COVER.png)