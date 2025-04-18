# Expense-Tracker
# FRONT END   
   
    
About.html   
   
   
<!DOCTYPE html>   
<html lang="en">   
<head>   
    <meta charset="UTF-8">   
    <meta name="viewport" content="width=device-width, initial-scale=1.0">   
    <title>About - Spam Email Detector</title>   
    <link rel="stylesheet" href="{{ url_for('static', filename='css/styles.css') }}">   
    <link  rel="stylesheet" 
 href="https://cdnjs.cloudflare.com/ajax/libs/fontawesome/6.0.0beta3/css/all.min.css">   
</head>   
<body>   
    <header>   
        <nav class="navbar">   
            <div class="logo">   
                <i class="fas fa-shield-alt"></i>   
                <span>Spam Detector</span>   
            </div>   
            <div class="nav-links">   
                <a href="/">Home</a>   
                <a href="/about" class="active">About</a>   
            </div>   
        </nav>   
    </header>   
   
    <main>   
        <section class="about-hero">   
            <div class="about-hero-content">   
                <h1>About Spam Detector</h1>   
                <p>Leveraging the power of machine learning to combat spam emails</p>   
            </div>   
        </section>   
   
        <section class="about-content">   
            <div class="card">   
            <h2>How It Works</h2>   
      
   
            <div class="about-item">   
                <div class="about-icon">   
                    <i class="fas fa-robot"></i>   
                </div>   
                <div class="about-details">   
                    <h3>TensorFlow Model</h3>   
                   <p>Our spam detection system is built using TensorFlow, a state-of-the-art machine learning 
framework. The model is trained on thousands of spam and legitimate (ham) emails to accurately classify 
new email content.</p>   
                    </div>   
                </div>   
                   
                <div class="about-item">   
                    <div class="about-icon">   
                        <i class="fas fa-cog"></i>   
                    </div>   
                    <div class="about-details">   
                        <h3>Text Processing</h3>   
                        <p>We use natural language processing techniques to analyze email content. The system 
preprocesses text by removing stopwords, stemming, and tokenizing the content to identify key patterns 
indicative of spam.</p>   
                    </div>   
                </div>   
                   
                <div class="about-item">   
                    <div class="about-icon">   
                        <i class="fas fa-brain"></i>   
                    </div>   
                    <div class="about-details">   
                        <h3>Bidirectional LSTM Neural Network</h3>   
                        <p>Our model utilizes a Bidirectional Long Short-Term Memory (LSTM) neural network 
architecture, which processes text in both directions to better understand context and sequence relationships 
in email content, leading to significantly improved spam detection accuracy.</p>   
                    </div>   
                </div>   
            </div>   
   
            <div class="card">   
                <h2>Technical Details</h2>   
                <div class="tech-details">   
                    <div class="tech-item">   
                        <div  class="tech-icon"><i  class="fab  fa-python"></i></div>                         
<div>Python</div>   
                    </div>   
                    <div class="tech-item">   
                        <div  class="tech-icon"><i  class="fab  fa-tensorflow"></i></div>                 
<div>TensorFlow</div>   
                    </div>   
                    <div class="tech-item">   
      
   
                        <div  class="tech-icon"><i  class="fas  fa-flask"></i></div>                         
<div>Flask</div>   
                    </div>   
                    <div class="tech-item">   
                        <div class="tech-icon"><i class="fab fa-js"></i></div>   
                    <div>JavaScript</div>   
                </div>   
                <div class="tech-item">   
                    <div class="tech-icon"><i class="fab fa-html5"></i></div>   
                    <div>HTML5</div>   
                </div>   
                <div class="tech-item">   
                   <div class="tech-icon"><i class="fab fa-css3-alt"></i></div>   
                    <div>CSS3</div>   
                </div>   
            </div>   
               
            <div class="model-details">   
                <h3>Model Accuracy</h3>   
                <p>Our spam detection model achieves an accuracy of 98.65% on test data, with 95.89% 
precision and 93.96% recall, making it a highly reliable tool for identifying unwanted emails.</p>   
                       
                    <h3>Privacy</h3>   
                    <p>Your email content is processed locally and is not stored or transmitted to external servers. 
We take your privacy seriously.</p>   
                </div>   
            </div>   
        </section>   
    </main>   
   
    <footer>   
        <div class="footer-content">   
            <p>&copy; 2025 Spam Email Detector | All Rights Reserved</p>         </div>   
    </footer>   
   
    <script src="{{ url_for('static', filename='js/script.js') }}"></script>   
</body>   
</html>   
   
   
   
Index.html   
   
   
<!DOCTYPE html>   
<html lang="en">   
<head>   
    <meta charset="UTF-8">   
      
   
    <meta  name="viewport"  content="width=device-width,  initial-scale=1.0">     
<title>Spam Email Detector</title>   
    <link rel="stylesheet" href="{{ url_for('static', filename='css/styles.css') }}">   
    <link  rel="stylesheet" 
 href="https://cdnjs.cloudflare.com/ajax/libs/fontawesome/6.0.0beta3/css/all.min.css">   
</head>   
<body>   
    <header>   
        <nav class="navbar">   
            <div class="logo">   
                <i class="fas fa-shield-alt"></i>   
            <span>Spam Detector</span>   
        </div>   
        <div class="nav-links">   
            <a href="/" class="active">Home</a>   
            <a href="/about">About</a>   
        </div>   
    </nav>   
