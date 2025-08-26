<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Md. Kobir Hossain - Web Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f0f6fc;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 30px;
            background: rgba(13, 17, 23, 0.85);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        header {
            text-align: center;
            padding: 30px 0;
            position: relative;
        }
        
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto 20px;
            background: linear-gradient(45deg, #64ffda, #00aaff);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            color: #0a192f;
            border: 4px solid #64ffda;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #64ffda, #00aaff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 700;
        }
        
        .subtitle {
            font-size: 1.4rem;
            color: #c9d1d9;
            margin-bottom: 20px;
        }
        
        .location {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            color: #8b949e;
            margin-bottom: 25px;
        }
        
        .divider {
            height: 3px;
            background: linear-gradient(90deg, transparent, #64ffda, transparent);
            margin: 30px 0;
            border: none;
        }
        
        .section {
            margin-bottom: 40px;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #64ffda;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        h2 i {
            background: linear-gradient(45deg, #64ffda, #00aaff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        p {
            margin-bottom: 15px;
            color: #c9d1d9;
            font-size: 1.1rem;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }
        
        .skill-badge {
            padding: 10px 20px;
            background: rgba(36, 113, 117, 0.3);
            border-radius: 50px;
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 500;
            border: 1px solid rgba(100, 255, 218, 0.3);
            transition: all 0.3s ease;
        }
        
        .skill-badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(100, 255, 218, 0.2);
            background: rgba(36, 113, 117, 0.5);
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            padding: 12px 25px;
            background: rgba(36, 113, 117, 0.3);
            color: #64ffda;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 500;
            transition: all 0.3s ease;
            border: 1px solid rgba(100, 255, 218, 0.3);
        }
        
        .social-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(100, 255, 218, 0.3);
            background: rgba(36, 113, 117, 0.5);
        }
        
        .quote {
            text-align: center;
            font-style: italic;
            margin-top: 40px;
            padding: 20px;
            border-radius: 10px;
            background: rgba(100, 255, 218, 0.1);
            border-left: 4px solid #64ffda;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .subtitle {
                font-size: 1.1rem;
            }
            
            .skills {
                justify-content: center;
            }
            
            .social-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="profile-pic">
                <i class="fas fa-user"></i>
            </div>
            <h1>Md. Kobir Hossain</h1>
            <div class="subtitle">Web Developer & Graphic Design Enthusiast</div>
            <div class="location">
                <i class="fas fa-map-marker-alt"></i>
                <span>Kishoreganj University, Bangladesh</span>
            </div>
        </header>
        
        <hr class="divider">
        
        <section class="section">
            <h2><i class="fas fa-user"></i> About Me</h2>
            <p>I'm a passionate web developer with a love for creating responsive, user-centered websites. I enjoy transforming ideas into real-world digital solutions using modern web technologies. Alongside coding, I explore graphic design — where creativity meets functionality.</p>
            <p>🔭 Currently working on personal and freelance web projects</p>
            <p>🌱 Learning more about backend frameworks & UI/UX design</p>
            <p>🤝 Looking to collaborate on open-source and startup ideas</p>
        </section>
        
        <hr class="divider">
        
        <section class="section">
            <h2><i class="fas fa-laptop-code"></i> Skills & Technologies</h2>
            <div class="skills">
                <div class="skill-badge"><i class="fab fa-html5"></i> HTML5</div>
                <div class="skill-badge"><i class="fab fa-css3-alt"></i> CSS3</div>
                <div class="skill-badge"><i class="fab fa-js"></i> JavaScript</div>
                <div class="skill-badge"><i class="fab fa-react"></i> React</div>
                <div class="skill-badge"><i class="fab fa-laravel"></i> Laravel</div>
                <div class="skill-badge"><i class="fas fa-database"></i> MySQL</div>
                <div class="skill-badge"><i class="fab fa-adobe"></i> Illustrator</div>
                <div class="skill-badge"><i class="fab fa-adobe"></i> Photoshop</div>
            </div>
        </section>
        
        <hr class="divider">
        
        <section class="section">
            <h2><i class="fas fa-envelope"></i> Connect With Me</h2>
            <div class="social-links">
                <a href="https://www.facebook.com/md.kobir.hossain.712952" class="social-btn" target="_blank">
                    <i class="fab fa-facebook-f"></i> Facebook
                </a>
                <a href="https://linkedin.com/in/yourprofile" class="social-btn" target="_blank">
                    <i class="fab fa-linkedin-in"></i> LinkedIn
                </a>
                <a href="mailto:your.kobir.17372@gmail.com" class="social-btn">
                    <i class="far fa-envelope"></i> Gmail
                </a>
            </div>
        </section>
        
        <div class="quote">
            <p>✨ "Code with purpose. Design with passion." ✨</p>
        </div>
    </div>

    <script>
        // Simple animation for skills on page load
        document.addEventListener('DOMContentLoaded', function() {
            const skills = document.querySelectorAll('.skill-badge');
            skills.forEach((skill, index) => {
                setTimeout(() => {
                    skill.style.opacity = 1;
                    skill.style.transform = 'translateY(0)';
                }, 100 * index);
            });
        });
    </script>
</body>
</html>
