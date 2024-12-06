# Bsection7
this is sample team project
team 1 Maritemappa Readme 1 file 
team 2 srirama Readme 2 file 
team 3 manju kadam Readme 3 file 

**Index.html**tm 3
<!DOCTYPE html>
<html>
<head>
  <title>Team Portfolio</title>
  <link rel="stylesheet" href="style.css"
</head>
<body>
  <header>
    <h1>Welcome to Our Team Portfolio</h1>
  </header>
  <section id="team">
    <h2>Meet the Team</h2>
    <div class="profile">
      <h3>Alice</h3>
      <p>Frontend Developer</p>
    </div>
    <div class="profile">
      <h3>Bob</h3>
      <p>UI/UX Designer</p>
    </div>
    <div class="profile">
      <h3>Charlie</h3>
      <p>JavaScript Developer</p>
    </div>
  </section>
  <footer>Contact us at: team@example.com</footer>
  <script src="script.js"> </script>
</body>
</html>

**Script.js** team number 1
document.querySelectorAll('.profile').forEach(profile => {
    profile.addEventListener('mouseenter', () => {
      profile.style.backgroundColor = '#f0f0f0';
    });
    profile.addEventListener('mouseleave', () => {
      profile.style.backgroundColor = 'white';
    });
  });

**Style.css** tm 2
body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
header { background-color: #4CAF50; color: white; padding: 20px; text-align: center; }
.profile { margin: 20px; padding: 10px; border: 1px solid #ddd; }
footer { text-align: center; padding: 10px; background: #f1f1f1; }
