# Ex.06 Book Front Cover Page Design
## Date: 25-10-2025

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

## bookcover.html:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Psychology of Money</title>
    <link rel="stylesheet" href="cover.css">
</head>

<body>
    <div class="container">
        <header>
            <section class="title">
                <p class="f1">The</p>
                <p class="f2">Psychology</p>
                <p class="f1">of</p>
                <p class="f2 highlight">Money</p>
            </section>
        </header>

        <section class="image-section">
            <img src="images/brain.png" alt="Book Cover" width="600" height="400">
            <p class="subtitle">TIMELESS LESSONS ON WEALTH, GREED, AND HAPPINESS</p>
        </section>

        <footer class="footer">
            <p class="f4">MORGAN HOUSEL</p>
            <p class="f3">"Everyone should own a copy."</p>
            <p class="f4">--JAMES CLEAR</p>
            <p class="f3">New York Times bestselling author of Atomic Habits</p>
        </footer>
    </div>
</body>

</html>
```

## cover.css:

```css
.container {
    border: 4px solid #000;
    padding: 20px;
    width: 600px;
    margin: 40px auto;
    text-align: center;

}

.f1 {
    font-family: 'big-caslon', serif;
    font-weight: 900;
    font-size: 25px;
    font-style: italic;
    height: 0px;
}

.f2 {
    font-family: 'big-caslon', serif;
    font-weight: 900;
    font-size: 40px;
    color: #333;
    height: 8px;
}

.highlight {
    color: rgb(43, 110, 110);
}

.subtitle {
    font-family: 'big-caslon', serif;
    font-weight: 900;
    font-size: 20px;
    color: rgb(43, 110, 110);
}

.f3 {
    font-family: 'big-caslon', serif;
    font-weight: 400;
    font-size: 20px;
    font-style: italic;
    color: #333;
}

.f4 {
    font-family: 'big-caslon', serif;
    font-weight: 900;
    font-size: 20px;
    color: #333;
}
```

## OUTPUT:

<img width="1919" height="1158" alt="Book-Cover" src="https://github.com/user-attachments/assets/bf177761-3142-4e43-91d6-27c37d654cc2" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
