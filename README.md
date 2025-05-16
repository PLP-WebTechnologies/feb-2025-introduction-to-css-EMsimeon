#[ Introduction to CSS

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
 - /project-folder
  ├── index.html
  └── style.css
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-title">Welcome to My Styled Page</h1>
  
  <p class="intro-text">This paragraph introduces the styling features applied using external CSS.</p>
  
  <img src="https://via.placeholder.com/150" alt="Sample Image" class="styled-image">

  <div class="content-box">
    <p>This is a content box with margins, paddings, and borders applied.</p>
  </div>

</body>
</html>

/* ID Selector */
#main-title {
  color: #2a9d8f;
  font-family: 'Georgia', serif;
  text-align: center;
  margin-top: 20px;
}

/* Class Selector */
.intro-text {
  font-size: 18px;
  font-family: 'Arial', sans-serif;
  color: #264653;
  margin: 10px 20px;
}

/* Element Selector */
body {
  background-color: #f0f0f0;
  line-height: 1.6;
  padding: 20px;
}

/* Image Styling */
.styled-image {
  display: block;
  margin: 20px auto;
  border: 5px solid #e76f51;
  border-radius: 10px;
}

/* Content Box with Margin, Padding & Border */
.content-box {
  background-color: #ffffff;
  border: 2px solid #ccc;
  padding: 15px;
  margin: 30px auto;
  width: 80%;
  font-family: 'Verdana', sans-serif;
}

Happy Coding! 💻✨
](https://github.com/PLP-WebTechnologies/feb-2025-advanced-html-EMsimeon/blob/d60dba11d935de36b29242fe1c5859562eff5b1a/README.md)****