</header>  
<main>   
    <section class="hero">   
        <div class="hero-content">   
            <h1>Spam Email Detector</h1>   
            <p>Check if an email is spam or not spam</p>         </div>   
        </section>   
   
        <section class="detection-container">   
            <div class="card">   
                <h2>Check Email</h2>   
                <div class="input-group">   
                    <textarea id="email-input" placeholder="Paste your email content here..."></textarea>   
                    <button id="check-button" class="primary-button">   
                        <i class="fas fa-search"></i> Check   
                    </button>   
                </div>   
                   
                <div id="result-container" class="result-hidden">   
                    <div class="result-content">   
                        <div class="result-icon">   
                            <i id="result-icon-element" class="fas"></i>   
                        </div>   
                        <div class="result-details">   
                            <div  id="result-text"  class="result-text-large"></div>                         
</div>   
                    </div>   
                </div>   
            </div>   
   
            <div class="card features-card">   
     
   
                <h2>Features</h2>   
                <ul class="features-list">   
                    <li>   
                        <i class="fas fa-brain"></i>   
                        <div>   
                            <h3>AI Detection</h3>   
                            <p>Advanced spam detection</p>   
                        </div>   
                    </li>   
                    <li>   
                        <i class="fas fa-bolt"></i>   
                        <div>   
                            <h3>Instant Results</h3>   
                            <p>Get results immediately</p>   
                        </div>   
                </li>   
                <li>   
                    <i class="fas fa-shield-alt"></i>   
                    <div>   
                        <h3>Simple Results</h3>   
                        <p>Clear SPAM or NOT SPAM indication</p>   
                    </div>   
               </li>   
                <li>   
                    <i class="fas fa-lock"></i>   
                    <div>   
                        <h3>Private</h3>   
                        <p>Your data stays on your machine</p>   
                    </div>   
                </li>   
                </ul>   
            </div>   
        </section>   
    </main>   
   
    <footer>   
        <div class="footer-content">   
            <p>&copy; 2025 Spam Email Detector | All Rights Reserved</p>         </div>   
    </footer>   
   
    <script src="{{ url_for('static', filename='js/script.js') }}"></script>   
