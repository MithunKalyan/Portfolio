# Ex01 Portfolio
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header, footer {
      background: #e28b11;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      cursor: pointer;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 20px;
      max-width: 700px;
      margin: 20px auto;
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      display: none;
    }
    section.active {
      display: block;
    }
    h2 {
      color: #c0db22;
    }
    .project {
      background: #eef;
      padding: 10px;
      margin-top: 10px;
      border-left: 4px solid #c4b61c;
    }
    footer {
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mithun Kalyan</h1>
    <nav>
      <a onclick="showSection('about')">About</a>
      <a onclick="showSection('projects')">Projects</a>
      <a onclick="showSection('contact')">Contact</a>
    </nav>
  </header>

  <section id="about" class="active">
    <h2>About Me</h2>
    <p>Hi! I'm Mithun, a web developer who loves creating simple websites. I focus on user-friendly and functional designs.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <strong>Portfolio Website:</strong> A personal site built using HTML and CSS.
    </div>
    <div class="project">
      <strong>To-Do App:</strong> A minimal app for managing daily tasks.
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: mithunkalyan@gmail.com</p>
    <p>GitHub: <a href="https://github.com/MithunKalyan" target="_blank">github.com/MithunKalyan</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Mithun</p>
  </footer>

  <script>
    function showSection(id) {
      const sections = document.querySelectorAll('section');
      sections.forEach(sec => sec.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
```
## OUTPUT

<img width="1271" height="510" alt="Screenshot 2025-08-13 173837" src="https://github.com/user-attachments/assets/80a4be26-d03c-4130-87cc-455848cbbcb0" />

<img width="1256" height="556" alt="Screenshot 2025-08-13 174519" src="https://github.com/user-attachments/assets/2db7cbfe-7bde-489e-a2e1-01d5213bc9f5" />

<img width="1223" height="528" alt="Screenshot 2025-08-13 174711" src="https://github.com/user-attachments/assets/653355d4-5718-4859-99ad-99139b6e366f" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
