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


INDEX.HTML

       <!DOCTYPE html>
       <html lang="en">
       <head>
           <meta charset="UTF-8">
           <meta name="viewport" content="width=device-width, initial-scale=1.0">
           <title>Styled Webpage</title>
           <link rel="stylesheet" href="style.css">
       </head>
       <body>
       
           <header>
               <h1 class="header-title">AI-Driven Appointment System</h1>
           </header>
       
           <section class="content">
               <p class="description">This system optimizes scheduling for healthcare appointments using artificial intelligence.</p>
               <img id="feature-image" src="appointment.jpg" alt="AI Appointment System">
           </section>
       
           <footer>
               <p>Developed by <span class="highlight">michael wambua</span></p>
           </footer>
       
       </body>
       </html>

STYLE.CSS

    body {
        font-family: 'Verdana', sans-serif;
        background-color: #f8f9fa;
        margin: 20px;
        padding: 20px;
    }
    
    
    .header-title {
        color: #007bff;
        text-align: center;
        font-size: 30px;
        margin-bottom: 20px;
    }
    
    
    .description {
        font-size: 18px;
        color: #333;
        padding: 10px;
        border-left: 5px solid #007bff;
        margin-bottom: 20px;
    }
    
    
    #feature-image {
        display: block;
        max-width: 100%;
        height: auto;
        margin: 20px auto;
        border: 4px solid #007bff;
        border-radius: 10px;
    }
    
    
    .highlight {
        color: #dc3545;
        font-weight: bold;
    }