</body>   
</html>   
   
   
Style.css   
   
   
/* Global Styles */     
:root {   --primary-color: #4a6fa5;   --secondary-color: #166088;   --accent-color: #4caf50;   --danger-color: #f44336;   --background-color: #f5f7fa;   --card-color: #ffffff;   --text-color: #333333;   --text-light: #666666;   --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);   --transition: all 0.3s ease;   
}   
* {     margin: 
0;     padding:  
0;      
box-sizing: border
box;   
}   
body {   
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;     backgroundcolor: 
var(--background-color);
     background-image:    
250, 0.9), rgba(245, 247, 250, 0.9)),      
      linear-gradient(rgba(245, 247, 
   url("data:image/svg+xml,%3Csvg width='60' 
height='60' viewBox='0 0 60 60'   
xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%234a6fa5' 
fill-opacity='0.05'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h- 
2v4h4v2h4v4h2V6h4V4h-4zM6  
34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6  
4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");     color: var(--textcolor);     
line-height: 1.6;   
}   
a {     text-decoration: none;      
color: var(--primary-color);   
}   
/* Header and Navigation */   
.navbar  
{     display: 
flex;   
justify-content: space-between;      
align
items: center;     padding: 1.2rem 2rem;     
background-color: var(--cardcolor);     box
shadow: 0 4px 6px rgba(0, 0,  
0, 0.1);      
position: sticky;      
top: 0;     z-index:  
100;   
}     
.logo {     display: flex;     align
items: center;     fontsize: 1.5rem;     
font-weight: bold;     color: var(-
primarycolor);   
}   
.logo i {     margin-right:  
0.5rem;     font-size:  
1.8rem;   
}   
.nav-links a {     margin-left: 
1.5rem;     color: var(--textcolor);     
font-weight: 500;
     transition: 
var(--transition);     padding: 
0.5rem 0;     position:  
relative;   
}   
.nav-links a:hover, .nav-links a.active {     color: var(-
primary-color);   
}   
.nav-links a.active:after, .nav-links a:hover:after {     
content: '';     
position: absolute;     
width: 100%;     
height: 2px;   
background-color: var(--primary-color);    
bottom: 0;      
left: 0;   
}   
/* Hero Section */ .hero,  
.about-hero {      
#4a6fa5, #166088);     
background: linear-gradient(135deg, #2c3e50, 
background-size: 400% 400%;     
gradient 15s ease  
infinite;     color: white;     padding: 5rem 2rem;    
position: relative;     overflow: hidden;  }   
.hero::before, .about-hero::before {      
content:  
"";     position: 
animation: 
 text-align: center;     
absolute;   
top:  0;     left: 
0;     right: 
0;     bottom: 
0;   
background-image: url("data:image/svg+xml,%3Csvg width='100' height='100' viewBox='0 0 100 100'  
xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M11 18c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134- 
7 7 3.134 7 7 7zm48 25c3.866 0 7-3.134 7-7s-3.134-7-7-7-7 3.134-7 7 3.134 7 7 7zm-43-7c1.657 0   
3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm63 31c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3     
1.343 3 3 3zM34 90c1.657 0 3-1.343 3-3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zm56-76c1.657 0 3-1.343  3
3s-1.343-3-3-3-3 1.343-3 3 1.343 3 3 3zM12 86c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4   
4zm28-65c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm23-11c2.76 0 5-2.24 5-5s-2.24-5-5-5-5   
2.24-5 5 2.24 5 5 5zm-6 60c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm29 22c2.76 0 5-2.24 
55s2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zM32 63c2.76 0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 
5zm5713c2.76  
0 5-2.24 5-5s-2.24-5-5-5-5 2.24-5 5 2.24 5 5 5zm-9-21c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2   
.895 2 2 2zM60 91c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2zM35 41c1.105 0 2-.895 
22s.895-2-2-2-2 .895-2 2 .895 2 2 2zM12 60c1.105 0 2-.895 2-2s-.895-2-2-2-2 .895-2 2 .895 2 2 2z' 
fill='%23ffffff' fill-opacity='0.05' fill-rule='evenodd'/%3E%3C/svg%3E");     opacity: 0.7;  }   
@keyframes gradient {   
0% {   
background-position: 0% 50%;   
}      
50% {   
background-position: 100% 50%;   
}   
100% {          
background
position: 0% 50%;   
}   
}   
.hero-content, .about-hero-content {     max
width: 800px;     margin: 0  
auto;
     position: relative;   
z-index: 1;   
}   
.hero h1, .about-hero h1 {     fontsize: 
3rem;     margin-bottom:  
1rem;      
text-shadow: 0 2px 4px rgba(0, 0, 
0, 0.2);  }   
.hero p, .about-hero p {   
  font-size: 
1.3rem;     opacity: 0.9;     
max-width:  
600px;     margin: 0 auto;   
}   
/* Main Content */ 
main {     padding:  
2rem;   
}   
.detection-container {     
maxwidth: 
1200px;     margin: 0 auto;     
display: grid;
     gridtemplate
columns: 1fr;     gap:  
2rem;   
}   
@media (min-width: 768px) {     .detectioncontainer {   
grid-template-columns: 3fr 2fr;   
}   
}   
.card {      
background-color: var(--card-color);     border-radius: 12px;     
box- 
shadow: 0 10px 20px rgba(0, 0, 0, 0.05), 0 6px 6px rgba(0, 0, 0, 0.1);     
padding: 2rem;     margin-bottom: 2rem;      
box-shadow 0.3s ease;   
.card:hover {   
transition: transform 0.3s ease,   
transform: translateY(-5px);      
box-shadow: 0 15px 30px rgba(0, 0, 0, 
0.1), 0 8px 8px rgba(0, 0, 0, 0.05); }   
.card h2 {     color: var(-primary
color);     marginbottom: 1.5rem;   
font-size: 1.8rem;   
}  
/* Input Area */ .inputgroup {     
display: flex;     flex-direction: 
column;     gap: 1rem;   
}   
textarea {     
width: 100%;     min-height: 180px;     
padding: 1.2rem;     border: 1px solid #ddd;     
border-radius: 10px;     font-family: inherit;     
fontsize: 1.05rem;
     resize: vertical;
     transition: 
all 0.3s ease;     box-shadow: inset 0 1px 3px rgba(0, 
0, 0, 0.05);     background-color: rgba(255, 255, 255, 
0.9);   
}   
textarea:focus  {     outline: none;   
border-color: var(--primary-color);   
box-shadow: 0 0 0 3px rgba(74, 111, 165, 0.2), inset 0 1px 3px rgba(0, 0, 0, 0.05); 
}   
.primary-button {      
background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));     color: white;     border: none;     padding: 0.9rem 2rem;     
border-radius: 50px;     cursor: pointer;     font-weight: 600;
 display: flex;     align-items:  
center;     justify-content: center;     gap: 0.7rem;   
box-shadow: 0 4px 15px rgba(74, 111, 165, 0.4);      
position: relative;     overflow: hidden;  }   
.primary-button:hover  
{     transform: 
translateY(-2px);   
box-shadow: 0 6px 20px rgba(74, 111, 165, 0.5);  
}   
.primary-button:active  
{     transform: 
translateY(1px);   
box-shadow: 0 2px 10px rgba(74, 111, 165, 0.4); }   
.primary-button::after {   
  content: "";
 absolute;     top: -50%;     left: - 
}   
     font-size: 1.05rem;     
  transition: all 0.3s ease;   
     position:   
60%;     width: 20%;     height: 200%;     background: 
rgba(255, 255, 255, 0.2);     transform: rotate(30deg);     
transition:  
all 0.6s ease;   
}   
.primary-button:hover::after  
left: 120%;   
}   
.primary-button i {     fontsize: 
1.1rem;   
}   
/*  
Results  
.result-hidden  {      
display: none;   
}   
.result-container {    
Area  */ 
 margintop: 
2rem;     border: 1px solid 
#ddd;     border-radius:  
8px;     overflow: hidden;   
}   
.result-header {    
{      
 backgroundcolor: 
#f5f5f5;     padding: 1rem;      
border-bottom: 1px solid #ddd;   
}   
.result-header  h3  
{     margin: 
0;     color: var(-text-color);   
}   
.result-content {     padding: 2rem;
     display: flex;     
align-items: center;     justify-content: center;     
gap: 2rem;     position: relative;     overflow: 
hidden;     background-color: rgba(255, 255, 255, 
0.8);   
backdrop-filter: blur(10px); -webkit-backdrop-filter:  
blur(10px); border-radius: 10px;  border: 
1px solid rgba(255, 255, 255, 0.18);   
}  
.result-icon {     
font-size: 2.5rem;     
align-items: center;     
display: flex;     
justify-content: center;     
width: 80px;     height: 80px;     border-radius: 50%;     
background-color: white;     box-shadow: 0 8px 32px    
.result-icon:hover  
scale(1.1);   
}   
{     transform: 
.result-icon.spam i {     color:  
var(--danger-color);   
}   
.result-icon.ham i {     color:  
var(--accent-color);   
}   
.result-details {     flex: 1;     
display: flex;     justifycontent: 
center;   
}   
.result-text-large {     fontsize: 
2.2rem;     font- 
weight: 700;     margin: 0;     
padding: 1.5rem 2.5rem;     
border-radius: 8px;     textalign: 
center;     letterspacing: 2px;     
width: 100%;     display: 
inlineblock;     min-width:  
200px;      
box-shadow: 0 8px 32px 0 rgba(31, 38, 
135, 0.1);      
}   
/*  
transition: all 0.3s ease;   
Features  List  */  
.features-list {
     liststyle: 
none;   
}   
.features-list li {     display:  
flex;     gap: 1rem;      
margin-bottom: 1.5rem;   
}   
.features-list i {     font-size:  
1.5rem;     color: var(-- 
primary-color);     min-width:  
30px;     text-align: center;   
}   
.features-list h3 {     fontsize: 
1.2rem;     marginbottom: 
}      
0.5rem;  .features-list p {     
color: var(--text-light);   
}   
/* About Page Styles */ .about
content {     maxwidth: 1000px;     
margin: 0 auto;   
}   
.about-item {     display: flex;     
gap: 1.5rem;     margin
bottom: 2rem;   
}   
.about-icon {     font-size: 2rem;     
color: var(--primarycolor);     min
width: 50px;     text-align: center;   
}   
.about-details h3 {     font-size:  
1.4rem;     margin-bottom: 0.5rem;     
color: var(-- 
primary-color);   
}   
.about-details p {     color: var(--text-light);     lineheight: 1.7;   
}   
.tech-details { display: 
flex;  
flex-wrap: 
wrap; gap: 1.5rem; 
margin-bottom:  
2rem;   
}  
.tech-item {     display: flex;     flex
direction:  
column;     align-items: 
center;     gap: 0.5rem;    
calc(33.33%  - 1rem);   
}   
 width: 
.tech-icon {     font-size: 2rem;     
color:  var(--primary-color);     
margin-bottom: 0.5rem;  .model
details h3 {     fontsize: 1.3rem;     
margin: 1.5rem 0 0.5rem;     color:  
   
}   
   
   
var(--primary-color);   
}   
   
.model-details  p  {     
color:  var(--text-light);     line
height: 1.7;   
}   
   
/* Footer */ footer  
{      background-color: var(--primary
color);      color: white;     textalign: 
center;     padding: 1.5rem;     margin-top:  
2rem;   
}   
   
.footer-content {     maxwidth: 
1200px;     margin: 0 auto;     
font-size: 0.9rem;   
}   
   
/* Responsive Adjustments */   
@media (max-width: 768px) {     
.about-item {         flexdirection: 
column;   
        gap: 0.5rem;   
    }   
       
    .about-icon {         marginbottom: 
0.5rem;   
 }      
   .tech-item {         width:  
calc(50% - 1rem);   
    }   
}   
   
   
   
Script.js   
   
   
   
// Wait for the DOM to be fully loaded  
document.addEventListener('DOMContentLoaded', function() 
{   
    // Get DOM elements   
      
   
    const emailInput = document.getElementById('email-input');     const 
checkButton = document.getElementById('check-button');     const 
resultContainer = document.getElementById('result-container');     const 
resultText = document.getElementById('result-text');     const resultIcon 
= document.getElementById('result-icon-element');   
   
    //  Add  event  listener  to  the  check  button     checkButton.addEventListener('click', 
function() {   
        const emailContent = emailInput.value.trim();   
           
        // Validate input         if (emailContent === '') {              
alert('Please enter some email content to check.');              
return;   
        }   
           
        // Change button text and disable while processing          checkButton.innerHTML  =  '<i 
 class="fas  fa-spinner  fa-spin"></i>  Analyzing...';          
checkButton.disabled = true;   
           
        // Make API call to the backend          
fetch('/predict', {             method: 
'POST',             headers: {   
                'Content-Type': 'application/json',   
            },   
            body: JSON.stringify({ email_text: emailContent })   
        })   
        .then(response => {             if 
(!response.ok) {   
                throw new Error('Network response was not ok');   
            }   
            return response.json();         
})   
       .then(data => {            //  
Display  the  result            
displayResult(data);   
       })   
       .catch(error  =>  {         console.error('Error:', error);          
alert('An error occurred while analyzing the email. Please try again.');   
    })   
    .finally(() => {   
          // Reset button            checkButton.innerHTML = '<i class="fas 
fasearch"></i> Check';              checkButton.disabled = false;   
        });   
    });   
   
    // Function to display the result     function 
 displayResult(data)  {          
// Show the result container          resultContainer.classList.remove('result
hidden');   
           
      
   
        // Set result text and icon         if 
(data.is_spam) {   
            resultText.textContent  =  'SPAM';             resultText.style.backgroundColor = '#f44336';   
            resultText.style.color = 'white';   
            resultIcon.className  =  'fas  fa-exclamation-triangle';             resultIcon.style.color = 
'#f44336';   
        } else {   
            resultText.textContent = 'NOT SPAM';             resultText.style.backgroundColor = '#4caf50';              
resultText.style.color = 'white';             resultIcon.className 
= 'fas fa-check-circle';             resultIcon.style.color = 
'#4caf50';   
        }   
   
        // Smooth scroll to result          resultContainer.scrollIntoView({ 
behavior: 'smooth', block: 'center' });   
    }   
   
    // Add event listener to allow submission with Enter key     
emailInput.addEventListener('keydown',  function(event)  {         
if (event.key === 'Enter' && !event.shiftKey) {   
            event.preventDefault();   
            checkButton.click();   
        }     });   
});   
   
   
 # BACKEND   
   
   
