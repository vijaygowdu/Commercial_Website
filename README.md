# Ex02 Commercial Website
## Date:17-03-25

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Sports Hub</h1>
        </header>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">News</a>
            <a href="#">Teams</a>
            <a href="#">Matches</a>
            <a href="#">Contact</a>
        </nav>
        <div class="main-content">
            <section class="content">
                <h2>Latest Sports News</h2>
                <p>Stay updated with the latest sports events and scores.</p>
            </section>
            <aside class="sidebar">
                <h2>Upcoming Matches</h2>
                <ul>
                    <li>Team A vs Team B - 5 PM</li>
                    <li>Team C vs Team D - 7 PM</li>
                    <li>Team E vs Team F - 9 PM</li>
                </ul>
            </aside>
        </div>
        <footer class="footer">
            <p>&copy; 2025 Sports Hub. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
```
## style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f8f8f8;
    color: #333;
}

.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    background: #0275d8;
    color: blue;
    text-align: center;
    padding: 1.5rem;
    font-size: 1.5rem;
}

.nav {
    display: flex;
    justify-content: space-around;
    background: #034694;
    padding: 1rem;
}

.nav a {
    color: violet;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

.nav a:hover {
    text-decoration: underline;
    color: #ffcc00;
}

.main-content {
    display: flex;
    flex: 1;
    padding: 2rem;
    gap: 1rem;
}

.sidebar {
    flex: 1;
    background: #f4f4f4;
    padding: 1rem;
    border-left: 4px solid #0275d8;
}

.content {
    flex: 2;
    background: #ddd;
    padding: 1.5rem;
    border-radius: 5px;
}

.footer {
    background: #034694;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: auto;
}

@media (max-width: 768px) {
    .main-content {
        flex-direction: column;
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/116a5f5d-6df5-492d-aace-74fcfda5e277)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
