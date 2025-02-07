# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
 
Clone the git hub repository and create a django admin interface.

### Step 2:

Write HTML and CSS code for disigning book cover page and execute them.

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
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Times New Roman', Times, serif;
            background-image: url(/static/images/book1.png);
            background-size: cover;
        }
            

        .insight{
            color:lightskyblue;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:lightgoldenrodyellow;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color: white;
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
            color: lime;
        }
        .ed{
            color: lightblue;
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
            color: lightgreen;
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
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: greenyellow;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="/static/images/George.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: greenyellow;">
            </div>
            <div class="author">
               <p><b>Steve Jobs</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:

![book_cover_page](./img/page.png)

## Result:

The project for designing book cover page using HTML and CSS is executed successfully.