App.py   
   
   
from flask import Flask, render_template, request, jsonify  
import tensorflow as tf import pickle   
from train_model import preprocess_text   
from tensorflow.keras.preprocessing.sequence import pad_sequences  
import os import numpy as np   
   
# Create a simple Flask app  
app = Flask(__name__)   
   
# Load the trained model and tokenizer try:      print("Loading spam detection model...")      
model  =  tf.keras.models.load_model('models/spam_detection_model.h5')      
print("Model loaded successfully")   
       
    print("Loading  tokenizer...")         
 with open('models/tokenizer.pickle',  'rb')  as  handle:         
tokenizer = pickle.load(handle)   
      
   
    print(f"Tokenizer loaded: {tokenizer.word_index}")   
       
    print("Loading  metadata...")          with 
open('models/metadata.pickle', 'rb') as handle:   
        metadata = pickle.load(handle)      
print(f"Metadata loaded: {metadata}")   
       
    print("All resources loaded successfully!") except 
Exception as e:   
    print(f"Error loading model: {e}")   
    print("Running training script to create a new model...")     
# Import and run training script if model doesn't exist     from 
train_model import train_and_save_model   
    model, tokenizer, metadata = train_and_save_model()   
   
def predict_spam(text):   
    """Analyze email text and predict if it's spam"""   
    # Preprocess the text     
