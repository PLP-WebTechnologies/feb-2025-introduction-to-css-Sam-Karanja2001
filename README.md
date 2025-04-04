# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Assignment</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 class="main-heading">Welcome to My Styled Page</h1>
    <p id="intro">This is an example of CSS styling.</p>
    <img src="image.jpg" alt="Example Image" class="styled-image">
    <div class="content-box">
        <p>CSS makes webpages beautiful!</p>
    </div>
</body>
</html>


corresponding style.css file:
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 20px;
    padding: 20px;
}

.main-heading {
    color: #333;
    text-align: center;
}

#intro {
    font-size: 18px;
    color: #555;
    padding: 10px;
}

.styled-image {
    width: 300px;
    border: 3px solid #000;
    margin: 20px auto;
    display: block;
}

.content-box {
    background-color: white;
    padding: 15px;
    border: 2px solid #ddd;
    margin-top: 20px;
    text-align: center;
}
