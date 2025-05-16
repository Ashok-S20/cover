# Ex.06 Book Front Cover Page Design
## Name: ASHOK S
## Date: 16.05.2025

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
  <title>Hitler and the Nazis: Evil on Trial - Book Template</title>
  <style>
    body {
      background: hsl(0, 89%, 65%);
      font-family: 'Georgia', serif;
      margin: 0;
      padding: 0;
    }
    .book {
      width: 12cm;          /* typical book width */
      height: 18cm;         /* fixed height */
      margin: 50px auto;
      padding: 20px;
      background: #ffffff;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      border: 2px solid #dcdcdc;
      overflow: hidden;     /* ensure content fits */
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .cover {
      text-align: center;
    }
    .cover img {
      width: 11cm;
      margin-bottom: 15px;
      box-shadow: 0 5px 15px rgba(109, 191, 246, 0.3);
    }
    .title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 5px;
    }
    .author {
      font-size: 18px;
      color: #555;
      margin-bottom: 15px;
    }
    .description {
      font-size: 14px;
      line-height: 1.4;
      color: #333;
      text-align: justify;
    }
  </style>
</head>
<body>

<div class="book">
  <div class="cover">
    <img src="HITLER.jpg" alt="Hitler and the Nazis: Evil on Trial">
    <div class="title">Hitler and the Nazis: Evil on Trial</div>
    <div class="author">By Joe Berlinger</div>
  </div>
  <div class="description">
    Adolf Hitler was the leader of the National Socialist German Workers' Party (Nazi Party) and dictator of Nazi Germany from 1933 to 1945. Under his rule, the Nazis promoted extreme nationalism, racism, and anti-Semitism. They aimed to establish a totalitarian regime and expand German territory. Hitler's aggressive policies led to World War II and the Holocaust, during which millions of Jews and other minorities were systematically murdered. His regime ended with Germany's defeat in 1945.
  </div>
</div>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (28).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