processed_text = preprocess_text(text)   
      
   # Convert to sequence     sequence = 
tokenizer.texts_to_sequences([processed_text])   
      
   # Pad sequence padded = pad_sequences(sequence, maxlen=metadata['max_length'], padding='post')   
   
# Get prediction    prediction = float(model.predict(padded, verbose=0)[0][0])   
      
   # Debug print     print(f"Text: {text}")     
print(f"Processed: {processed_text}")      
print(f"Prediction score: {prediction}")   
       
    return {   
        'is_spam': bool(prediction > 0.5),   
        'spam_probability': prediction,   
        'original_text': text,   
        'processed_text': processed_text   
    }   
   
@app.route('/') def index():     return render_template('index.html')  
@app.route('/about')  def  about():      
return render_template('about.html')   
   
@app.route('/predict', methods=['POST']) def 
predict():   
    # Get data from request     data = 
request.json   
    email_text = data.get('email_text', '')   
       
     
   
    # Make prediction      result = 
predict_spam(email_text)   
       
    return jsonify(result)   
   
@app.route('/batch_predict', methods=['POST']) 
def batch_predict():     # Get data from request     
data = request.json   
    emails = data.get('emails', [])   
       
    # Make predictions      results = 
[predict_spam(email) for email in emails]   
       
    return jsonify({'results': results})   
   
@app.route('/test') 
def test(): # Test 
cases test_cases = [     
# Obvious spam   
    "CONGRATULATIONS! You've won $1,000,000! Click here to claim your prize now!",   
    "FREE VIAGRA! Best prices guaranteed! Order now!",   
 "Make money fast! Work from home! 100% guaranteed income!",   
   
# Challenging spam examples from dataset   
"URGENT! You have won a 1 week FREE membership in our £100,000 Prize Jackpot!",   
"WINNER!! As a valued network customer you have been selected to receivea £900 prize reward!",   
"SIX chances to win CASH! From 100 to 20,000 pounds txt CSH11 and send to 87575.",   
   
# Obvious non-spam   
"Hi, can we meet tomorrow at 2pm to discuss the project?",   
    "Please find attached the report for Q3 sales figures.",   
    "Don't forget to bring your laptop to the meeting."   
    ]   
       
    # Load model and tokenizer     try:   
        model_path  =  'models/spam_detection_model.h5'          
tokenizer_path = 'models/tokenizer.pickle'         metadata_path = 
'models/metadata.pickle'   
           
        print(f"Model  exists:  {os.path.exists(model_path)}")         print(f"Tokenizer  exists: 
 {os.path.exists(tokenizer_path)}")         print(f"Metadata exists: 
{os.path.exists(metadata_path)}")   
           
        # Test without preprocessing          
results_raw  =  []          
for text in test_cases:   
            #  Get  sequence  directly  without 
 preprocessing             sequence = 
tokenizer.texts_to_sequences([text.lower()])   
      
   
            padded  =  pad_sequences(sequence,  maxlen=metadata['max_length'],  padding='post')              
prediction = float(model.predict(padded, verbose=0)[0][0])   
               
            results_raw.append({   
                'text': text,   
                'prediction': 'SPAM' if prediction > 0.5 else 'NOT SPAM',   
                'probability': prediction,   
                'processed': False   
            })   
    except Exception as e:   
        print(f"Error  testing  without  preprocessing:  {e}")          
results_raw = []   
       
    # Regular test with preprocessing     results 
= []     for text in test_cases:         result 
 =  predict_spam(text)          
results.append({             'text': text,   
            'prediction': 'SPAM' if result['is_spam'] else 'NOT SPAM',   
            'probability': result['spam_probability'],   
            'processed_text': result.get('processed_text', '')         
})         return 
jsonify({   
       'with_preprocessing': results,   
       'without_preprocessing': results_raw   
   })   
   
if __name__ == '__main__':  app.run(debug=True)   
test_model.py   
   
import tensorflow as tf 
import pickle import 
numpy as np   
from train_model import preprocess_text   
from tensorflow.keras.preprocessing.sequence import pad_sequences import os   
   
def main():     # Test  
messages      
test_cases = [         #  
Obvious spam   
        "CONGRATULATIONS! You've won $1,000,000! Click here to claim your prize now!",   
        "FREE VIAGRA! Best prices guaranteed! Order now!",   
        "Make money fast! Work from home! 100% guaranteed income!",   
           
        # Obvious non-spam   
        "Hi, can we meet tomorrow at 2pm to discuss the project?",   
        "Please find attached the report for Q3 sales figures.",   
        "Don't forget to bring your laptop to the meeting."   
      
   
    ]          
try:   
        print("Loading  model  and  tokenizer...")         model_path 
 =  'models/spam_detection_model.h5'         tokenizer_path = 
'models/tokenizer.pickle'   
        metadata_path = 'models/metadata.pickle'   
           
        print(f"Model  exists:  {os.path.exists(model_path)}")         print(f"Tokenizer  exists: 
 {os.path.exists(tokenizer_path)}")         print(f"Metadata exists: 
{os.path.exists(metadata_path)}")   
           
        # Load model          model = tf.keras.models.load_model(model_path)   
        print("Model loaded successfully")   
           
        # Load tokenizer         with open(tokenizer_path,  'rb') 
 as  handle:             tokenizer  = 
 pickle.load(handle)          
print("Tokenizer loaded")   
           
        #  Load  metadata          with  
 open(metadata_path,  'rb')  as  handle:          
metadata = pickle.load(handle)   
    print(f"Metadata loaded: {metadata}")   
       
    # Test the model  print("\nTesting model on example 
messages:")   
for text in test_cases:    # 
Preprocess the text     
processed_text  = preprocess_text(text)     
print(f"\nOriginal:  
{text}")      print(f"Processed: 
{processed_text}")   
       
    # Convert to sequence      sequence = 
tokenizer.texts_to_sequences([processed_text])   
         tokens  =  [tokenizer.index_word.get(i,  '<UNK>')  for  i  in  sequence[0]]          
print(f"Tokens: {tokens}")   
               
            # Pad sequence   
            padded = pad_sequences(sequence, maxlen=metadata.get('max_length', 100), padding='post')   
               
            # Get prediction              prediction = float(model.predict(padded, verbose=0)[0][0])              
print(f"Prediction: {prediction:.6f} - {'SPAM' if prediction > 0.5 else 'NOT SPAM'}")   
           
    except  Exception  as  e:         
print(f"Error: {e}")   
   
if __name__ == "__main__":   
    main()    
     
   
   
train-model.py   
   
   
import numpy as np import 
pandas  as  pd 
 import  
tensorflow as tf   
from tensorflow.keras.preprocessing.text import Tokenizer from 
tensorflow.keras.preprocessing.sequence import pad_sequences from 
sklearn.model_selection import train_test_split import pickle import 
nltk from nltk.corpus import stopwords from nltk.stem import  
PorterStemmer import re  
import os   
   
#  Create  directory  for  saving  models  if  it 
 doesn't  exist os.makedirs('models', exist_ok=True)   
   
# Download necessary NLTK resources  
nltk.download('stopwords')   
   
def preprocess_text(text):   
    """Clean and preprocess text while preserving important spam indicators"""   
    # Convert to lowercase      
text = text.lower()   
       
    # Replace URLs with token      text = re.sub(r'http[s]?://(?:[a-zA-Z]|[0-9]|[$-_@.&+]|[!*\\(\\),]|(?:%[0
9a-fA-F][0-9a-fA-F]))+', 'URL',  
text)   
   
# Replace email addresses with token  text = 
re.sub(r'[\w\.-]+@[\w\.-]+\.\w+', 'EMAIL', text)   
# Replace phone numbers with token  text = 
re.sub(r'\b\d{3}[-.]?\d{3}[-.]?\d{4}\b', 'PHONE', text)   
   
# Replace money amounts with token   
text = re.sub(r'\$\d+(?:\.\d{2})?', 'MONEY', text)   
   
# Replace numbers with token     text  
= re.sub(r'\d+', 'NUMBER', text)   
       
    # Remove HTML tags   
    text = re.sub('<.*?>', '', text)   
       
    # Keep exclamation marks and question marks (common in spam)     text = 
re.sub('[^a-zA-Z!?]', ' ', text)   
       
    # Remove extra spaces   
    text = re.sub('\s+', ' ', text).strip()   
       
      
   
    # Tokenize     words  
= text.split()   
       
    # Remove stopwords but keep important ones     ps = 
PorterStemmer()   
    stop_words = set(stopwords.words('english')) - {'free', 'win', 'winner', 'won', 'urgent', 'important',   
'guarantee', 'guaranteed', 'limited', 'offer', 'now', 'click', 'claim'}   
    words = [ps.stem(word) for word in words if word not in stop_words]   
       
    return ' '.join(words)   
   
def load_data(filepath='data/spam.csv'):      
"""Load and prepare spam dataset"""     # Check 
if data directory exists, create if not     
os.makedirs('data', exist_ok=True)   
       
    # Check if data file exists     if not os.path.exists(filepath):         # If not, download sample data         
print(f"Data file {filepath} not found. Please download a spam dataset and place it in the data 
directory.")         print("You can use the UCI SMS Spam Collection dataset: 
https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection")         # For demonstration, create 
a small sample dataset         create_sample_dataset(filepath)   
         
try:   
        # First, try to determine format of the file     with 
open(filepath, 'r', encoding='latin-1') as f:          
first_line = f.readline().strip()   
       
    # Check if tab-separated or has header     if 
'\t' in first_line:   
     print("Loading tab-separated dataset...")   
    # Tab-separated format (original UCI SMS Spam Collection)    if 
first_line.lower().startswith(('ham', 'spam')):   
       df = pd.read_csv(filepath, encoding='latin-1', sep='\t', names=['label', 'message'])      
else:         df = pd.read_csv(filepath, encoding='latin-1', sep='\t', header=0) else:   
    print("Loading CSV dataset...")   
     #  Comma-separated  format  df  =  
pd.read_csv(filepath, encoding='latin-1')   
   
        # Make sure we have the expected columns         if 
'label' not in df.columns:   
            # Try to detect which column contains spam/ham labels             for col 
in df.columns:                 if df[col].astype(str).str.lower().isin(['ham', 
 'spam']).any():                      
print(f"Found label column: {col}")   
                    df['label']  =  df[col]                      
break   
           
        if 'message' not in df.columns:   
            # Try to find the message column (usually the longest text column)             
text_cols = df.select_dtypes(include=['object']).columns.tolist()             if  
      
   
'label' in text_cols:                 text_cols.remove('label')                           
if text_cols:   
                # Use the first non-label text column as the message                 
message_col = text_cols[0]   
                print(f"Using  {message_col}  as  message  column")                  
df['message'] = df[message_col]   
           
        # Ensure we have the necessary columns         if 'label' not in df.columns or 'message' 
not in df.columns:             raise ValueError("Could not identify label and message columns 
in the dataset")   
       
    # Convert labels to binary         if 
df['label'].dtype == 'object':   
            label_map = {'spam': 1, 'ham': 0}              
df['label'] = df['label'].str.lower().map(label_map)   
       
        print(f"Loaded dataset with {len(df)} examples ({df['label'].sum()} spam, {len(df) - df['label'].sum()}  
ham)")   
    return df   
       
    except Exception as e:         print(f"Error loading 
dataset: {e}")         print("Creating  
sample  dataset  instead...")          
create_sample_dataset(filepath)   
        return load_data(filepath)   
   
def create_sample_dataset(filepath):   
"""Create a challenging dataset with clearer spam/ham examples""" spam_examples  
= [   
    "URGENT! You have won a 1 week FREE membership in our £100,000 Prize Jackpot!",   
    "WINNER!! As a valued network customer you have been selected to receivea £900 prize reward!",   
    "SIX chances to win CASH! From 100 to 20,000 pounds txt CSH11 and send to 87575.",   
    "CONGRATULATIONS! You've won $1,000,000! Click here to claim your prize now!",     
"FREE VIAGRA! Best prices guaranteed! Order now!",   
    "Make money fast! Work from home! 100% guaranteed income!",   
    "You are a WINNER! You have been selected to receive a $1000 cash prize! To claim call   
123456789 now!",   
        "URGENT: Your account has been compromised. Click here to verify your details immediately!",   
        "You have been specially selected to receive this exclusive offer! Limited time only!",   
        "Congratulations! You've been pre-approved for a credit card with a $10,000 limit!",   
        "FREE entry into our prize draw! Text YES to 80122 to receive your prize",   
        "URGENT: We're trying to contact you regarding your vehicle's extended warranty",   
        "Hot singles in your area are waiting to meet you! Click here to see profiles",   
        "BUY NOW! Limited stock of miracle weight loss pills! Lose 20 pounds in 2 weeks!",   
        "FINAL NOTICE: Your payment is past due. Click here to avoid service termination",   
        "IMPORTANT: Your recent transaction requires verification. Click here to verify",   
        "Congratulations! You've been selected for our exclusive discount program!",   
        "ATTENTION: Your account will be suspended. Verify your information now!",   
  
   
        "Your package delivery has been delayed. Click here to reschedule delivery",          
"SPECIAL OFFER: Buy one get two free! Limited time only!"   
    ]   
       
    ham_examples = [   
        "Hi, can we meet tomorrow at 2pm to discuss the project?",   
        "Please find attached the report for Q3 sales figures.",   
        "Don't forget to bring your laptop to the meeting.",   
        "The quarterly financial report is now available for review.",   
        "I'll be working from home tomorrow due to the weather forecast.",   
        "Can you send me the updated spreadsheet when you get a chance?",   
        "The client meeting has been rescheduled to next Wednesday at 10am.",   
        "Please review the attached document and provide feedback by Friday.",   
        "We need to discuss the budget allocations for the upcoming quarter.",   
        "I've updated the presentation with the latest data from the research team.",   
        "Let me know if you need any clarification on the project requirements.",          
"The team will be having lunch at the new restaurant around the corner.",   
        "Sorry I missed your call earlier. I'll be available after 3pm today.",   
        "Can we schedule a quick call to go over the implementation details?",   
        "I'm looking forward to seeing you at the conference next month.",   
        "Thank you for your prompt response. This helps us move forward with the project.",   
        "I'll be out of office next week. Please contact Sarah for urgent matters.",   
        "Don't worry about the report. I've already submitted it to the management.",   
        "Great work on the presentation yesterday. The client was very impressed.",         "I've 
booked the meeting room for our team discussion tomorrow."   
    ]   
       
    # Combine them into a single dataset with clear labels     data = {   
        'label': ['spam'] * len(spam_examples) + ['ham'] * len(ham_examples),   
        'message': spam_examples + ham_examples   
    }   
   
# Create DataFrame  df 
= pd.DataFrame(data)   
   
# Ensure directory exists  
os.makedirs(os.path.dirname(filepath), exist_ok=True)   
   
# Save as tab-separated file to match UCI SMS Spam Collection format   
with open(filepath, 'w', encoding='utf-8') as f:     for  
label, message in zip(df['label'], df['message']):         f.write(f"{label}\t{message}\n")   
      
 print(f"Created dataset with {len(df)} examples ({len(spam_examples)} spam, {len(ham_examples)} ham)  
at {filepath}")   
    return df   
   
def build_model(vocab_size, max_length):   
    """Build and compile the model with improved architecture"""     model = 
tf.keras.Sequential([   
      
   
        tf.keras.layers.Embedding(vocab_size,  256,  input_length=max_length),         
tf.keras.layers.SpatialDropout1D(0.2),   
        tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(128, return_sequences=True)),          
tf.keras.layers.Bidirectional(tf.keras.layers.LSTM(64)),         tf.keras.layers.Dense(64, 
activation='relu'),         tf.keras.layers.Dropout(0.5),         tf.keras.layers.Dense(32, 
activation='relu'),         tf.keras.layers.Dense(1, activation='sigmoid')   
    ])   
       
    model.compile(          
optimizer=tf.keras.optimizers.Adam(learning_rate=0.001),          
loss='binary_crossentropy',   
        metrics=['accuracy', tf.keras.metrics.Precision(), tf.keras.metrics.Recall()]   
    )   
       
    return model   
   
def train_and_save_model():   
    """Train the spam detection model with improved parameters"""   
    # Load and prepare data      
df = load_data()   
       
    #  Preprocess  messages     print("Preprocessing messages...")   
    df['processed_message'] = df['message'].apply(preprocess_text)   
       
    # Split data   
    X_train, X_test, y_train, y_test = train_test_split(          df['processed_message'], 
df['label'], test_size=0.2, random_state=42, stratify=df['label']   
    )   
       
    # Tokenize text   
    max_words = 10000  # Increased vocabulary size      
max_length = 200   # Increased sequence length   
       
   tokenizer = Tokenizer(num_words=max_words, oov_token='<OOV>')    tokenizer.fit_on_texts(X_train)   
   
# Save tokenizer with open('models/tokenizer.pickle', 
'wb') as handle:   
    pickle.dump(tokenizer, handle, protocol=pickle.HIGHEST_PROTOCOL)   
   
# Convert text to sequences   
X_train_seq = tokenizer.texts_to_sequences(X_train)   
X_test_seq = tokenizer.texts_to_sequences(X_test)   
   
    # Pad sequences   
    X_train_pad = pad_sequences(X_train_seq, maxlen=max_length, padding='post')      
X_test_pad = pad_sequences(X_test_seq, maxlen=max_length, padding='post')   
       
    # Build model      model = 
build_model(max_words, max_length)   
     
   
       
    # Early stopping callback      early_stopping = 
tf.keras.callbacks.EarlyStopping(   
        monitor='val_loss',          
patience=3,   
        restore_best_weights=True   
    )   
       
    #  Train  model     print("Training 
 model...")     history  = 
 model.fit(         X_train_pad, 
 y_train,          
epochs=30,         batch_size=64,   
        validation_data=(X_test_pad, y_test),          
callbacks=[early_stopping],         verbose=1   
    )   
       
    #  Evaluate  model     print("\nEvaluating model...")   
    results = model.evaluate(X_test_pad, y_test, verbose=1)      
print(f"Test  Loss:  {results[0]:.4f}")     print(f"Test Accuracy: 
{results[1]*100:.2f}%")     print(f"Test Precision: 
{results[2]*100:.2f}%")   
    print(f"Test Recall: {results[3]*100:.2f}%")   
       
    #  Save  model     model.save('models/spam_detection_model.h5')   
       
    #  Save  metadata     metadata = {   
        'max_length': max_length,   
        'accuracy': results[1],   
        'precision': results[2],   
        'recall': results[3]   
    }   
       
   with open('models/metadata.pickle', 'wb') as handle:   
       pickle.dump(metadata, handle, protocol=pickle.HIGHEST_PROTOCOL)   
          
   print("\nModel and tokenizer saved successfully!")    return  
model, tokenizer, metadata   
   
if __name__ == "__main__": train_and_save_model()

